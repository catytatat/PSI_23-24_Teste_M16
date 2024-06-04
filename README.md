# Teste de Programação e Sistemas de Informação - Módulo 16

Cria um repositório **privado** no GitHub com o nome **"PSI_Teste_M16"** e com um ficheiro **README**.

Podes fazer clone do repositório para o teu computador (ou para o Replit) e preencher o README localmente (ou no Replit) com as respostas dos exercícios. Seguidamente, terás de fazer commit e push das atualizações.

Alternativamente, podes preencher o ficheiro README diretamente no GitHub. A partir da página principal do repositório, clica em "Edit File" (ícone representando um lápis). Com o README preenchido, carrega no botão "Commit Changes".

Escreve as respostas dentro dos blocos correspondentes. Substitui as reticências pelo que é pedido em cada pergunta. Não desformates o documento.

Para entregar a ficha, acede a [este link](https://docs.google.com/spreadsheets/d/1DrdGnICVAA8q9bs9_LAURFKoReAO7jJGB8qqvUWacL0/edit?usp=sharing) (separador **Teste Módulo 16**), e mete o **URL** do teu repositório ao lado do teu nome.
No teu repositório, acede a "Settings -> Collaborators" e adiciona o utilizador "Manuel Geraldes" para ter acesso.

Quando acabares, carrega no botão "Commit Changes".

## Informação do aluno

    Nome: ...

## P1 - Para as seguintes questões, assinala a opção correta: (4v)

1. Qual das seguintes expressões LINQ é usada para selecionar apenas os elementos que satisfazem uma condição específica?

    a) select
   
    b) where
   
    c) group by
   
    d) order by

        Resposta: ...
    
2. Qual das seguintes palavras-chave LINQ é usada para ordenar os resultados?
   
    a) select

    b) orderby
   
    c) group
   
    d) where

        Resposta: ...
   
3. Que expressão LINQ é usada para projetar dados numa nova forma?

    a) where
   
    b) select
   
    c) orderby
   
    d) group

        Resposta: ...

4. Qual método de extensão é usado em LINQ para contar o número de elementos numa coleção?

    a) Count()
   
    b) Sum()
   
    c) Average()
   
    d) Max()

       Resposta: ...

## P2 - Indica, justificando, se as seguintes afirmações são verdadeiras ou falsas: (6v)

1. O método Select em LINQ é usado para filtrar elementos de uma coleção.

        Resposta: ...

2. O método OrderBy em LINQ ordena os elementos de uma coleção em ordem decrescente.

        Resposta: ...

3. Em LINQ, o método Any() verifica se qualquer elemento em uma coleção satisfaz uma condição específica.

        Resposta: ...

## P3 - Resolve os seguintes exercícios de desenvolvimento de código: (8v)

1. Considera a seguinte lista de produtos:

        public class Produto
        {
            public int Id { get; set; }
            public string Nome { get; set; }
            public double Preco { get; set; }
        }
        
        List<Produto> produtos = new List<Produto>
        {
            new Produto { Id = 1, Nome = "Produto A", Preco = 45.0 },
            new Produto { Id = 2, Nome = "Produto B", Preco = 60.0 },
            new Produto { Id = 3, Nome = "Produto C", Preco = 70.0 },
            new Produto { Id = 4, Nome = "Produto D", Preco = 30.0 }
        };

Escreve uma expressão LINQ para selecionar apenas os produtos cujo preço é maior que 50.

        Resposta: ...

2. Considera a seguinte lista de pessoas:

       List<Pessoa> pessoas = new List<Pessoa>
        {
            new Pessoa { Nome = "Ana", Idade = 25 },
            new Pessoa { Nome = "João", Idade = 30 },
            new Pessoa { Nome = "Maria", Idade = 28 },
            new Pessoa { Nome = "Pedro", Idade = 35 }
        };

   Usa LINQ para calcular a média das idades, e guarda o resultado numa variável apropriada.

       Resposta: ...
