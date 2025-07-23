# calculadora-py
## 💡 Lógica da Calculadora

O programa da calculadora foi desenvolvido em Python com o objetivo de realizar operações básicas (+, -, *, /).

### Como funciona:

1. O usuário é solicitado a digitar dois números e o operador desejado.
2. O código verifica qual operação foi solicitada e realiza o cálculo correspondente.
3. Caso o operador seja inválido, uma mensagem de erro é exibida.
4. O programa trata entradas inválidas com `try-except`, incluindo:
   - Erros de conversão de string para número (`ValueError`).
   - Divisão por zero (`ZeroDivisionError`).

Este código está localizado no arquivo `calculadora.py` e pode ser executado diretamente via terminal ou pelo script `executar_calculadora.sh`.
