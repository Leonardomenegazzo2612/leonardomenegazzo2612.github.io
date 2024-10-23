codigo----->

    perder = 0
    controds = 0
    carta_veia = "escuridao"
    
    print(f'bem vindo ao meu pedra papel e tesoura sem pedra papel e tesoura')
    print(f'se voce ja sabe as regras dijite 1 se n conhece digite qualquer outra coisa')
    conhecer = input()
    if conhecer != "1":
        print(f'as regras sao simples e consiste em')
        print(f'tera uma carta na mesa por exemplo pedra')
        print(f'dai voce escolhe papel para continuar o jogo')
        print(f'se voce escolher tesoura vao perde o jogo e tera de reiniciar')
        print(f'com isso explicado boa sorte')
        print(f'')

    print(f'agora podemos comecar')
    print(f'lembre-se')
    
    while perder != 1:
        print(f'a carta na mesa eh: {carta_veia}')
        carta = input()
        while carta != "fogo"  and carta != "mago" and carta != "agua" and carta != "planta" and carta != "rato" and carta != "bigorna" and carta != "luz" and carta != "escuridao" and carta != "arqueiro" and carta != "montanha" and carta != "explorador" and carta != "sabio" and carta != "gelo" and carta != "raio" and carta != "dragao" and carta != "help":
            print(f'help para a lista de cartas')
            print(f'')
    
            carta = input()

        if carta == "help":
            print(f'opcoes de escolha')
            print(f'fogo')
            print(f'mago')
            print(f'agua')
            print(f'planta')
            print(f'rato')
            print(f'bigorna')
            print(f'luz')
            print(f'escuridao')
            print(f'arqueiro')
            print(f'montanha')
            print(f'explorador')
            print(f'sabio')
            print(f'gelo')
            print(f'raio')
            print(f'dragao')
            print(f'')
            continue
    
        elif carta_veia == "fogo":
            if carta == "planta":
                print(f'fogo queima planta')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "rato":
                print(f'um rato eh agil, mas nao o suficiente para fugir do fogo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "escuridao":
                print(f'fogo ilumia escuridao')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "arqueiro":
                print(f'eu acho que um arqueiro nao se torna imortal a fogo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "explorador":
                print(f'quente quente quente')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "gelo":
                print(f'gelo vira agua agua ganha de fogo fica a dica')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "raio":
                print(f'fogo > raio')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1

        elif carta_veia == "mago":
            if carta == "fogo":
                print(f'mago manipula fogo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "agua":
                print(f'mago manipula agua')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "rato":
                print(f'o rato roeu a roupa do mago de roma')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "luz":
                print(f'brilho <<<<<<<<<')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "arqueiro":
                print(f'bola de fogo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "explorador":
                print(f'visao magica')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "sabio":
                print(f'inteligencia nao supera magia')
                print(f'bola de fogo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1

        elif carta_veia == "agua":
            if carta == "fogo":
                print(f'serio???????')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "bigorna":
                print(f'novo item: bigorna molhada')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "luz":
                print(f'luz reflete na agua')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "arqueiro":
                print(f'arqueiro molhado, essa eh nova')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "explorador":
                print(f'vai apaga a tocha?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "gelo":
                print(f'gelo eh muito ruim')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "dragao":
                print(f'sauna criada')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
    
        elif carta_veia == "planta":
            if carta == "mago":
                print(f'mago elemental, nao fumante')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "agua":
                print(f'ja jogou pokemon?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "bigorna":
                print(f'pedra embrulha papel')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "luz":
                print(f'fotosintese')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "escuridao":
                print(f'nao fotosintese')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "montanha":
                print(f'arvores existem sabia?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "raio":
                print(f'ja jogou pokemon?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
    
        elif carta_veia == "rato":
            if carta == "agua":
                print(f'rato moiado')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "planta":
                print(f'esse tem dentes')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "escuridao":
                print(f'ratata')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "arqueiro":
                print(f'esses dentes viu')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "explorador":
                print(f'serio que cogitou isso?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "sabio":
                print(f'esse sabe correr do rato')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "dragao":
                print(f'eh so um rato que tem filho com burro')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1

        elif carta_veia == "bigorna":
            if carta == "fogo":
                print(f'hefesto')   
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "mago":
                print(f'um galo na cabeça de um mago')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "rato":
                print(f'pega o rato, pega o rato')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "escuridao":
                print(f'chumbo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "arqueiro":
                print(f'um galo na cabeça de um arqueiro')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "explorador":
                print(f'um galo na cabeça de um explorador')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "dragao":
                print(f'eu declaro que esse rato esta casado com um galo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1

        elif carta_veia == "luz":
            if carta == "fogo":
                print(f'que aja luz')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "rato":
                print(f'ratatule')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "bigorna":
                print(f'que luz linda')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "escuridao":
                print(f'que aja luz')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "sabio":
                print(f'ele nao pensa direito')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "gelo":
                print(f'derreteu')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "dragao":
                print(f'roarrrrr')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1

        elif carta_veia == "escuridao":
            if carta == "mago":
                print(f'esqueceu o feitico certo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "agua":
                print(f'se voce ver agua no escuro parabens eh um braco a menos')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "arqueiro":
                print(f'como atira no escuro?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "montanha":
                print(f'tao alta que nao chega luz')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "raio":
                print(f'cabelos para cima')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "sabio":
                print(f'muito inteligente batalhar contra o escuro')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1

        elif carta_veia == "arqueiro":
            if carta == "planta":
                print(f'uma flecha afiada, apenas')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "luz":
                print(f'nao sei exatamente o porque voce pensou nisso')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "explorador":
                print(f'explorou tanto que tomou uma flechada')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "sabio":
                print(f'sabia muito mesmo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "gelo":
                print(f'pra gelar oq?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "raio":
                print(f'flecha eletrica')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "dragao":
                print(f'uma fleecha bem colocoda')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1

        elif carta_veia == "montanha":
            if carta == "fogo":
                print(f'queima pedra bruta')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "mago":
                print(f'que magia boa')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "agua":
                print(f'tem rios na montanha...')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "bigorna":
                print(f'1:50000000')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "luz":
                print(f'que iluminaçao que a montanha tampa?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "arqueiro":
                print(f'a flecha vai aonde exatamente?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "raio":
                print(f'um para raios gigante')
                print(f'')    
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1

        elif carta_veia == "explorador":
            if carta == "planta":
                print(f'nada que uma tocha resolva')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "luz":
                print(f'isso nao cega muito bem')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "escuridao":
                print(f'ele nao ilumina muito')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "montanha":
                print(f'um explorador e uma montanha. serio?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "sabio":
                print(f'um sabia da armadilha')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "gelo":
                print(f'a explorador abe se precaver')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "raio":
                print(f'a raio n mata esse explorador')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1

        elif carta_veia == "sabio":
            if carta == "fogo":
                print(f'ele sabe correr do fogo...')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "agua":
                print(f'porque molharia um nadador')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "bigorna":
                print(f'nele galo nao existe')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "montanha":
                print(f'tinha um templo aqui...')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "gelo":
                print(f'congelo tadinho')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "dragao":
                print(f'fogo...')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "planta":
                print(f'eh pra ele fuma?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1

        elif carta_veia == "gelo":
            if carta == "mago":
                print(f'fogo agua terra e tudo que a de bom')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "planta":
                print(f'mamute')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "rato":
                print(f'no gelo ele nao corre')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "bigorna":
                print(f'vai emagar oq exatamente?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "escuridao":
                print(f'o gelo continuara sao e salvo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "montanha":
                print(f'eh de pedra n de gelo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "raio":
                print(f'dessa vez nao eh por causa do pokemon')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1

        elif carta_veia == "raio":
            if carta == "mago":
                print(f'contemplem o mago')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "agua":
                print(f'agua de raiosssssssssss')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "rato":
                print(f'ratin frito?')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "bigorna":
                print(f'pq eu quis, n tem outro motivo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "luz":
                print(f'muito claro realmente')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "sabio":
                print(f'eh sabio mas n ligeiro')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "dragao":
                print(f'um galo na cabeça da galinha')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1

        elif carta_veia == "dragao":

            if carta == "fogo":
                print(f'roarrrrrrrrrrrrrr')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "mago":
                print(f'ropao de fogo')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "planta":
                print(f'plantnha preta')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "montanha":
                print(f'so mais um dia no papheiro')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "explorador":
                print(f'vai explorar onde')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "gelo":
                print(f'isso n eh pokemon')
                print(f'')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
            elif carta == "raio":
                print(f'escuridao')
                print(f'e o fogo?')
                print(f'vc durou {controds} rodadas. parabens!')
                perder = 1
        controds += 1
        print(f'escolha sua proxima carta')
        print(f'')
    cara_veia = carta
