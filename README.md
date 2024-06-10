# Algoritmo-da-mochila
Algoritmo da mochila

Você pode resolver este problema usando a técnica de programação dinâmica chamada "mochila 0-1", que é usada para maximizar o valor dos itens que podem ser colocados em uma mochila com uma capacidade limitada. Neste caso, a capacidade da mochila é 500, e o valor de cada item é dado pela lista de ações. O objetivo é selecionar um subconjunto desses itens cuja soma não ultrapasse 500 e seja a maior possível.

Aqui está um exemplo de código que implementa o algoritmo da mochila 0-1 para resolver esse problema:
Neste código, a lista valor representa o valor máximo que pode ser obtido para cada capacidade da mochila, e a lista escolhidos guarda a combinação de ações correspondente a cada valor máximo. O loop externo itera sobre todas as ações, e o loop interno itera sobre todas as capacidades da mochila de capacidade até acoes[i]. Para cada capacidade j, o código calcula o valor máximo que pode ser obtido selecionando a ação i e adicionando o valor máximo que pode ser obtido com a capacidade restante j - acoes[i]. Se esse valor máximo for maior do que o valor máximo atual de j, atualiza-se o valor máximo de j e a combinação de ações correspondente.

Ao final do código, imprime-se o valor máximo que pode ser obtido e a combinação de ações correspondente.
