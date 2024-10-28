codigo ----->

def mostrar_cartas():
    cartas_disponiveis = [
        "fogo", "mago", "agua", "planta", "rato", "bigorna", "luz",
        "escuridao", "arqueiro", "montanha", "explorador", "sabio", "gelo",
        "raio", "dragao"
    ]
    print()
    print("Opções de escolha:")
    print("fogo, mago, agua, planta, rato, bigorna, luz, escuridao, arqueiro, montanha, explorador, sabio, gelo, raio, dragao")
    print()

def perder_jogo():
    print(f'vc durou {controds} rodadas. parabens!')

regras = {
    "fogo": ["planta", "rato", "escuridao", "arqueiro", "explorador", "gelo", "raio"],
    "mago": ["fogo", "agua", "rato", "luz", "arqueiro", "explorador", "sabio"],
    "agua": ["fogo", "bigorna", "luz", "arqueiro", "explorador", "gelo", "dragao"],
    "planta": ["mago", "agua", "bigorna", "luz", "escuridao", "montanha", "raio"],
    "rato": ["agua", "planta", "escuridao", "arqueiro", "explorador", "sabio", "dragao"],
    "bigorna": ["fogo", "mago", "rato", "escuridao", "arqueiro", "explorador", "dragao"],
    "luz": ["fogo", "rato", "bigorna", "escuridao", "sabio", "gelo", "dragao"],
    "escuridao": ["mago", "agua", "arqueiro", "montanha", "raio", "sabio"],
    "arqueiro": ["planta", "luz", "explorador", "sabio", "gelo", "raio", "dragao"],
    "montanha": ["fogo", "mago", "agua", "bigorna", "luz", "arqueiro", "raio"],
    "explorador": ["planta", "luz", "escuridao", "montanha", "sabio", "gelo", "raio"],
    "sabio": ["fogo", "agua", "bigorna", "montanha", "gelo", "dragao", "planta"],
    "gelo": ["mago", "planta", "rato", "bigorna", "luz", "escuridao", "raio"],
    "raio": ["fogo", "mago", "agua", "planta", "rato", "bigorna", "montanha"],
    "dragao": ["fogo", "mago", "agua", "planta", "rato", "luz", "explorador"]
}

perder = 0
controds = 0
carta_veia = "escuridao"

print('Bem-vindo ao meu pedra, papel e tesoura sem pedra, papel e tesoura!')
print('Se você já sabe as regras, digite 1; se não, digite qualquer outra coisa:')
conhecer = input()

if conhecer != "1":
    print("As regras são simples")
    print("voce tera varias opçoes de carta (que pode ser assesado pela funçao help)")
    print("e tera de escolher uma que ganhe da carta da mesa")
    print("Escolha uma carta que continue o jogo. Boa sorte!")
    print()

print("Agora podemos começar! Lembre-se:")

while perder != 1:
    print(f'A carta na mesa é: {carta_veia}')
    carta = input("Escolha sua carta: ")
    print()

    if carta == "help":
        mostrar_cartas()
        continue

    elif carta not in regras:
        print("Carta inválida. Digite 'help' para ver a lista de cartas disponíveis.")
        continue
    
    if carta not in regras[carta_veia] and carta != carta_veia:
        carta_veia = carta
        controds += 1
    else:
        perder_jogo()
        perder = 1
