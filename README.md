# ServidorHttp

Este texto é um tutorial sobre como usar o servidor HTTP simples em C#, que pode ser usado para testar o código de páginas web. Para seguir este tutorial, você precisa ter instalado o .NET Framework e um editor de código de sua preferência. Os passos são os seguintes:

1. Clone o repositório do projeto, que contém o código-fonte do servidor HTTP, usando o comando `git clone e a url do repositorio`.
2. Abra o editor de código e navegue até a pasta do projeto clonado.
3. Dentro da pasta do projeto, crie uma subpasta chamada "www", que será o diretório raiz do servidor HTTP.
4. Dentro da pasta "www", crie um arquivo HTML com o nome que quiser, por exemplo "index.html". Escreva o código HTML que você quer testar nesse arquivo.
5. Volte para a pasta do projeto e abra o arquivo "ServidoHttp.cs", que contém o código do servidor HTTP. Você pode alterar a porta em que o servidor vai escutar as requisições, por padrão é a 8080.
6. Execute o projeto usando o comando `dotnet run` no terminal. Você deve ver uma mensagem indicando que o servidor está rodando na porta escolhida.
7. Abra o navegador e digite o endereço `http://localhost:8080/nome_do_arquivo.html`, substituindo "nome_do_arquivo" pelo nome do arquivo HTML que você criou na pasta "www".
8. Você deve ver a página web que você escreveu sendo exibida no navegador. Você pode fazer alterações no código HTML e recarregar a página para ver as mudanças.
9. Para encerrar o servidor, pressione Ctrl+C no terminal.
