# Conheça o projeto

Nesse desafio você irá implementar uma calculadora que solicita ao usuário dois números e uma operação matemática (+, -, *, /, etc) e exibe o resultado.


## Instruções

### Estrutura, regras e requisitos do projeto

Descrição

O programa pede um número, depois um operador e, em seguida, o segundo número. Ele deve então calcular e mostrar o resultado.
Conceitos Praticados

    Fundamentos: Entrada e saída básica (gets, puts).
    Tipos de Dados: Conversão de Strings para Inteiros (to_i) ou Floats (to_f).
    Estruturas de Controle:
        Uso de if/elsif/else ou case para determinar qual operação realizar.
        Tratamento de exceções (begin/rescue) para lidar com entradas inválidas (operadores inválidos ou texto não numéricos) ou divisão por zero (ZeroDivisionError).


### Tarefas

- [ ] Capturar Entradas: Pedir ao usuário o primeiro número, o operador (+, -, \*, /) e o segundo número.
- [ ] Converter Tipos: Converter as entradas dos números de texto (String) para números (`Float`).
- [ ] Implementar Operações: Usar uma estrutura `case` ou `if/elsif` para verificar o operador e realizar o cálculo correto.
- [ ] Exibir Resultado: Mostrar o resultado da operação na tela.
- [ ] Tratar Divisão por Zero: Impedir o cálculo e mostrar uma mensagem de erro se o segundo número for zero na divisão.
- [ ] Tratar Operador Inválido: Mostrar uma mensagem de erro se o operador não for +, -, \* ou /.
- [ ] Tratar Entrada Inválida: Usar `begin/rescue` para mostrar um erro caso o usuário digite texto onde deveria ser um número.