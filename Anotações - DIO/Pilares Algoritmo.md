# Pilares algoritmo

#### **Como construir um algoritmo?**

* Compreensão do problema
  * pontos mais importantes
* Definição dos dados de entrada
  * dados fornecidos e cenário
* Definir processamento
  * cálculos e Restrições
* Definição dos dados de saída
  * resultado após o processamento
* Utilizar um método de construção
  * construção e refinamento do algoritmo
* Teste e Diagnóstico

#### **Construção de um algoritmo**

* Narrativa
  * utilização da linguagem natural
* Fluxograma
  * utilização de símbolos pré definidos
* Pseudocódigo
  * portugol

#### **O que é lógica de programação?**

* a lógica é uma forma de pensamento estruturada que auxilia determinar o que é verdadeiro ou não.

#### **Técnicas de lógica de programação**

* Técnica linear
  * modelo tradicional
  * não tem vínculo
    * estrutura hierárquica
    * programação de computadores
  * execução sequenciada
  * recursos limitados
  * única dimensão
  * **ex:** acordo, desço as escadas, preparo meu café e leio meu jornal
* Técnica estruturada
  * organização, disposição e ordem dos elementos essenciais que compõem um corpo (concreto ou abstrato)
  * objetivo:
    * escrita
      * programa
    * entendimento
    * validação
    * manutenção
      * facilitador
  * Tem escolhas
  * **Ex:** acordo, faço um café ou um suco e depois eu leio meu jornal
* Técnica modular
  * controlada por um conjunto de regras
  * dados de entrada
  * processo de transformação
  * dados de saída
  * metas:
    * simplificação
    * decompor o problema
    * verificação do módulo
  * detalhadas
  * **Ex:** para que eu acorde eu preciso tirar o descansa-olho, sentar na cama, levantar da cama, descer a escada…

#### **Tipologia e variáveis** 

* numéricos 
  * inteiro
  * reais (-5,5 ; -4,5; 0; 1…)
* caracteres
  * 1; *, A, !, ?, (, a…
* lógicos
  * booleano
    * verdadeiro - 1
    * falso - 0 

#### Variáveis

* é um tipo de estrutura mutável, ela pode variar dentro do seu valor
* inconstante
* pode assumir qualquer valor dentro de um determinado conjunto de valores
* se receber inteiro ela vai sair inteiro
* regras:
  * atribua uma ou mais caractere 
  * primeira letra - não número
  * sem espaços em branco
  * vedado
    * utilização de palavras reservadas
  * caracteres e números
* possui um papel, seja eles:
* ação 
  * modifica o estado do programa
* controle
  * vigiada, utilizada para o controle de alguma estrutura

#### **Instruções primitivas**

* Irão determinar as ações que iremos processar e tratar esses dados
* Cálculos matemáticos
  * variáveis 
  * constante
* Operadores

#### **Estruturas condicionais e operadores**

* se uma condição que se satisfeita, executa uma determinada instrução

* tipos de estruturas

  * **estrutura condicional simples:**
    * condição → operação
  * **estrutura condicional composta:**
    * condição → exceção
                     ↓
              operação
  * **encadeada**
    * condição → condição → exceção
            ↓                    ↓
      operação     operação

* operadores relacionais

  | Operadores relacionais |   Significado    |
  | :--------------------: | :--------------: |
  |           =            |     igual a      |
  |          < >           |   diferente de   |
  |           <            |    menor que     |
  |           >            |    maior que     |
  |           <=           | menor ou igual a |
  |           >=           | maior ou igual a |

* operadores lógicos
  *  AND
    * todas as condições devem estar satisfeitas
  * OR
    * apenas uma condição for verdadeira
  * NOT
    * inverte o resultado lógico

#### **Estruturas de repetição**

- repete a condição
- laço, repetição, loop…
- condição de parada 
  - número de repetição
  - condição a ser satisfeita
- vantagens
  - redução de linhas
  - compreensão facilitada
  - redução de erro
- existe mais de uma estrutura de repetição
- enquanto … faça
  - teste lógico: início
  - número de repetições: indefinido
- repita … até
  - teste lógico: final
  - número de repetições: indefinido
- para … de … até … faça
  - teste lógico: início
  - número de repetições: definido

#### **Vetores e** **matrizes**

* um vetor é uma variável que possui uma sequência, um tamanho pré-fixado que irá receber n valores
* matriz unidimensional
* matriz:
  * coleção de variáveis 
  * contíguas em memória (armazenadas na memória do computador)
  * índices
* definição:
  * vetor conjunto [1 .. 8] < inteiro >
  * vetor[15]
  * Vetor = []

#### Funções

* subalgoritmo, subprograma, método, bloco, sub-rotina…
* vai implicar de um elemento A a um elemento do conjunto B
* são blocos de instruções que realizam tarefas específicas
* modularização do problema
* código mais claro e conciso]reutilização de código
* identificados por nomes e parâmetros
* variação local são utilizadas apenas dentro da função e são destruídas ao encerrar a função
* Exemplo:

```
funcao mediaescolar(nota1, nota2)
​	resultado = 0
​	resultado = (nota1 + nota2) / 2
​	retorne resultado
fim funcao
—---------------------------------------
​	aluno1 = mediaescolar(nota11, nota21)
​	aluno2 = mediaescolar(nota12, nota22)
​	aluno3 = mediaescolar(nota13, nota23)
```

