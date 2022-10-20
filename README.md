# Irrigador Automático 

Este é um projeto para a disciplina de programção de software básico em C

Um dos requisitos era utilizar o arduino na construção do projeto. Para isso foi utilizado o TinkerCAD, plataforma que simula os circuitos e nos dá a possibilidade de rodar o projeto sem a necessidade de termos as peças em mãos.

O meu projeto foi baseado na idéia de um irrigador automático, utilizando um sensor de umidade para verificar a situação do solo. Após a verificação do nível de água no solo, o irrigador identifica a situação baseado nos parâmetros configurados, se o solo necessitar a rega é realizada.

Para o monitoramento são utilizados 3 LEDs( Vermelho, Verde, Amarelo), e uma tela LCD.

Para a representação da Bomba D'água é utilizada uma lâmpada, alimentada por um simulador de função, que representaria a fonte de energia externa, e um relé que conectado ao arduíno que realiza o ativamento do mesmo. O ciclo se repete a cada 5 segundos.

Classificações:
- Terra Seca 
- Terra Meio Seca 
- Terra úmida 

Componentes:
1- Arduino Uno R3
1- LCD 16 x 2
1- 250 kΩ Potenciômetro
1- 220 Ω Resistor
1- Sensor de umidade do solo
3- 220 kΩ Resistor
1- Lâmpada
1- Relé SPDT
3- LEDs

