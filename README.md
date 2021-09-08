# Guia dos Repositórios de ESP32

Uma compilação dos meus repositórios usando ESP32

### Resumo

Aqui temos uma ligação para todos os repositórios que venho desenvolvendo com ESP32. Os primeiros repositórios contém projetos mais simples e fáceis, a complexidade de projeto vai aumentando conforme a progressão. Contém um link para cada um dos repositórios e uma breve descrição de cada um, como o Framework escolhido e as tecnologias/periféricos usados(as). Os primeiros projetos foram construídos usando o framework Arduíno, porém depois houve uma mudança para usar o framework nativo do ESP32, o ESP SDK IDF em linguagem C.  
 
### Como Instalar e Usar

Todos esses projetos foram desenvolvidos no PlatformIO do VSCode. Para obter instruções para clonar corretamente qualquer um destes repositórios, consulte o [Guia de Instruções PlatformIO](https://github.com/Zebio/Instrucoes-PlatformIO)

### Repositórios

[Projeto 01 - Controle de Saídas Independentes](https://github.com/Zebio/ESP32-Projeto01-Saidas-Independentes)  
Usa um disparo num contador de tempo para controlar várias saídas digitais com acionamentos totalmente independentes.   
Framework: Arduíno.  
Periféricos/Tecnologias: GPIOs, Disparo em Contagem de Tempo 


[Projeto 02 - Biblioteca para Leitura de Botões](https://github.com/Zebio/ESP32-Projeto02-Biblioteca-para-leitura-de-Botoes)  
Facilita a leitura de entradas digitais de interface com usuários como push-buttons  
Framework: Arduíno.  
Periféricos/Tecnologias: GPIOs, Disparo em Contagem de Tempo.

[Projeto 03 - Leitura do ADC e Driver de Motor DC 9V com PWM](https://github.com/Zebio/ESP32-Projeto03-ADC-e-Controle-de-Motor-com-PWM)  
Lê o valor de tensão no ADC e o Converte para o duty cicle de um PWM que chaveia um motor DC 9V.  
Framework: Arduíno.  
Periféricos/Tecnologias: ADC, PWM, Circuito Driver de motor DC.

[Projeto 04 - Gerador de Funções](https://github.com/Zebio/ESP32_Projeto04-Gerador-de-Funcoes)  
Através de uma interface com o usuário contendo um display 16x2 e botões touch, controla 2 canais independentes no DAC que podem gerar as funções Triângulo, Pulso, Seno e Dente-de-Serra  
Framework: Arduíno.  
Periféricos/Tecnologias: DAC, Interface para o display 16x2, sensores touch, geração de saídas usando "math.h".

[Projeto 05 - Controlador PID](https://github.com/Zebio/ESP32-Projeto05-Controlador-PID)  
Usa controle Proporciona, Integral e Derivativo para controlar uma malha de controle fechada composta por LEDs que têm sua intensidade controlada por PWM e sensores de luminosidade captando a intensidade dos LEDs  
Framework: Arduíno.  
Periféricos/Tecnologias: Controle PID, PWM, ADC

[Projeto 06 - Web Server para Automação Wireless](https://github.com/Zebio/ESP32-Projeto06-Web-Server)  
Automação Residencial/Industrial onde temos um web server http que controla 2(ou mais) saídas digitais via Wireless.  
Framework: Arduíno.  
Periféricos/Tecnologias: Wireless, Http server.

[Projeto 07 - Acompanhamento de Nível de Carga de Bateria de Lítio Wireless](https://github.com/Zebio/ESP32-Projeto07-Nivel-de-Carga-Wireless)  
Cria um http server via Wireless na rede para realizar monitoramento da porcentagem estimada de carga de uma bateria Li-ion.    
Framework: Arduíno.  
Periféricos/Tecnologias: Wireless, Http server.

[Projeto 08 - Acompanhamento de Nível de Carga de Bateria de Lítio Wireless - Framework ESP IDF](https://github.com/Zebio/ESP32-Projeto08-Carga-Wireless)  
Cria um http server via Wireless na rede para realizar monitoramento da porcentagem estimada de carga de uma bateria Li-ion.    
Framework: ESP SDK IDF   
Periféricos/Tecnologias: Wireless, Http server, RTOS tasks.

[Projeto 09 - Web Server para Automação Wireless - Framework ESP IDF](https://github.com/Zebio/ESP32-Projeto09-Http-Server)  
Automação Residencial/Industrial onde temos um web server http que controla 2(ou mais) saídas digitais via Wireless.  
Framework ESP SDK IDF   
Periféricos/Tecnologias: Wireless, Http server.

[Projeto 10 - Gerador PWM - Framework ESP IDF](https://github.com/Zebio/ESP32-Projeto10-Gerador-PWM)   
Cria um http server via Wireless que controla um gerador PWM profissional com 2 canais e regulagens de frequência(resolução do duty adaptável à frequência) e duty cicle.  
Framework: ESP SDK IDF  
Periféricos/Tecnologias: Wireless, Http server, PWM.

[Projeto 11 - Caixa-D'agua](https://github.com/Zebio/Projeto11-Caixa_dagua)     
Esse projeto alimentado com energia solar monitora o nível de uma caixa d'agua a distância usando o ESP32 e BLE para enviar informações.     
Framework: Arduíno.       
Periféricos/Tecnologias: Bluetooth Low Energy    


[Projeto 12 - Carro Controlado por Controle ps3](https://github.com/Zebio/Projeto12_ps3_controller_car)
Controla um carrinho de brinquedo através de um controle de ps3, conectando o ESP e o Controle por bluetooth. É usando um CI Driver de motor para tração e direção do carro.   
Framework: Arduíno.    
Periféricos/Tecnologias: Bluetooth.  


