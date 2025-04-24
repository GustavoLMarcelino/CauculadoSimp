# Calculadora Simples

## Especificação Funcional

### 1. Descrição Geral
Este software é uma calculadora simples desenvolvida em JavaScript com funcionalidades básicas de operações aritméticas: soma, subtração, multiplicação e divisão. O objetivo é fornecer uma ferramenta de uso simples para realizar cálculos com dois operandos, através de uma interface gráfica acessível via navegador.

### 2. Funcionalidades
- Permitir ao usuário escolher a operação desejada entre soma, subtração, multiplicação e divisão.
- Solicitar dois números como entrada.
- Exibir o resultado da operação.
- Impedir divisão por zero com tratamento de erro.
- Permitir múltiplas operações sem necessidade de recarregar a página.

### 3. Requisitos Funcionais
- O sistema deve exibir um menu com as opções disponíveis.
- O sistema deve ler e validar a entrada do usuário.
- O sistema deve realizar a operação escolhida e mostrar o resultado.
- O sistema deve tratar erros de entrada e divisão por zero.

### 4. Requisitos Não Funcionais
- O sistema deve ser executado em qualquer navegador moderno.
- O código deve ser comentado para facilitar a compreensão.
- O sistema deve ter baixa complexidade e alta legibilidade.

---

## Plano de Testes - Calculadora Simples

### Caso de Teste 1 - Soma
- Entradas: 4, 5
- Operação: Soma
- Resultado Esperado: 9
- Resultado Obtido: Conforme execução.

### Caso de Teste 2 - Divisão por Zero
- Entradas: 10, 0
- Operação: Divisão
- Resultado Esperado: Mensagem de erro 'Divisão por zero não é permitida.'
- Resultado Obtido: Conforme execução.

### Caso de Teste 3 - Entrada Inválida
- Entradas: 'abc', 5
- Operação: Soma
- Resultado Esperado: Mensagem de erro 'Entrada inválida. Digite um número.'
- Resultado Obtido: Conforme execução.

---

## Fluxograma - Calculadora Simples
O fluxograma abaixo representa o fluxo de execução da calculadora:

1. Início
2. Mostrar menu de operações
3. Usuário escolhe operação
4. Ler primeiro número
5. Ler segundo número
6. Validar entradas
7. Executar operação escolhida
8. Mostrar resultado
9. Fim ou repetir operação

(Considere adicionar o fluxograma em imagem ou ferramenta visual no repositório)
