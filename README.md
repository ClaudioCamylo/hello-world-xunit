# Hello World com xUnit

Projeto desenvolvido na disciplina de Garantia da Qualidade de Software para praticar a criação de uma solução .NET 10, implementação de testes unitários com xUnit e versionamento com Git e GitHub.

## Tecnologias utilizadas

- .NET 10
- C#
- xUnit
- Git
- GitHub

## Estrutura da solução

- `MeuPrimeiroTeste.App`: projeto principal da aplicação.
- `MeuPrimeiroTeste.Tests`: projeto de testes unitários com xUnit.

## Funcionalidade

A classe `OlaMundo` possui o método `ObterMensagem()`, responsável por retornar:

`Hello, World!`

O projeto de testes verifica se o método retorna exatamente a mensagem esperada utilizando `Assert.Equal()`.

## Como executar a aplicação

```bash
dotnet run --project MeuPrimeiroTeste.App