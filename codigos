from time import sleep
import random
cor = ''
limpar = ''
j = 0
final = '{}VAI INICIAR{}'.format(cor, limpar)
pc = 0
AA = ' '
AB = ' '
AC = ' '
BA = ' '
BB = ' '
BC = ' '
CA = ' '
CB = ' '
CC = ' '

#Estrutura de repetição para sempre jogar novamente
while (j == 0):

#Começando com os espaços em branco

    print('\n' * 25)
    print('          COLUNAS')
    print('     1       2      3')
    print('         |      |')
    print('         |      |')
    print('1     {}{}{}  |  {}{}{}   |  {}{}{}'.format(cor, AA, limpar, cor, AB, limpar, cor, AC, limpar))
    print(' --------|------|--------')
    print('2     {}{}{}  |  {}{}{}   |  {}{}{}   LINHAS'.format(cor, BA, limpar, cor, BB, limpar, cor, BC, limpar))
    print(' --------|------|--------')
    print('3     {}{}{}  |  {}{}{}   |  {}{}{}'.format(cor, CA, limpar, cor, CB, limpar, cor, CC, limpar))
    print('         |      |')
    print('         |      |')
    print('\n' * 7)
    print(final)
    print('Aguarde...')
    sleep(3)

    pc = 0
    AA = ' '
    AB = ' '
    AC = ' '
    BA = ' '
    BB = ' '
    BC = ' '
    CA = ' '
    CB = ' '
    CC = ' '



#Para fechar o jogo quando tivermos um ganhador
    final = '...'
    while (final == '...'):

        # Tabuleiro
        print('\n' * 25)
        print('          COLUNAS')
        print('     1       2      3')
        print('         |      |')
        print('         |      |')
        print('1     {}{}{}  |  {}{}{}   |  {}{}{}'.format(cor, AA, limpar, cor, AB, limpar, cor, AC, limpar))
        print(' --------|------|--------')
        print('2     {}{}{}  |  {}{}{}   |  {}{}{}   LINHAS'.format(cor, BA, limpar, cor, BB, limpar, cor, BC, limpar))
        print(' --------|------|--------')
        print('3     {}{}{}  |  {}{}{}   |  {}{}{}'.format(cor, CA, limpar, cor, CB, limpar, cor, CC, limpar))
        print('         |      |')
        print('         |      |')
        print('\n' * 7)

#Pedindo para o jogador selecionar um espaço
        linha = int(input('DIGITE A LINHA: '))
        coluna = int(input('DIGITE A COLUNA: '))

#Identificando qual foi o espaço selecionado pelo jogador
        if linha == 1:
            if coluna == 1 and AA == ' ':
                AA = 'x'
            if coluna == 2 and AB == ' ':
                AB = 'x'
            if coluna == 3 and AC == ' ':
                AC = 'x'

        if linha == 2:
            if coluna == 1 and BA == ' ':
                BA = 'x'
            if coluna == 2 and BB == ' ':
                BB = 'x'
            if coluna == 3 and BC == ' ':
                BC = 'x'

        if linha == 3:
            if coluna == 1 and CA == ' ':
                CA = 'x'
            if coluna == 2 and CB == ' ':
                CB = 'x'
            if coluna == 3 and CC == ' ':
                CC = 'x'

        print('\n' * 25)
        print('          COLUNAS')
        print('     1       2      3')
        print('         |      |')
        print('         |      |')
        print('1     {}{}{}  |  {}{}{}   |  {}{}{}'.format(cor, AA, limpar, cor, AB, limpar, cor, AC, limpar))
        print(' --------|------|--------')
        print('2     {}{}{}  |  {}{}{}   |  {}{}{}   LINHAS'.format(cor, BA, limpar, cor, BB, limpar, cor, BC, limpar))
        print(' --------|------|--------')
        print('3     {}{}{}  |  {}{}{}   |  {}{}{}'.format(cor, CA, limpar, cor, CB, limpar, cor, CC, limpar))
        print('         |      |')
        print('         |      |')
        print('\n' * 7)

        sleep(1)

