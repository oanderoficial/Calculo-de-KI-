# Cáculo de KI 

Calculando o KI, que é a constante de inibição no contexto de um ensaio de inibição enzimática. O programa deve imprimir o Ki na tela.

```
from rdkit import Chem

ic50 = float(input('Digite o valor de ic50: '))
substrato = float(input('Concentração do substrato: '))
Km = float(input('Constante de Michaelis: '))

Ki = (ic50/(1 + (substrato/Km)))
print('O valor da constante de inibição é',round(Ki,3))

```
