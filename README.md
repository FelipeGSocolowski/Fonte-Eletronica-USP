# Fonte Ajustável
&nbsp;&nbsp;&nbsp;&nbsp;Projeto de uma Fonte de Tensão ajustável entre 3V a 12V com capacidade de 100mA.
## Componentes utilizados
| Componente | Descrição | Quantidade | Preço |
| :-: | :-: | :-: | :-: |
| Transformador | TRANSFORMADOR 18.1VAC | 1 | R$-- |
| Diodo         | DIODO RETIFICADOR 1N4007 LGE=1N4004 | 4 | R$0.20 |
| Capacitor     | CAPACITOR ELCO 1000UFX50V 105°C 16X20 EPCOS | 1 | R$2.50 |
| LED Vermelho  | LED 5MM VM DIFUSO 333-2SDRD/S530-L PARALIGHT | 1 | R$0.50 |
| Zener         | DIODO ZENER 13V 1W = 1N4743 SEMTECH | 1 | R$0.50 |
| Potenciômetro | POTENCIÔMETRO 1W B5K B-16,5XE-20XR-7MM JH | 1 | R$7.00 |
| Resistor 100Ω | RESISTOR 2W 100R 5% METAL FILME YAGEO | 1 | R$1.70 |
| Resistor 1.8kΩ| RESISTOR CR25 1K8 CARVÃO HITANO | 1 | R$0.07 |
| Resistor 2.2kΩ| RESISTOR CR25 2K2 CARVÃO ROHS | 2 | R$0.07 |
| Transistor    | TRANSISTOR TIP41C NPN 115V 6A 3MH TO-220 FAIRC | 1 | R$3.00 |
| Protoboard    | PROTOBOARD 170F TOWER | 1 | R$6.90 |
| Jumper        | JUMPER MACHO X MACHO 20CM TOWER | 5 | R$0.70 |
## Explicação para os componentes
&nbsp;&nbsp;&nbsp;&nbsp;Transformador:<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;Diodos: O conjunto de 4 diodos forma uma ponte retificadora que alimenta a fonte independentemente do ciclo da corrente alternada. <br><br>
&nbsp;&nbsp;&nbsp;&nbsp;Capacitor:<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;LED: O LED indica se uma corrente está passando pelo circuito no momento. Esse componente não serve propósito prático na corrente.<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;Diodo Zenner: O Zener é um regulador que irá limitar a tensão máxima da corrente que o atravessa em 13V. Caso a tensão seja menor que o limite, o componente não irá agir.<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;Potenciômetro: Possibilita o controle da tensão da fonte por meio de uma resistência variável. Por meio deste, a fonte alcança uma tensão mínima e máxima de 3V e 12V, respectivamente.<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;Resistor: Os resistores limitam o fluxo da corrente a fim de impedir danos aos componentes da fonte.<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;Transistor:<br><br>
## Simulação no Falstad
&nbsp;&nbsp;&nbsp;&nbsp;![Print da simulação](Imagens/falstad.svg)<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;Link da simulação: https://tinyurl.com/2xr4mxyp
## Foto da Protoboard
&nbsp;&nbsp;&nbsp;&nbsp;![Foto da Protoboard](Imagens/protoboard1.jpg)
## Cálculos
## Grupo
+ Arthur de Castro Dias
+ Felipe Gausmann Socolowski
+ Gabriel Carraro Salzedas
+ Guilherme Cavalcanti de Santana