#### **Instruções de entrada/saída**

inserção e recebimento de dados do mundo real, por meio de ação de alguma interface

existem dois tipos de saída:

* programada
  * condicional
    * aguarda o dispositivo
  * interrupção
    * definida pelos periféricos

* para toda saída existe casos

  - bem sucedidos 

  - erro de sintaxe ou semântica

  - erro com a interface 

  - erro de programação

#### **Introdução às linguagens de programação**

* método padronizado composto por um conjunto de regras sintáticas e semânticas
* problemas computacionais:
  * **problema de decisão**
    * problemas de caráter lógico - sim ou não
    * pertencimento
    * ex: dado um número n inteiro positivo, determine se n é primo.
  * **problema de busca**
    * relacionamento binário
    * objetivo
      * semelhante ao nome (busca)
      * x está em A?
    * recorrente em teoria de grafos
      * ex: clique
  * **problema de otimização**
    * maximizar ou minimizar uma função
* código fonte
  * traduzido
  * interpretado

#### **Como um computador entende um programa?**

* um programa é um amontoado de palavras se não for possível que o computador entenda
* código fonte
  * traduzido 
    * geração do programa objeto
    * execução do programa objeto
    * mais rápidas 
    * programas menores
  * interpretado
    * programa fonte é executado diretamente
    * maior flexibilidade

#### Características de um programa

* **legibilidade** 
  * facilidade de leitura
  * compreensão
  * ortogonalidade
  * definição adequada das estruturas
* **redigibilidade**
  * poder conflitar com a legibilidade
  * ortogonalidade
  * simplicidade da escrita
  * suporte à abstração
  * reuso do código
  * expressividade
* **confiabilidade**
  * verificação de tipos
  * trata exceções 
  * uso de ponteiros
  * compatibilidade entre compiladores
* **custo**
  * treinamento
  * codificação
  * compilação
  * execução
  * infraestrutura

#### Análise de código

* na fase em que o código fonte vai para o compilador existe três tipos de análise:
  * léxica 
    * ler caractere por caractere do código fonte
    * particionar
      * vai identificar os elementos léxicos e agrupa-los
    * classificar
    * eliminar
      * comentários/espaços em branco 
  * sintática
    * interligam os constituinte da sentença, atribuindo uma estrutura
  * semântica
    * é o estudo do significado, incide sobre a relação entre significantes, como palavras, frases, sinais…

#### **Paradigmas de programação**

* forma de resolução de problemas com diretrizes e limitações específicas de cada paradigma
* classificação
  * orientação objeto
  * procedural
    * chamada sucessivas e procedimentos separados
  * funcional
    * instruções são baseadas em funções
  * estruturado
    * estrutura de blocos aninhados
  * computação distribuída
    * funções executadas de forma independente
  * lógico
* conceitos
  * sequência
  * decisão
    * teste lógico
  * interação
    * funções, laços, condições
* utilização
  * problemas simples e diretos
  * aprender programação
* orientação à objeto
  * paradigma de programação baseado na utilização de objetos e suas interações
  * análogo ao mundo real
  * um objeto é descrito por características específicas, comportamentos e estados
  * o que eu tenho?
    * atributo
  * sou capaz de fazer…
    * métodos
  * como faço?
    * estados
* o que é um objeto? Dentro do ponto de vista da programação
  * POO
    * classe
      * alocação de memória
      * operações associadas 
  * estruturada
    * alocação em memória
    * operações associadas
  * Exemplo:

```
classe caneta ( ):
​	cor: inteiro
​	carga: caractere 
​	tambada: lógico
​	metodo escrever( )
​		se estado tampada
​			escreva (“Destampar”)
​		senão
​			escreva (“algo”)
​		fimse
​			metodo tampar( )
​			tampada = verdadeiro
fimclasse
```

* pilares de orientação a objeto
  * herança
    * classe filho herda uma características de uma classe mãe
    * características
      * atributos
      * métodos
    * ela também pode ter especializações e métodos específicos dela
    * a classe mãe tem comportamentos gerais 
    * a classe filho tem comportamentos mais específicos

#### Algoritmos em Portugol

```
	programa {
​		funcao inicio() {
​			inteiro x,y
​			escreva("Digite os números para executar a soma do 		​		intervalo: ")
​			leia(x)
​			leia(y)
​			escreva(soma_intervalo(x,y))
​		}
​		funcao inteiro soma_intervalo(inteiro x, inteiro y) {
​   	 	inteiro total, resultado_parcial
​    		total = y/2
​  		  	resultado_parcial = y + x
​ 	 	  	inteiro resultado = total * resultado_parcial
​	    	retorne resultado
​		}
​	}
​	programa {
​		funcao inicio( ) {
​			real a, b, nota_a, nota_b
​			escreva("Escreva a nota p1 e p2 do aluno: ")
​			leia(a)
​			leia(b)
​			escreva("Escreva a nota p1 e p2 do aluno: ")
​			leia(nota_a)
​			leia(nota_b)
​			escreva("Média do aluno A: ", media_aluno(a, b))
​			escreva("\nMédia do aluno B: ", media_aluno(a, b))
​		}
​		funcao real media_aluno(real nota_a, real nota_b){
​    		retorne (nota_a + nota_b)/2
​		}
​	}
```

