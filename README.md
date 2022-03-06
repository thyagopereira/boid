# Boids

Boids é um conceito proposto por Craig Reynolds em 1986 para estudos voltados ao ramo da [A-life](https://pt.wikipedia.org/wiki/Vida_artificial) ou vida artifical.
Basicamente no que diz respeito á A-life, buscasse entender comportamentos biologicos por meio do estudado desses comportamentos em simulações artificiais computadorizadas. Trata-se de um ramo da Inteligẽncia artificial que se enquadra em mutuo aprendizado entre as áreas da ciência da computação e da biologia.
Este estudo e simulação tem como objetivo, aplicar o conceito de processamento multithreading, utilizando a linguagem golang. O uso de go routines permite a execução concorrente do precesso, de modo a melhor aproveitar o hardware do dispositivo, criando uma simulação mais eficaz.

__Boids__
- Boids basicamente são simulações do comportamento de agrupamento de passáros durante um vôo [Flocking Behaviour](https://en.wikipedia.org/wiki/Flocking_(behavior)).
- Mais sobre o comportamento observado nos passáros e simulado nos Boids pode ser encontrado [aqui](https://en.wikipedia.org/wiki/Boids).

__Execução do programa__
- Clone esse repositório para seu dispositivo.
- Se estiver usando ubuntu, basta ir ao diretório e utilizar o comando ``./boid`` para utilizar o executável.
- Caso não esteja utilizando o ubuntu, deve-se instalar o go neste [link](https://go.dev/).
- Instale o Ebiten como uma biblioteca para o Go, seguindo as [instruções](https://ebiten.org/documents/install.html).
- Compile o arquivo com o comando ``go build main.go boid.go vector2d.go``
- Basta utilizar o execútavel.

![](https://repository-images.githubusercontent.com/258305543/28971980-92d2-11ea-8a66-4d0d91c0e790)
![](https://miro.medium.com/max/1400/0*3VX77enRMl6yJOOc.jpg)

Aproveite os boids.
