# Robô-Pivot-Point-Mt5-com-Python

* Vídeo do código:  https://youtu.be/mD7_zojami4


Robôs Investidores para Metatrader 5, usando a estratégia de Pivot Point feito em python.
Para que esse robô funcione você precisa ter algumas bibliotecas instaladas em seu python:

pip install metatrader 5; pip install date time;pip install pandas, pip install numpy

Ponts Pivot são sempre muito úteis para as operações, esta é uma maneira simples para se ter uma idéia de onde o mercado está indo durante o dia.

O indicador também fornece as três primeiros suportes e resistências.

As fórmulas que eu usei são:

Resistência 3 = High + 2*(Pivot - Low)

Resistência 2 = Pivot + (R1 - S1)

Resistência 1 = 2 * Pivot - Low

Pontos Pivô = ( High + Close + Low )/3

Suporte 1 = 2 * Pivot - High

Suporte 2 = Pivot - (R1 - S1)

Suporte 3 = Low - 2*(High - Pivot)

![Resultado](https://github.com/alissonf216/Robo-Pivot-Point-Mt5-com-Python/blob/main/ilustrac.png)

Obs: Isso nao é uma indicação que essa é a melhor estrategia para negocioação, é a penas um estudo.

