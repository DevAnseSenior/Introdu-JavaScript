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
  
    ```js
    /*
    	Tudo no meio é um comentário.
    */
    ```
  
  - ### Se o seu comentário não tiver apenas uma linha, coloque dessa maneira:
  
    ```js
    // Isto é um comentário
    ```
  
  ## Operadores
  
  - ### Simbolo matemática que produz um resultado baseado em dois valores;
  
  - ### Vejamos alguns deles:
  
    | Operador                       | Explicação                                                   | Simbolo(s) | Exemplo                                                      |
    | ------------------------------ | ------------------------------------------------------------ | ---------- | ------------------------------------------------------------ |
    | adição/concatenação            | Usado para somar dois numeros ou juntar duas strings         | +          | 6 + 9;<br />"Olá " + "Mundo!"                                |
    | subtrair, multiplicar, dividir | Fazem exatamente o que você espera que eles façam na matemática básica. | -, *, /    | 9 - 3;<br />8 * 2;<br />9 / 3;                               |
    | operador de atribuição         | Já vimos, ela associa um valor a uma váriavel.               | =          | var nome = 'Bob';                                            |
    | operador de igualdade          | Faz um teste para ver se dois valores são iguais um ao outro, retornando um resultado true/false (booleano) | ===        | var numero = 3;<br />numero === 4;                           |
    | negação, não igual(diferente)  | Retorna o valor lógico oposto do sinal; transforma um true em false, etc. Quando usado junto com o operador de igualdade, o operador de negação testa se os valores são diferentes. | !, !==     | "Não igual" dá basicamente o mesmo resultado da sintaxe diferente. Aqui estamos testando "É  numero NÃO é igual a 3". Isso  retorna false porque numero É igual a 3.<br />var numero = 3;<br />numero !== 3; |
  
  - ### Há vários outros operadores para explorar, mas por enquanto esse são suficientes.
  
  ## Condicionais
  
  - ### tPermite testar se uma expressão retorna verdadeiro ou não;
  
  - ### Executa um código alternativo, dependendo da situação;
  
  - ### Uma forma comum de condicional é a instrução if... else.
  
    ```js
    var sorvete = 'chocolate';
    if (sorvete === 'chocolate') {
        alert('Gosto desse sabor');
    } else {
        alert('Bom, mas o meu sabor favorito é chocolate.');
    }
    ```
  
  - ### A expressão dentro do if (...) é o teste - ela usa o operador de igualdade(como descrito anteriormente) para comparar a variável sorvete com a string chocolate para ver se elas são iguais;
  
  - ### Se a comparação retorna true, o primeiro bloco é executado;
  
  - ### Se for falsa, o primeiro bloco é ignorado e o segundo executado.
  
  ## Loops
  
  - ### Permite que uma parte do código continue executando repetidademente, até que determinada condição seja satisfeita. Vamos testar o seguinte:
  
    ```js
    for (var i = 1 ; i < 21; i++) {
        console.log(i);
    }
    ```
  
  - ### O que aconteceu? Os numeros de 1 a 20 foram exibidos no seu console. Isso acontece por causa do loop. Um loop for utiliza a inserção de três valores (argumentos):
  
    1. **Um valor inicial**: Nesse caso estamos iniciando a contagem com 1, mas pode ser qualquer numero da minha escolha;
    2. **Uma condição de saída**: Aqui nos especificamos i < 21 - O loop irá continuar até que i não seja mais menor que 21.
    3. **Incremento:** Especificado como i++. Significa "Adicione 1 à i".
  
  ## Funções
  
  - ### Maneira de encapsular funcionalidades reutilizaveis;
  
  - ### Apresentada a necessidade, posso chamar a função pelo nome, ao invés de, reescrever o código inteiro;
  
  - ### Já vimos um exemplo:
  
    ```js
    alert('hello');
    ```
  
  - ### Essa função é pré-definida nos navegadores para ser usada quando quiser;
  
  - ### Se ver alguma coisa com um nome de variável, mas com parênteses - () - depois, provavelmente é uma função;
  
  - ### Geralmente tem argumentos;
  
  - ### Esses colocados dentro dos parênteses e separados por vírgula.
  
  - ### Tambem é possivel definirmos nossas próprias funções, façamos uma que multiplica dois numeros:
  
    ```js
    function multiplicacao(num1, num2) {
    	var resultado = num1 * num2;
        return resultado;
    }
    ```
  
  - ### Tente executar essa função no console e teste com vários argumentos. Ex.:
  
    ```js
    Próxima 
    mutiplicacao(4,7);
    mutiplicacao(20,20);
    mutiplicacao(0.5,3);
    ```
  
    ##### **Nota:** A instrução return diz ao navegador que retorne a variável resultado da função. Isso é necessário pois, variáveis definidas dentro de funções só estão disponíveis dentro de funções.
  
    