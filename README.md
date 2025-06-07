# GS-Edge-Computing-IoT
# Sistema de Alerta de Enchentes com Arduino

## Descrição do Problema
Enchentes causam sérios prejuízos materiais e riscos à vida. Um sistema de monitoramento de nível de água pode ajudar na prevenção e resposta rápida a esses eventos.

## Solução Proposta
Criamos um sistema de alerta que detecta a altura da água usando um sensor ultrassônico HC-SR04. O sistema fornece alertas visuais e sonoros quando a água ultrapassa o nível de segurança.

## Componentes Usados
- Arduino Uno
- Sensor HC-SR04
- LCD 16x2 com I2C
- LED vermelho
- Buzzer
- Jumpers e resistores
- Simulador Wokwi

## Funcionamento
- Até 20 cm: nível seguro (LCD indica "Nível Seguro")
- Entre 10 e 20 cm: nível de atenção (LCD indica "Atenção")
- Abaixo de 10 cm: nível de alerta (LED acende, buzzer toca, LCD mostra "ALERTA!")

## Simulador Wokwi
- [Acesse o projeto aqui]([https://wokwi.com/projects/SEU-LINK-AQUI](https://wokwi.com/projects/430746070009397249))

## Vídeo Demonstrativo
- [Assista ao vídeo aqui](https://)
