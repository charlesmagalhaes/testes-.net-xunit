# Sistema de Estacionamento

Sistema de estacionamento simples em C# com as classes `Patio`, `Veiculo` e `Operador`. Os testes unitários validam o funcionamento adequado do sistema.

## Classes Principais

**Patio**
- Gerencia veículos.
- Calcula faturamento.
- Registra entrada e saída.
- Pesquisa por ID de ticket.
- Altera dados do veículo.

**Veiculo**
- Representa um veículo no estacionamento.
- Contém informações como placa, proprietário, tipo, cor, hora de entrada/saída.
- Métodos para acelerar, frear e alterar dados.

**Operador**
- Representa um operador do estacionamento.
- Possui matrícula e nome.

## Testes Unitários

- Verifica cálculo correto do faturamento.
- Localiza veículo pelo ID do ticket.
- Altera dados do veículo e verifica as alterações.
- Testes para os métodos `Acelerar` e `Frear` da classe `Veiculo`.
- Teste para o método `ToString` da classe `Veiculo`.
- Teste para validação de nome do proprietário.
- Teste para validação da mensagem de exceção ao definir o quarto caractere da placa.

## Como Usar

1. Compile o código-fonte C#.
2. Execute o programa para acessar o menu de opções.
3. Escolha as opções desejadas.
4. Siga as instruções do programa.

## Pré-requisitos

Certifique-se de ter o ambiente de desenvolvimento C# configurado corretamente.

## Contribuições

Contribuições são bem-vindas via pull requests.

