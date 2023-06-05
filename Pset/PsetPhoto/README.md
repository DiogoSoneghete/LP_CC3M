# PHOTOSHOP - Questões

### Questão 1)

> - altura: 1
> - largura: 4
> - pixels: [29, 89, 136, 200]

#### se você passar essa imagem pelo filtro de inversão, qual seria o output esperado?

##### Calculando:

Fórmula utilizada:
- c = 255 - a

**(c = cor invertida | a = cor original)** 

**Resultado:** 
- c = 255 - 29 = 226
- c = 255 - 89 = 166
- c = 255 - 136 = 119
- c = 255 - 200 = 55


Explicação: Temos que o máximo que podemos chegar nos numeros definidos é 255 (Preto Total).

Para invertermos as cores utilizamos o cálculo com a cor total e subtraindo a cor utilizada assim achamos o inverso da cor desejada.


### Questão 2)

> #### faça a depuração e, quando terminar, seu código deve conseguirpassar em todos os testes do grupo de teste TestInvertida (incluindo especificamente o que você acabou de criar). Execute seu filtro de inversão na imagem test_images/bluegill.png, salve o resultado como uma imagem PNG e salve a imagem em seu repositório GitHub.

**Resultado:**

![bluegill](https://github.com/DiogoSoneghete/LP_CC3M/assets/103038064/6ebfa771-568a-483a-88a1-b992a22e4403)


### Questão 3)

> #### Qual será o valor do pixel na imagem de saída no local indicado pelo destaque vermelho?

**Resultado:** Como temos pixels iguais a zero, eu relevei a conta destes pixels.
Para entendermos o cálculo primeiro temos que ter em mente o local onde cada um se inicia.
- Aqui como definido em Kernel, começamos do canto superior esquerdo e contamos através das linhas de x e y.
- Definido pelo pixel temos o pixel central como padrão, sendo ele o x,y inicial.

 Logo após fazemos o nosso calculo baseado na fórmula:

**Ox,y =Ix,y × Kx,y**

Após aplicarmos a fórmula em todas as posições, nós somamos e obtemos o resultado esperado que deverá sera 32,76 ou aproximadamente 33, usando arredondamento.


![Calc](https://github.com/DiogoSoneghete/LP_CC3M/assets/103038064/4f01a515-3b48-463d-83ea-9246a5d44bcf)
