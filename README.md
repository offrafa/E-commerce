
## Catálogo de produtos:

Listando os catálogo de produtos importando-os a partir de um arquivo JSON, depois convertendo este texto em dados que são gravados na tabela de produtos. Em seguida, 


exibindo os produtos na nossa tela de carrossel, de quatro em quatro, utilizando-se uma técnica de paginação feita na nossa view de carrossel com código C# e LINQ.



Por falar nisso, foi combinado o código C# com HMTL em uma view, é possível utilizarmos um motor de renderização chamado Razor.



![Loom-Message-29-December-2022](https://user-images.githubusercontent.com/91328590/209982911-c6195a23-3d2b-4c5e-86e0-62687460e086.gif)



## Banco de dados:

A partir do conceito de Model First, ou Code First, para inicialmente foi criado as classes em C#, após o qual foram migradas para o banco de dados SQL Server. Para isso, foi utilizado o Entity Framework Core, que fez esta migração, ou mapeamento, para o banco de dados.



![image](https://user-images.githubusercontent.com/91328590/210010047-91aa1765-f3c9-45c6-8990-8aa663d9358b.png)



## Funções AJAX:

Ao implementar os eventos de click nos botões "+" e "-" para alterar a quantidade de itens no carrinho. Utilizamos funções do JavaScript em um evento de cliques em botões no html.

<p>Em seguida, utilizando o jQuery para selecionar os elementos html e obter as informações necessárias, por exemplo o id do item pedido, navegando pela hierarquia de elementos html para, por exemplo, buscar uma linha <div> que estava mais abaixo no código, para montar uma requisição e enviar dados para o servidor</p>


![Carrinho-Casa-do-Código-29-December-2022](https://user-images.githubusercontent.com/91328590/210020572-e4b37159-5520-40c8-bb9c-c75ba3a9693d.gif)
