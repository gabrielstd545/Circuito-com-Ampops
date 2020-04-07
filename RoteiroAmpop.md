# Laboratório de Eletronica - AmpOps
Aluno: 
* Gabriel Wagner - <gabrielstd545@gmail.com>

Professores: 
* Daniel Lohmann
# Parte 01 - Buffer
* Objetivo específico: Medir o ganho de um amplificador inversor.
* Experimento: Utilizando os ampops Lm324n e Experimento: Utilizando os ampops Lm324n e TL082 na configuração de amplificador inversor.
Especificações: 
* Utilize uma resistência de realimentçãoo de 10 kΩ.
* Utilize a alimentação simétrica de +/-12 V.
* Limitar a corrente em 0,05A
* Gerador de funções: Senoide 0,5Vpp
* Frequência: 1KHz
## Funcionamento do Buffer
O ampop na configuração buffer tem o seguinte funcionamento, todo o sinal de saída tem que ser igual ao sinal de entrada, sem ocorrer distorções na forma de onda.
## Buffer
Figura 1 - Circuito Buffer teórico

![](lab%20ampop/buffer/buffer.jpg)
## Simulação Do Lm324n LTSpice
Figura 2 - Circuito buffer utilizando o ampop Lm324n
![](lab%20ampop/buffer/Simula%C3%A7%C3%A3o%20Do%20Lm324n%20LTSpice%20-%20circuito.jpg)
Obs: Buffer realimentado para diminuição da corrente de polarização
## Simulação Do Lm324n LTSpice 
Figura 3 - Tensão de entrada x Tensão de saída
![](lab%20ampop/buffer/Simula%C3%A7%C3%A3o%20Do%20Lm324n%20LTSpice%20-%20simula%C3%A7%C3%A3o.jpg)
## Comparação dos resultados
Tensões (V) | Tensões de Pico (V) | Tensão Máxima (V) | Tensão Mínima (V)
----------- | ------------------- | ----------------- | ----------------
Tensão de entrada teórica | 0,5 | 0,5 | -0,5 
Tensão de entrada simulada | 0,5 | 0,5 | -0,5
Tensão de saída teórica | 0,5 | 0,5 | -0,5
Tensão de saída simulada | 0,5 | 0,5 | -0,5
## TL082 - Simulação
Figura 4 - Circuito simulado com ampop TL082
![](lab%20ampop/buffer/TL082%20%E2%80%93%20SIMULA%C3%87%C3%83O%20-%20circuito.jpg)
## TL082 - Simulação
Figura 5 - Tensão de entrada x Tensão de saída
![](lab%20ampop/buffer/TL082%20%E2%80%93%20SIMULA%C3%87%C3%83O%20-%20simula%C3%A7%C3%A3o.jpg)
Tensões (V) | Tensões de Pico (V) | Tensão Máxima (V) | Tensão Mínima (V)
----------- | ------------------- | ----------------- | ----------------
Tensão de entrada teórica | 0,5 | 0,5 | -0,5 
Tensão de entrada simulada | 0,5 | 0,5 | -0,5
Tensão de saída teórica | 0,5 | 0,5 | -0,5
Tensão de saída simulada | 0,5 | 0,5 | -0,5
## Conclusão
* O buffer possui ganho unitário para os dois ampops utilizados, desconsiderando é claro as imperfeições dos dois componentes.

