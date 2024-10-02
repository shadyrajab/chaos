# Pêndulo Duplo: Explorando a Teoria do Caos com Python 🔄🎢

Este projeto é uma simulação do comportamento caótico de um pêndulo duplo utilizando Python. A animação mostra como pequenas variações nas condições iniciais podem resultar em trajetórias completamente diferentes, ilustrando a famosa **Teoria do Caos**.

## 🌀 O que é o Pêndulo Duplo?

O pêndulo duplo é um exemplo clássico de um sistema caótico. Ele consiste em dois pêndulos acoplados, e seu movimento é muito sensível a pequenas alterações nas condições iniciais. Isso significa que, mesmo com uma leve diferença nos ângulos iniciais, as trajetórias dos pêndulos rapidamente se tornam imprevisíveis.

Este comportamento é um exemplo perfeito do chamado **efeito borboleta** — a ideia de que mudanças mínimas em um sistema podem resultar em grandes diferenças ao longo do tempo.

## 📈 Sobre o Código

O código deste projeto utiliza o método de Runge-Kutta de 4ª ordem para resolver as equações diferenciais do movimento dos pêndulos. Em seguida, é utilizada a biblioteca **matplotlib** para criar uma animação que compara a evolução de dois pêndulos com uma diferença inicial extremamente pequena.

- ``double_pendulum_derivatives``: Função que define as equações diferenciais para o pêndulo duplo.
- ``y``: Vetor de estado contendo os ângulos e as velocidades angulares dos pêndulos
- ``t``: Vetor de tempo.
- ``L1`` e ``L2``: Comprimentos das hastes dos pêndulos.
- ``m1`` e ``m2``: Massas dos pêndulos.
- ``g``: Aceleração da gravidade.

### ⚙️ Requisitos

Para rodar este projeto, você precisará do Jupyter Notebook e das seguintes bibliotecas:

- **numpy**
- **scipy**
- **matplotlib**

A animação será exibida mostrando dois pêndulos começando com ângulos quase idênticos, mas que rapidamente se movem de forma completamente diferente devido à natureza caótica do sistema.

## 📊 Visualização Gráfica

A animação criada pelo script mostra claramente o comportamento caótico do sistema. As trajetórias dos dois pêndulos começam de forma quase idêntica, mas divergem rapidamente. Esta é uma ótima maneira de visualizar a sensibilidade a condições iniciais — a essência da Teoria do Caos.

## 📚 Conceitos Envolvidos

Teoria do Caos: Pequenas alterações nas condições iniciais de um sistema dinâmico podem levar a diferenças significativas na evolução do sistema.
Sistemas Dinâmicos Não-Lineares: O pêndulo duplo é um exemplo de um sistema dinâmico que é difícil de prever devido à sua não-linearidade.

## 💡 Inspiração e Resultado Final
Este projeto foi inspirado pela vontade de entender e visualizar um exemplo prático da Teoria do Caos. O pêndulo duplo é um sistema fascinante e surpreendentemente complexo, que nos lembra que o universo é cheio de beleza e imprevisibilidade.

![pendulo_caotico](https://github.com/user-attachments/assets/a1215dd8-16f3-453e-9455-05bd815ccfba)
