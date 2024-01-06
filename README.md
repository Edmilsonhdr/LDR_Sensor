# Projeto Arduino com Sensor de Luz LDR

Este é um projeto simples que utiliza um sensor de luz LDR em conjunto com uma placa Arduino para detectar luminosidade e controlar um LED.

## Componentes Necessários
- Arduino Board
- Sensor de Luz LDR
- LED
- Resistor (opcional, para limitar a corrente do LED)
- Fios de Conexão

## Instalação
1. Conecte o Sensor de Luz LDR ao pino analógico A0 do Arduino.
2. Conecte o LED ao pino digital D13 do Arduino.
3. (Opcional) Se necessário, utilize um resistor para limitar a corrente do LED.

## Uso
1. Carregue o código `LDR_Sensor.ino` no Arduino IDE.
2. Conecte a placa Arduino ao computador e faça o upload do código.
3. Abra o Monitor Serial para visualizar as leituras do sensor.

## Funcionamento
- O LED se acenderá se a luminosidade ultrapassar o valor definido como "Limiar".
- O monitor serial exibirá as leituras do sensor.


