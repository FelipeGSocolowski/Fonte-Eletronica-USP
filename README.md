# Fonte Ajustável
&nbsp;&nbsp;&nbsp;&nbsp;Projeto de uma Fonte de Tensão ajustável entre 3V a 12V com capacidade de 100mA.
## Componentes utilizados
| Quant. | Componente | Descrição | Preço |
| :-: | :-: | :- | :-: |
| 1 | Transformador | TRANSFORMADOR 18.1VAC | R$-- |
| 4 | Diodo         | DIODO RETIFICADOR 1N4007 LGE=1N4004 | R$0.20 |
| 1 | Capacitor     | CAPACITOR ELCO 1000UFX50V 105°C 16X20 EPCOS | R$5.21 |
| 1 | LED Vermelho  | LED 5MM VM DIFUSO 333-2SDRD/S530-L PARALIGHT | R$0.50 |
| 1 | Zener         | DIODO ZENER 13V 1W = 1N4743 SEMTECH | R$0.50 |
| 1 | Potenciômetro | POTENCIÔMETRO 1W B5K B-16,5XE-20XR-7MM JH | R$7.00 |
| 1 | Resistor 100Ω | RESISTOR 2W 100R 5% METAL FILME YAGEO | R$1.20 |
| 1 | Resistor 1.8kΩ| RESISTOR CR25 1K8 CARVÃO HITANO | R$0.07 |
| 2 | Resistor 2.2kΩ| RESISTOR CR25 2K2 CARVÃO ROHS | R$0.07 |
| 1 | Transistor    | TRANSISTOR TIP41C NPN 115V 6A 3MH TO-220 FAIRC | R$3.00 |
| 1 | Protoboard    | PROTOBOARD 170F TOWER | R$6.90 |
| 5 | Jumper        | JUMPER MACHO X MACHO 20CM TOWER | R$0.70 |
| **Total** | -/- | -/- | **R$28.82** |
## Explicação para os componentes
&nbsp;&nbsp;&nbsp;&nbsp;**Transformador**: O transformador diminui a tensão da fonte de corrente alternada a fim de garantir a diferença de potencial desejada para o resto do circuito.<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;**Diodos**: O conjunto de 4 diodos forma uma ponte retificadora que alimenta a fonte independentemente do ciclo da corrente alternada. <br><br>
&nbsp;&nbsp;&nbsp;&nbsp;**Capacitor**: Armazena carga elétrica a fim de liberá-la quando a tensão interna do componente é superior à tensão da corrente<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;**LED**: Indica se uma corrente está passando pelo circuito no momento. Esse componente não serve propósito prático na corrente.<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;**Diodo Zenner**: É um regulador que irá limitar a tensão máxima da corrente que o atravessa em 13V. Caso a tensão seja menor que o limite, o componente não irá agir.<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;**Potenciômetro**: Possibilita o controle da tensão da fonte por meio de uma resistência variável. Por meio deste, a fonte alcança uma tensão mínima e máxima de 3V e 12V, respectivamente.<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;**Resistor**: Os resistores limitam o fluxo da corrente a fim de impedir danos aos componentes da fonte.<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;**Transistor**: Ajusta a corrente a ser alimentada pela fonte enquanto regula a corrente que atravessa o zener.
## Cálculos
## Simulação no Falstad
&nbsp;&nbsp;&nbsp;&nbsp;![Print da simulação](Imagens/falstad.svg)<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;**Link da simulação**: https://tinyurl.com/2xr4mxyp
## Eagle
| Esquemático | PCB |
| :-: | :-: |
| ![Esquemático no Eagle](Imagens/esquematico.png) | ![PCB no Eagle](Imagens/pcb.png) |
## Foto da Protoboard
&nbsp;&nbsp;&nbsp;&nbsp;![Foto da Protoboard](Imagens/protoboard1.jpg)
## Grupo
+ Arthur de Castro Dias
+ Felipe Gausmann Socolowski
+ Gabriel Carraro Salzedas
+ Guilherme Cavalcanti de Santana
