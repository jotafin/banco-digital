# Projeto Bytebank - Disciplina de Testes

Este projeto foi desenvolvido como parte da disciplina de **Testes de Software**. Ele representa um **Mínimo Produto Viável (MVP)** de uma aplicação bancária digital da empresa fictícia **Bytebank**. O objetivo deste repositório é demonstrar a importância de testes no desenvolvimento de software e aplicar boas práticas de teste no desenvolvimento front-end, utilizando uma aplicação simples.

O projeto ainda está em desenvolvimento e possui algumas funcionalidades já implementadas, mas também apresenta erros e áreas que precisam de correção, especialmente relacionadas ao cálculo do saldo nas transações.

## Estrutura do Projeto

A aplicação simula uma interface de banco digital onde o usuário pode realizar transações financeiras, como depósitos e transferências, visualizar seu saldo e consultar um extrato das transações realizadas.

### Tela de Login (já implementada)

- **Barra superior** com o logotipo do Bytebank à esquerda e o nome do usuário logado à direita (exemplo: Joana Fonseca Gomes).
- **Corpo da página** com fundo verde claro.
  
### Menu Lateral Esquerdo

- Links para diferentes áreas da aplicação:
  - Inicial
  - Transferências
  - Investimentos
  - Outros serviços

### Seção de Extrato

- Lateral direita da página, onde as transações realizadas são listadas (por enquanto, sem transações cadastradas, mas já funcional para visualização).
  
### Componentes Principais

- **Saldo**: No topo da página, com o saldo atual do usuário (inicialmente R$1000,00).
- **Transações**: Campo para realizar uma transação (depósito ou transferência), onde o usuário pode:
  - Selecionar o tipo de transação
  - Inserir o valor
  - Realizar a transação, que será registrada no extrato.

### Bug Conhecido

- O saldo está apresentando um erro ao realizar transações:
  - **Depósito**: Deveria adicionar o valor ao saldo, mas está subtraindo.
  - **Transferência**: Deveria subtrair o valor do saldo, mas está somando.

Este erro é um exemplo clássico de como a falta de testes pode levar a problemas difíceis de identificar e corrigir. A implementação de testes, que será feita nas próximas etapas do projeto, ajudará a prevenir esses tipos de erros e garantir que a aplicação funcione corretamente.

---

## Começando

Este projeto é um exercício prático para aprender sobre testes no desenvolvimento de aplicações front-end. Siga os passos abaixo para rodar a aplicação em seu ambiente local.

### Pré-requisitos

- **Node.js** v16 ou superior
- **npm** ou **yarn**

### `npm start`

Executa o aplicativo no modo de desenvolvimento.\
Abra [http://localhost:3000](http://localhost:3000) para visualizá-lo no seu navegador.

A página será recarregada quando você fizer alterações.\


