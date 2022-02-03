# SitemaDeCadastro

## Descrição

### O programa desenvolvido é um sistema automatizado para pagamento de impostos, que cadastra usuarios classificados como Pessoa Física e Pessoa Jurídica.

## Funcionalidades
### O sistema faz o cadastro, permite a alteração dos dados dos usuários e possibilita o pagamentos de tributos dos usuários cadastrados.

## Tecnologias
* .NET 5
* Visual Studio Code
### O .NET é uma tecnologia server-side potencial e facilitadora na criação de projetos que usam o paradigma de orientação a objetos. O VS Code é um editor de código que permite criar projetos desde basicos a avançados, permitindo que o programador adeque os seus projetos em contextos distintos sem ter que usar uma IDE.

## Organização
### O sistema está dividido em cinco arquivos, cada arquivo representa um objeto que armazena os dados obtidos dos usuários. ![image](https://user-images.githubusercontent.com/88802868/152272116-24f9ba8f-0302-4e60-b4f5-064f7a951bc7.png)
### A classe pessoa é uma classe abstrata, fornece recursos para as classes filhas que a herdarem. A classe Pessoa Jurídica recebe dados somente dos usuários declarados como portadores do CNPJ. A classe Pessoa Física recebe dados somente dos usuários declarados como portadores do CPF.

## Como Usar
### Para usar ou alterar o sistema é preciso ter instalado na maquina o .NET 5 ou versão superior, além disso deve ter um editor de código ou uma IDE, como o Visual Studio.

## Execução
### Para executar o projeto é necessário abrir um terminal na pasta onde o projeto está e digitar __dotnet run__ e para cancelar a aplicação usar o atalho __Ctrl + C__.

## Erros Comuns
### Os erros mais comuns de acontecer é quando o sistema pede que o usuário insira dados, e ao inserir o progarama pode cancelar a aplicação por ter digitado um dado que não podia ser armazenado em uma variavel que pede dados específicos.

## Contribuidores
### Produzido por Ruan Lucas
