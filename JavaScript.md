# JavaScript

- ## Linguagem de programação interpretada e estruturada;

- ## Script de alto nível e tipagem dinâmica fraca;

- ## Multi-paradigma(Protótipos, orientada a objetos, imperativo e funcional);

- ## Uma das três técnologias WWW;

- ## Criação de páginas Web Interativas;

  ![JS-logo](assets/JavaScript_logo_2.png)

# Primeiros passos com JavaScript

- ## É uma linguagem usada para adicionar interatividade ao seu site(Ex.: Jogos, respostas quando botões são pressionados ou dados inseridos em formulários, estilo dinâmico, animações).

# Um exemplo "Olá mundo"

- ## Para começar, veja como adicionar algum JS básico a sua página, criando um "olá mundo!".

  1. ### Primeiro  crie um arquivo chamado main.js;

  2. ### Neste arquivo, escreva o seguinte trecho de código:

     ```js
     console.log('Olá mundo!!!');
     ```

  3. ### Para executar o código, utilize a combinação de teclas CTRL + ALT + n;

- ## O que aconteceu?

  - ### Basicamente fizemos com que uma mensagem fosse impressa no console.


# Curso intensivo de fundamentos da linguagem

- ## Vamos explicar alguns dos principais recursos do JS, para dar um melhor entendimento de como tudo funciona.

  ## Variáveis

  - ### São espaços na memória do computador onde são armazenados dados. Variáveis são iniciadas com a palavra-chave **var**, seguida por qualquer nome que você queira chamá-la:

    ```js
    var nome;
    var genero;
    var idade;
    var	minhaVariavel;
    ```

    ##### **Nota:** Ponto-e-virgula no final da linha indica onde uma instrução termina, colocá-las é uma boa prática;

    ##### **Nota:** JS é case sensitive, ou seja, 'minhaVariavel' é diferente de 'minhavariavel'.

  - ### Depois de declarar uma várivel, você pode dar um valor a ela:

    ```js
    var nome = 'Bob';
    ```

  - ### Se quiser é possível fazer as duas operções na mesma linha:

    ```js
    var genero = 'Masculino';
    ```

  - ### Você pode retornar o valor chamando a váriavel pelo nome:

    ```js
    nome;
    ```

  - ### Depois de dar um valor a variável, tambem é possível mudá-lo:

    ```js
    var nome = 'Bob';
    nome = 'Steve';
    ```

    ### Note que as variáveis tem diferentes tipos de dados:

    | Variáveis | Explicação                                                   | Exemplo                                                      |
    | --------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | String    | Sequência de texto é conhecida como string. Para mostrar que o valor é uma String, deve ser envolvida entre aspas. | var nome = 'Bob';                                            |
    | Number    | Um número. Números não tem aspas.                            | var num = 10;                                                |
    | Boolean   | Um valor verdadeiro ou falso.<br />As palavras 'true' e 'false' são reservadas em JS e não precisam de aspas. | var bool = true;                                             |
    | Array     | Uma estrutura que permite armazenar vários valores em uma única variável. | var pessoa = [1, 'Bob', 10]<br />Cada item pode ser acessado:<br />pessoa[0], pessoa[1], etc. |
    | Object    | Basicamente, qualquer coisa. Em JS tudo é objeto e pode ser armazenado em uma váriavel. Tenha isso em mente enquanto aprende. | var titulo = document.querySelector('h1');                   |

  - ### Variáveis são necessárias para qualquer coisa interessante na programação. Se os valores não podessem mudar, nada dinâmico seria criado.

  ## Comentários

  - ### É possível colocar comentários em códigos JS: