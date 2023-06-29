# Mandelbrot

 > Criando um Mandelbrot utilizando HTML

![Mandelbrot](https://github.com/Sofia-Magalhaes/Mandelbrot/assets/52801509/58f814e3-4912-49a3-9a03-ec8ac676b4f5)


# O que é um Mandelbrot?
O conjunto de Mandelbrot é um conjunto de números complexos que exibe um comportamento interessante quando iterados através de uma fórmula matemática específica. Ele foi descoberto pelo matemático polonês-francês Benoit Mandelbrot e é frequentemente representado graficamente como uma imagem colorida ou em preto e branco.

Para entender como o conjunto de Mandelbrot é gerado, primeiro precisamos entender o conceito de números complexos. Um número complexo é uma combinação de uma parte real e uma parte imaginária, representada como a + bi, onde "a" é a parte real, "b" é a parte imaginária e "i" é a unidade imaginária (√-1).

A fórmula usada para gerar o conjunto de Mandelbrot é a seguinte:

> Zₙ₊₁ = Zₙ² + C

Onde Zₙ é um número complexo que começa com o valor zero e C é um número complexo que representa a coordenada no plano complexo. A ideia é iterar essa fórmula repetidamente para cada ponto C no plano complexo e verificar se o valor de Zₙ permanece limitado (não explode para o infinito) ou escapa para o infinito. Se o valor de Zₙ permanecer limitado após um número suficientemente grande de iterações, então o ponto C pertence ao conjunto de Mandelbrot.

Para gerar uma imagem do conjunto de Mandelbrot, calculamos essa iteração para cada pixel em uma grade no plano complexo e atribuímos uma cor com base na rapidez com que o valor de Zₙ escapa para o infinito. Os pontos dentro do conjunto de Mandelbrot são geralmente coloridos em preto, enquanto os pontos fora do conjunto são coloridos de acordo com uma paleta de cores.

A imagem resultante exibe uma forma fractal altamente detalhada e intrincada, com estruturas repetidas em várias escalas. Essas estruturas são conhecidas como fractais, que são objetos geométricos complexos que exibem auto-similaridade, o que significa que eles possuem detalhes semelhantes em diferentes níveis de ampliação.

O conjunto de Mandelbrot é uma das descobertas mais famosas e estudadas na área da matemática e fractais. Sua beleza visual e complexidade matemática o tornaram um tema fascinante para exploração e apreciação tanto na matemática quanto na arte

##  Código retirado do canal Brainxyz 

> https://youtu.be/mzizK6ms-gY