# Parte 02 - Inversor
* Objetivo Específico: Medir o ganho de um aplificador inversor
* Experimento: Utilizando os ampops LM324n e TL082 na configuração de amplificador inversor.
Especificações:
* Resistor de entrada: 2k
* Resistor de Realimentação: 20K
* Alimentação: +/- 12V
* Gerador de Funções: 0,5Vpp
* Frequência: 1KHz
## Cálculo do ganho inversor
* Vout: - (Rr/Re)*Vin
* Resistor de entrada: 2k
* Resistor de Realimentação: 20K
* Ganho de: 10
* Tensão de entrada: 0,5V
* Tensão de saída: 5V
## Simulação LM324n
Figura 6 - Circuito simulado inversor com ampop LM324n
![](lab%20ampop/inversor/simula%C3%A7%C3%A3o%20lm324%20circuito.jpg)
## Simulação LM324n
Figura 7 - Tensão de entrada x Tensão de saída com LM324n
![](lab%20ampop/inversor/lm324%20SIMULA%C3%87%C3%83O%20-%20grafico.jpg)
## Simulação do TL082
Figura 8 - Circuito simulado inversor com ampop TL082
![](lab%20ampop/inversor/TL082%20%E2%80%93%20SIMULA%C3%87%C3%83O%20-%20circuito.jpg)
## Simulação do TL082
Figura 9 - Tensão de entrada x Tensão de saída com ampop TL082
![](lab%20ampop/inversor/TL082%20%E2%80%93%20SIMULA%C3%87%C3%83O%20-%20grafico.jpg)
## Conclusões
Em relação a configuração inversora, ambos ampops apresentaram o ganho de 10, excluindo as imperfeições.

# Parte 03 - Não Inversor
* Objetivo Específico: Medir o ganho de um amplificador inversor.
* Experimento: Utilizando os ampops Lm324n e TL082 na configuração de amplificador inversor.
Especificações
* Resistor de entrada: 2k
* Resistor de Realimentação: 20K
* Alimentação: +/- 12V
* Gerador de Funções: 0,5Vpp
## Cálculo do ganho não inversor
* Vout: (1 + Rr/Re)*Vin
* Resistor de entrada: 2k
* Resistor de Realimentação: 20K
* Ganho de: 11
* Tensão de entrada: 0,5V
* Tensão de saída: 5,5V
* Frequência: 1KHz
# Imagem Simulação lm324 circuito
# Imagem Simulação lm324 grafico
# Imagem Simulação tl082 circuito
# Imagem Simulação tl082 grafico
## Conclusões
Em relação a configuração não inversora, ambos ampops apresentaram o ganho esperado de 11, excluindo imperfeições
# Parte 04 - Subtrator
* Vout: (Vin+) - (Vin-)
* Resistores de entrada: 51k
* Resistor de Realimentação: 510K
* Tensão de entrada positiva = Tensão de entrada negativa.
* Tensão de saída: 0V
# Imagem circuito subtrator
# imagem grafico lm324 0,5 vpico
# imagem grafico tl082 0,5 vpico
## Resultados - 0,5 Vpico
Considerando um ganho de 10
Ampop | Vin+ | Vin- | Saída | Voffset Datasheet
----- | ---- | ---- | ----- | ---------------
LM324n | 230,5 mV | 228 mV | 35,5 mV | 2 mV (typ) / 3 mV (Max)
Tl082 | 226,796 mV | 226,792 mV | 4,07 mV | 3 mV (typ) / 6 mV (Max)
# imagem grafico lm324 0 vpico
# imagem grafico tl082 0 vpico
## Resultados - 0 V
Considerando um ganho de 10.
AmpOp | Vin+ | Vin- | Saída | Voffset datasheet
----- | ---- | ---- | ----- | -----------------
LM324n | 952,758 uV | 3,72 mV | 31,44 mV | 2 mV (Typ) / 3 mV (Max)
TL082 | -1,91 uV | 9 uV | 120 uV | 2 mV (Typ) / 3 mV (Max)
## Resultados - 0V - Circuito 1 / Circuito 2
Considerando ganho de 10
AmpOp | Circuito | Vout
----- | -------- | -----
LM324n | Circuito 1 | 31,44 mV
LM324n | Circuito 2 | 31,43 mV
TL082 | Circuito 1 | 120 uV
TL082 | Circuito 2 | 120,67 uV
## Conclusões
A tensão na saída é diferente de zero devido a tensão de offset, além disso a tensão de offset simulada é diferente do datasheet, o que demonstra a presença de outras imperfeições. O ampop TL082 apresentou uma tensão de offset muito inferior ao valor do datasheet
Por último, as duas topologias de circuito apresentam leves diferenças na saída, pois mesmo mudando a posição de um resistor de entrada, a impedância de entrada continua a mesma
