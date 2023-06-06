# GS-Edge
# Validity Control - Controle de Validade

Este projeto consiste em um sistema de controle de validade de produtos alimentícios utilizando a plataforma Arduino. O objetivo é evitar o desperdício de alimentos e garantir a segurança alimentar, alertando os responsáveis quando a data de validade de um produto está próxima.

## Funcionamento

O sistema utiliza um display LCD para exibir a quantidade de dias de validade restantes para o produto em questão. Os botões de incremento e decremento permitem ajustar a quantidade de dias de validade inicialmente definida. 

A cada 24 horas (definido como 10.000 milissegundos), o sistema incrementa o número de dias decorridos e verifica se a porcentagem da validade atingiu 80%. Caso tenha atingido, o buzzer é acionado para alertar os responsáveis sobre a proximidade da data de validade.

## Componentes utilizados

- Arduino Uno
- Display LCD 16x2
- Buzzer
- Botões de incremento e decremento
- LDR (Light Dependent Resistor)

## Configuração do hardware

- Display LCD: Conectado aos pinos 12, 11, 10, 5, 4, 3 e 2 do Arduino.
- Buzzer: Conectado ao pino 9 do Arduino.
- Botões de incremento e decremento: Conectados aos pinos 6 e 7 do Arduino, respectivamente.

## Instalação e Execução

1. Faça as devidas conexões entre o Arduino e os componentes conforme descrito na seção de configuração do hardware.
2. Abra o código fornecido no Arduino IDE.
3. Compile e faça o upload do código para o Arduino.
4. Observe as informações no display LCD e teste os botões de incremento e decremento para ajustar a quantidade de dias de validade.
5. O buzzer será acionado quando 80% da validade for atingida.

## Resultados Esperados

- Gerenciamento de estoque mais eficiente e organizado.
- Redução do desperdício de alimentos por prazos vencidos.
- Melhoria na segurança alimentar, evitando o consumo de produtos vencidos.
- Planejamento de compras mais preciso.
- Aumento da organização e eficiência no controle de validade.

## Impacto

- Contribuição para a redução do desperdício de alimentos.
- Economia financeira ao evitar descartes desnecessários.
- Promover a conscientização sobre a importância do controle de validade e segurança alimentar.
- Estimular o uso de tecnologias como o Arduino para soluções sustentáveis.

## Nomes e rms
[Adriano Lopes rm: 98574]
[Diogo Ramos Fernandes rm: 551752]
[Filipe Soares rm: 97830]
[Gustavo Medeiros rm: 552093]
