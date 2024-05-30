# ContaBanco

Este projeto é um código simples em Java para o desafio do bootcamp da DIO. O desafio consiste em criar um programa que simule a criação de uma conta bancária, recebendo dados via terminal e exibindo uma mensagem de confirmação ao usuário.

## Desafio: Sintaxe - Desafio

Vamos exercitar todo o conteúdo apresentado no módulo de Sintaxe codificando o seguinte cenário:

### Objetivo

Crie o projeto ContaBanco que receberá dados via terminal contendo as características de conta em banco conforme atributos abaixo:

| Atributo       | Tipo    | Exemplo         |
|----------------|---------|-----------------|
| Numero         | Inteiro | 1021            |
| Agencia        | Texto   | 067-8           |
| Nome Cliente   | Texto   | MARIO ANDRADE   |
| Saldo          | Decimal | 237.48          |

### Passos

1. **Criação do Projeto e Classe**
   - Dentro do projeto, crie a classe `ContaTerminal.java` para realizar toda a codificação do nosso programa.
   - Revise sobre regras de declaração de variáveis.

2. **Inserção de Dados via Terminal**
   - Utilize a classe `Scanner` para permitir que os dados sejam inseridos via terminal.
   - O usuário receberá mensagens indicando quais informações precisam ser fornecidas, por exemplo:
     - Programa: "Por favor, digite o número da Agência!"
     - Usuário: 1021 (depois ENTER para o próximo campo)
   - Revise sobre terminal, `main args`, e a classe `Scanner`.

3. **Concatenação e Exibição de Mensagem**
   - Revise sobre concatenação e a classe `String` com o método `concat`.
   - Depois que todas as informações tiverem sido inseridas, o sistema deverá exibir a seguinte mensagem:
     - "Olá [Nome Cliente], obrigado por criar uma conta em nosso banco, sua agência é [Agencia], conta [Numero] e seu saldo [Saldo] já está disponível para saque".
   - Os campos em `[ ]` devem ser alterados pelas informações fornecidas pelos usuários.

### Exemplo de Uso

Ao executar o programa, a interação será como no exemplo abaixo:

