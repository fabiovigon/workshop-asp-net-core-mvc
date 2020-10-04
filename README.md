# workshop-asp-net-core-mvc


Projeto desenvolvido afim de estudos sobre a linguagem C# e seu framework .NET MVC Core 2.1 junto da ORM Entity Framework e o MySql
o projeto consiste em um CRUD de vendas simples, onde possui pagina de vendas, vendedores e departamentos

Para executar basta baixar o projeto no seu computador e instalar você irá precisar:
.NET 2.1(se for uma versão superior os riscos de conflitos de packages será grande);
.Packages com as referencias do projeto(basta dar um build do projeto que o proprio NuGet resolve essas dependências)
.MySql Workbench que foi o banco de dados usado para esse estudo.

Tendo instalado e configurado todos os itens anteriores, segue o passo a passo para criar o banco atraves do Entity basta executar os seguintes comandos:
Add-Migration Initial (ou qualquer outro nome que você preferir )
Update-Database  (Isso irá criar o banco de dados dentro do MySQL)

OBS: Não esqueça de mudar a connection string do projeto.
