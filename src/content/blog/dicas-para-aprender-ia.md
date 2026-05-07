---
title: "Diquinhas para aprender IA"
description: "Perguntei ao oráculo e ele respondeu: um roteiro de estudos para (tentar) compreender Machine Learning!"
pubDate: "2026-05-06"
updatedDate: "2026-05-07"
cover: "../../assets/computador-ia.png"
---

Fiz a seguinte pergunta para meu amigo, o Rodrigo:

> _Por onde devo começar para aprender Machine Learning?_

## A resposta

O ideal seria você entender bem como funcionam os algoritmos básicos de ML (Machine Learning) antes, então você precisa ter a seguinte base:

- **Cálculo** - vetor gradiente, derivadas, derivadas parciais.
- **Álgebra linear** - vetores, produto matricial.
- **Probabilidade** - o suficiente para entender probabilidade condicional, acho que é suficiente
  e entender melhor como funciona ML.

A seguir, eu diria pra seguir um caminho de estudos, tá? Porque essas coisas são muito dependentes:

1. **Regressão Linear/Logística** - aqui você vai entender o que é treinar um modelo, a ideia é aprender o algoritmo de gradiente descendente, funções de ativação, softmax e definir problemas de regressão x classificação.
2. **Redes Neurais** - algoritmos como forward e backpropagation, isso é a base de tudo pra treinar modelo e fazer inferencia
3. **Redes Convolucionais** - tipo de rede neural especifica pra treinar modelos em cima de imagens. Aqui voce vai aprender a extrair features de imagens e tomar decisões com base nisso.

não vou dizer que é facil e rapido, mas dá pra aprender.

> [O <mark>learning from data</mark> é um bom livro pra se entender esses básicos.](<https://github.com/zaferemreocak/machine-learning/blob/master/Yaser%20S.%20Abu-Mostafa%2C%20Learning%20from%20Data%2C%20a%20Short%20Course%20(2012).pdf>)

Ele vai atá redes neurais; tem bastante coisa teórica (VC dimension e afins) que você pode ignorar. Para redes convolucionais, recomendo alguma aula no Youtube.

> <mark>[Tem essa playlist de Stanford que é ótima](https://www.youtube.com/watch?v=2fq9wYslV0A&list=PLoROMvodv4rOmsNzYBMe0gJY2XS8AQg16)</mark>, de um curso de Visão Computacional mesmo. Lembra a disciplina de Deep Learning da [Nina](https://www.ime.usp.br/~nina/).

### Sobre a Implementação

É importante ter domínio de algumas coisas, tipo saber programar em Python e conseguir ler a documentação de algumas bibliotecas:

- **Numpy** - cálculos matemáticos, produto matricial, etc, é super otimizada.
- **Pandas** - se precisar mexer com dados tabulares, dataframes.
- **Matplotlib** - se precisar plotar gráficos.
- **Pytorch** - biblioteca clássica pra treinar modelos.

Essas bibliotecas têm boas documentações e são bem famosas, então tudo você encontra na internet ou consegue pedir pra IA.

No Pytorch especificamente, se você fosse treinar uma rede convolucional pra um modelo de visão, na própria doc eles ensinam a fazer isso com um dataset simples:

> <mark>[Aqui eles treinam um classificador](https://docs.pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html).</mark>
