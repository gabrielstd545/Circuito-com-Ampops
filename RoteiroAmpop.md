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
# Parte 01 - Buffer
O ampop na configuração buffer tem o seguinte funcionamento, todo o sinal de saída tem que ser igual ao sinal de entrada, sem ocorrer distorções na forma de onda.
## Buffer
Figura 1 - Circuito Buffer teórico
![](lab%20ampop/buffer/buffer.jpg)
# Simulação Do Lm324n LTSpice
Figura 2 - Circuito buffer utilizando o ampop Lm324n
![](lab%20ampop/buffer/Simula%C3%A7%C3%A3o%20Do%20Lm324n%20LTSpice%20-%20circuito.jpg)
Obs: Buffer realimentado para diminuição da corrente de polarização
# Simulação Do Lm324n LTSpice 
Tensão de entrada x Tensão de saída
![](lab%20ampop/buffer/Simula%C3%A7%C3%A3o%20Do%20Lm324n%20LTSpice%20-%20simula%C3%A7%C3%A3o.jpg)
# Comparação dos resultados
Tensões (V) | Tensões de Pico (V) | Tensão Máxima (V) | Tensão Mínima (V)
----------- | ------------------- | ----------------- | ----------------
Tensão de entrada teórica | 0,5 | 0,5 | -0,5 
Tensão de entrada simulada | 0,5 | 0,5 | -0,5
Tensão de saída teórica | 0,5 | 0,5 | -0,5
Tensão de saída simulada | 0,5 | 0,5 | -0,5
# TL082 - Simulação
![](lab%20ampop/buffer/TL082%20%E2%80%93%20SIMULA%C3%87%C3%83O%20-%20circuito.jpg)
# TL082 - Simulação
![](lab%20ampop/buffer/TL082%20%E2%80%93%20SIMULA%C3%87%C3%83O%20-%20simula%C3%A7%C3%A3o.jpg)
Tensões (V) | Tensões de Pico (V) | Tensão Máxima (V) | Tensão Mínima (V)
----------- | ------------------- | ----------------- | ----------------
Tensão de entrada teórica | 0,5 | 0,5 | -0,5 
Tensão de entrada simulada | 0,5 | 0,5 | -0,5
Tensão de saída teórica | 0,5 | 0,5 | -0,5
Tensão de saída simulada | 0,5 | 0,5 | -0,5
# Conclusão
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
# Cálculo do ganho inversor
* Vout: - (Rr/Re)*Vin
* Resistor de entrada: 2k
* Resistor de Realimentação: 20K
* Ganho de: 10
* Tensão de entrada: 0,5V
* Tensão de saída: 5V
# Simulação LM324n
![](lab%20ampop/inversor/simula%C3%A7%C3%A3o%20lm324%20circuito.jpg)
# Simulação LM324n
![](lab%20ampop/inversor/lm324%20SIMULA%C3%87%C3%83O%20-%20grafico.jpg)
# Simulação do TL082
![](lab%20ampop/inversor/TL082%20%E2%80%93%20SIMULA%C3%87%C3%83O%20-%20circuito.jpg)
# Simulação do TL082
![](lab%20ampop/inversor/TL082%20%E2%80%93%20SIMULA%C3%87%C3%83O%20-%20grafico.jpg)
# Conclusões
Em relação a configuração inversora, ambos ampops apresentaram o ganho de 10, excluindo as imperfeições.

Parte 03 - Não Inversor
* Objetivo Específico: Medir o ganho de um amplificador inversor.
* Experimento: Utilizando os ampops Lm324n e TL082 na configuração de amplificador inversor.
Especificações
* Resistor de entrada: 2k
* Resistor de Realimentação: 20K
* Alimentação: +/- 12V
* Gerador de Funções: 0,5Vpp
# Cálculo do ganho não inversor
* Vout: (1 + Rr/Re)*Vin
* Resistor de entrada: 2k
* Resistor de Realimentação: 20K
* Ganho de: 11
* Tensão de entrada: 0,5V
* Tensão de saída: 5,5V
* Frequência: 1KHz