#O COMPUTADOR DEVE JOGAR:
#Estratégias e possibilidades pré-estabelecidas de jogadas para o computador
        if AB == 'o' and AC == 'o' and AA == ' ':
            AA = 'o'
        elif BA == 'o' and BC == 'o' and AA == ' ':
            AA = 'o'
        elif BB == 'o' and CC == 'o' and AA == ' ':
            AA = 'o'
        elif AA == 'o' and AC == 'o' and AB == ' ':
            AB = 'o'
        elif CB == 'o' and BB == 'o' and AB == ' ':
            AB = 'o'
        elif AA == 'o' and AB == 'o' and AC == ' ':
            AC = 'o'
        elif CC == 'o' and BC == 'o' and AC == ' ':
            AC = 'o'
        elif CA == 'o' and BB == 'o' and AC == ' ':
            AC = 'o'
        elif AA == 'o' and CA == 'o' and BA == ' ':
            BA = 'o'
        elif BC == 'o' and BB == 'o' and BA == ' ':
            BA = 'o'
        elif AB == 'o' and CB == 'o' and BB == ' ':
            BB = 'o'
        elif CA == 'o' and AC == 'o' and BB == ' ':
            BB = 'o'
        elif BA == 'o' and CA == 'o' and BB == ' ':
            BB = 'o'
        elif AA == 'o' and CC == 'o' and BB == ' ':
            BB = 'o'
        elif BA == 'o' and BB == 'o' and BC == ' ':
            BC = 'o'
        elif AC == 'o' and CA == 'o' and BC == ' ':
            BC = 'o'
        elif AA == 'o' and BA == 'o' and CA == ' ':
            CA = 'o'
        elif CB == 'o' and CC == 'o' and CA == ' ':
            CA = 'o'
        elif BB == 'o' and AC == 'o' and CA == ' ':
            CA = 'o'
        elif CA == 'o' and CC == 'o' and CB == ' ':
            CB = 'o'
        elif AB == 'o' and BB == 'o' and CB == ' ':
            CB = 'o'
        elif CA == 'o' and CB == 'o' and CC == ' ':
            CC = 'o'
        elif AC == 'o' and BC == 'o' and CC == ' ':
            CC = 'o'
        elif AA == 'o' and BB == 'o' and CC == ' ':
            CC = 'o'

        elif AB == 'x' and AC == 'x' and AA == ' ':
            AA = 'o'
        elif BA == 'x' and BC == 'x' and AA == ' ':
            AA = 'o'
        elif BB == 'x' and CC == 'x' and AA == ' ':
            AA = 'o'
        elif AA == 'x' and AC == 'x' and AB == ' ':
            AB = 'o'
        elif CB == 'x' and BB == 'x' and AB == ' ':
            AB = 'o'
        elif AA == 'x' and AB == 'x' and AC == ' ':
            AC = 'o'
        elif CC == 'x' and BC == 'x' and AC == ' ':
            AC = 'o'
        elif CA == 'x' and BB == 'x' and AC == ' ':
            AC = 'o'
        elif AA == 'x' and CA == 'x' and BA == ' ':
            BA = 'o'
        elif BC == 'x' and BB == 'x' and BA == ' ':
            BA = 'o'
        elif AB == 'x' and CB == 'x' and BB == ' ':
            BB = 'o'
        elif CA == 'x' and AC == 'x' and BB == ' ':
            BB = 'o'
        elif BA == 'x' and CA == 'x' and BB == ' ':
            BB = 'o'
        elif AA == 'x' and CC == 'x' and BB == ' ':
            BB = 'o'
        elif BA == 'x' and BB == 'x' and BC == ' ':
            BC = 'o'
        elif AC == 'x' and CA == 'x' and BC == ' ':
            BC = 'o'
        elif AA == 'x' and BA == 'x' and CA == ' ':
            CA = 'o'
        elif CB == 'x' and CC == 'x' and CA == ' ':
            CA = 'o'
        elif BB == 'x' and AC == 'x' and CA == ' ':
            CA = 'o'
        elif CA == 'x' and CC == 'x' and CB == ' ':
            CB = 'o'
        elif AB == 'x' and BB == 'x' and CB == ' ':
            CB = 'o'
        elif CA == 'x' and CB == 'x' and CC == ' ':
            CC = 'o'
        elif AC == 'x' and BC == 'x' and CC == ' ':
            CC = 'o'
        elif AA == 'x' and BB == 'x' and CC == ' ':
            CC = 'o'

