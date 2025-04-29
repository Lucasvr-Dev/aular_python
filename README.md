# aulas-python

## Tipos primitivos (string. number(int/float), boolean

<img src="https://github.com/user-attachments/assets/1644e27f-42d5-4650-b46d-3968b36bd9aa" width="650px" height="450px">

para saber mais, [clique aqui.](https://dev.to/dormin/tipos-primitivos-em-python-10jg)
### Operadores aritmeticos*
#### Operadores* logicos/comparativos
### (if/ elif/ else)

**Tipos de estruturas condicionais:**

- if: Executa um boco de código se uma condição especificada for verdadeira.
- elif: Significa "else if" e permite que você verifique várias condições.
- else: Executa um bloco de código se nenhuma das condições anteriores for verdadeira.

  a = int(input(print('Insira o valor do primeiro lado do quadrado')))
b = int(input(print('Insira o valor do segundo lado do quadrado')))
c = int(input(print('Insira o valor do terceiro lado do quadrado')))

```py
if a == b and b == c:
  print('Você tem um triângulo equilatero')
elif a == b or b == c or a == c:
  print('Você tem um triângulo isósceles')
else:
  print('Você tem um triângulo escaleno')
  
