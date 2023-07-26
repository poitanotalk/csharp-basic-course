# Linguagem de Programação C# - Básico

## Sumário

* Apresentação
* __Módulo 1__
   * Introdução
      * História
      * Conceitos importantes
      * Preparação do ambiente para desenvolvimento
      * Primeiro programa em C#
      * Inserção de comentários
      * Variáveis
      * Conversão
      * Formatação
      * Leitura de dados
      * Inferência
* __Módulo 2__
   * Estruturas para desenvolvimento
      * Operadores aritméticos
      * Operadores relacionais
      * Operadores lógicos
      * Operadores unários
      * Estruturas de controle - _If/else_
      * Estruturas de controle - _Switch_
* __Módulo 3__
   * Desenvolvimento final
      * Leitura de notas
      * Calculadora Soma
      * Fechamento
      * Referências

## Apresentação

Bem-vindo(a) ao curso Linguagem de Programação C# - Básico!

O curso tem como objetivo transmitir o conhecimento básico no que diz respeito a linguagem C#, sua história, os principais conceitos, descrevendo seus princípios fundamentais. Ele está estruturado em três módulos.

O primeiro módulo você aprenderá a história, os principais conceitos e princípios dessa linguagem, bem como a preparação do ambiente para desenvolvimento, aprendendo a realizar a instalação da IDE (do inglês, ‘Integrated Development Environment’) utilizada para desenvolvimento dos códigos: o ‘Visual Studio’.

Nosegundomódulovocê conhecerá a estruturaparaodesenvolvimento de seus programas, abordando operadores e estruturas, e no terceiro e último verá as particularidades do desenvolvimento final. Seus estudos serão conduzidos por meio de exemplos didáticos e seguirá a montagem de algoritmos, a fim de colocarmos em prática o conteúdo abordado. Desejamos a você um bom aprendizado!

## Módulo 1

## Introdução

Para conhecer melhor a linguagem de programação C#, neste primeiro módulo
do curso, você estudará e aprenderá sobre os conceitos gerais da linguagem,
sua história e os principais conteúdos necessários que o possibilitará iniciar o
desenvolvimento de seus projetos.

## História

A linguagem C# é um tipo de linguagem relativamente nova, que fornece alguns
recursos importantes para o desenvolvimento de algoritmos, como: enumerações,
delegações e expressões lambdas, o que faz com que se tenha uma melhor
segurança para o sistema, além de um melhor desempenho.
Ela é considerada nova se compararmos a linguagem C# com as linguagens mais
clássicas, como C e C++, observe no quadro a seguir:

| Linguagem C | Linguagem C++ | Linguagem C# |
| --- | --- | --- |
| Lançada em 1942 | Lançada em 1979 | Lançada em 1998 |
| Linguagem estruturada | Linguagem híbrida | Linguagem orientada a objetos |
| Utilizada em programas que lidam diretamente com hardware, como um sistema operacional ou um driver. | A linguagem C++ é mais utilizada no desenvolvimento de alguns sistemas, como jogos de alto nível, aplicativos utilizados no mercado financeiro, sistemas operacionais, dispositivos embarcados, além de aplicativos de celulares. | Ela é usada na maioria das classes do .NET Framework |

A escolha da linguagem correta para o desenvolvimento de um projeto, dependerá de seu objetivo.

Em 1998 foi criada a linguagem C# como uma evolução da linguagem C++. Desenvolvida por Anders Hejlsberg, essa linguagem tem como objetivo uma interação simples com uma plataforma de desenvolvimento realizada pela Microsoft, chamada de .NET. Nesse caso, foram utilizados os princípios de uma linguagem criada por ele, chamada de ‘cool’ e que modificou seu nome para C#.

Duascaracterísticasespecíficasfazemcomqueessalinguagemsejamuitointeressante para uso no desenvolvimento da programação, são elas:

1. Simplicidade <br> Pois, é uma linguagem que é completamente orientada a objetos.
   
2. Flexibilidade <br> Devido a possibilidade de interação com diversos sistemas operacionais.

> __Saiba mais:__
> a sintaxe da linguagem C# é bem próxima a outros tipos de linguagens como C, C++ e Java. Uma grande vantagem da linguagem é que ela pode ser programada utilizando framework, sendo possível rodar em Linux ou Mac. Para obter mais informações sobre a história da linguagem, acesse o vídeo C# EM 5 MINUTOS: Tudo Que Você Precisa saber!

Neste tópico, apresentamos brevemente a história da Linguagem C#, que foi criada
em 1998 por Anders Hejlsberg e que representou uma evolução da Linguagem
C e C++. Além disso, evidenciamos que as principais características dela são a
simplicidade, a flexibilidade e a utilização de frameworks.

No entanto, antes de você se aprofundar nessa linguagem, é necessário dominar
alguns conceitos fundamentais de programação, os quais são abordados ao longo
do curso, considerando a atuação profissional futura. Desta forma, no próximo
tópico, você aprenderá sobre algoritmo, estrutura de dados, .NET e CLR. 

## Conceitos importantes

É essencial que você estude alguns conceitos importantes para entender melhor a base da programação de algoritmos. Esses conceitos e a função de cada parte que integra a programação, possibilitarão uma melhor compreensão do todo. Vamos lá?

1. Conceito de algoritmo <br> O conceito de algoritmo diz respeito a uma sequência que é utilizada para realizar determinadas ações. Essa sequência poderá ser realizada a partir de determinadas condições impostas pelo programador e podem ter estruturas condicionais ou de repetição.

2. Conceito de bug <br> Em casos de erros nos algoritmos, ocorre o que comumente é chamado entre os programadores de ‘bug’. De forma resumida, o algoritmo será o código criado pelo programador, que irá depender do tipo de linguagem utilizada.

3. Conceito de estrutura de dados <br> Esse conceito consiste em uma definição de regras para organização dos dados. Um exemplo dessa estrutura é o da Fila, que tem a prioridade de executar o primeiro dado recebido. É importante analisarmos também a estrutura de dados, como eles estarão dispostos no algoritmo, analisando o conteúdo que está sendo armazenado ou transferido.

4. Conceito de .NET <br> O .NET é um framework criado pela Microsoft que fornece as ferramentas necessárias para o desenvolvimento, e a linguagem C# está inserida nele. Dentro do framework .NET existe ainda o CLR (Common Language Runtime), este tem uma função intermediária de realizar a conversão do programa para a estrutura necessária para o funcionamento.
   
5. Conceito de CLR <br> O CLR é responsável por fazer uma compilação just-in-time que permite o compartilhamento de classes que também são orientadas a objetos escritos em diferentes idiomas. O .NET também é denominado de ambiente gerenciado, aquele que não precisa de um local específico para execução.

> __Saiba mais:__
> o CLR é onde o código é transformado em linguagem de máquina, sendo o local final que o projeto é executado, passando primeiro
pela linguagem intermediária e posteriormente para o CLR. Ele facilita a interação entre as linguagens, fazendo com que objetos
de linguagens diferentes consigam se comunicar uns com os outros, ou seja, ter um comportamento integrado. Esse tipo de
integração se torna possível, pois os compiladores de um sistema comum, seguem como regra o tempo de execução.

Agora que você já conheceu a história, os principais conceitos sobre programação de algoritmos e a diferença entre as linguagens C, C++ e C#, você verá sobre a preparação do ambiente para o desenvolvimento de seu projeto. Acompanhe.