#Verificando um empate após uma jogada pré-estabelecida
        if AA != ' ' and AB != ' ' and AC != ' ' and BA != ' ' and BB != ' ' and BC != ' ' and CA != ' ' and CB != ' ' and CC != ' ':
            final = '{}EMPATE{}'.format(cor, limpar)
            break

#Jogada aleatória quando não se tem uma estratégia ou possibilidade pré-estabelecida para o computador
        while (pc != ' '):
            lista = [11, 12, 13, 21, 22, 23, 31, 32, 33]
            n = random.choice(lista)
            if n == 11:
                pc = AA
            if n == 12:
                pc = AB
            if n == 13:
                pc = AC
            if n == 21:
                pc = BA
            if n == 22:
                pc = BB
            if n == 23:
                pc = BC
            if n == 31:
                pc = CA
            if n == 32:
                pc = CB
            if n == 33:
                pc = CC

        else:
            if n == 11 and AA == ' ':
                AA = 'o'
            if n == 12 and AB == ' ':
                AB = 'o'
            if n == 13 and AC == ' ':
                AC = 'o'
            if n == 21 and BA == ' ':
                BA = 'o'
            if n == 22 and BB == ' ':
                BB = 'o'
            if n == 23 and BC == ' ':
                BC = 'o'
            if n == 31 and CA == ' ':
                CA = 'o'
            if n == 32 and CB == ' ':
                CB = 'o'
            if n == 33 and CC == ' ':
                CC = 'o'

#Verificando um empate após uma jogada aleatória
        if AA != ' ' and AB != ' ' and AC != ' ' and BA != ' ' and BB != ' ' and BC != ' ' and CA != ' ' and CB != ' ' and CC != ' ':
            final = '{}EMPATE{}'.format(cor, limpar)
            break

#Identificando um ganhador (quando tiver)
        if AA == AB == AC:
            if AA == 'x':
                final = 'VOCÊ {}GANHOU{}'.format(cor, limpar)
            elif AA == 'o':
                final = 'VOCÊ {}PERDEU{}'.format(cor, limpar)
        if AA == BA == CA:
            if AA == 'x':
                final = 'VOCÊ {}GANHOU{}'.format(cor, limpar)
            elif AA == 'o':
                final = 'VOCÊ {}PERDEU{}'.format(cor, limpar)
        if AA == BB == CC:
            if AA == 'x':
                final = 'VOCÊ {}GANHOU{}'.format(cor, limpar)
            elif AA == 'o':
                final = 'VOCÊ {}PERDEU{}'.format(cor, limpar)
        if AB == BB == CB:
            if BB == 'x':
                final = 'VOCÊ {}GANHOU{}'.format(cor, limpar)
            elif BB == 'o':
                final = 'VOCÊ {}PERDEU{}'.format(cor, limpar)
        if BA == BB == BC:
            if BB == 'x':
                final = 'VOCÊ {}GANHOU{}'.format(cor, limpar)
            elif BB == 'o':
                final = 'VOCÊ {}PERDEU{}'.format(cor, limpar)
        if CA == BB == AC:
            if BB == 'x':
                final = 'VOCÊ {}GANHOU{}'.format(cor, limpar)
            elif BB == 'o':
                final = 'VOCÊ {}PERDEU{}'.format(cor, limpar)
        if CA == CB == CC:
            if CC == 'x':
                final = 'VOCÊ {}GANHOU{}'.format(cor, limpar)
            elif CC == 'o':
                final = 'VOCÊ {}PERDEU{}'.format(cor, limpar)
        if AC == BC == CC:
            if CC == 'x':
                final = 'VOCÊ {}GANHOU{}'.format(cor, limpar)
            elif CC == 'o':
                final = 'VOCÊ {}PERDEU{}'.format(cor, limpar)
        print('\n' * 7)
