# Guia dos Repositórios de ESP32

### Resumo

Aqui temos uma ligação para todos os repositórios que venho desenvolvendo com ESP32. Os primeiros repositórios contém projetos mais simples e fáceis, a complexidade de projeto vai aumentando conforme a progressão. Contém um link para cada um dos repositórios e uma breve descrição de cada um, como o Framework escolhido e as tecnologias/periféricos usados(as). Os primeiros projetos foram construídos usando o framework Arduíno, porém depois houve uma mudança para usar o framework nativo do ESP32, o ESP SDK IDF em linguagem C.  
 
### Como usar

Todos esses projetos foram desenvolvidos no PlatformIO do VSCode. Para obter instruções para clonar corretamente qualquer um destes repositórios, consulte o [Guia de Instruções PlatformIO](https://github.com/Zebio/Instrucoes-PlatformIO)

### Repositórios

[Projeto 01 - Controle de Saídas Independentes](https://github.com/Zebio/ESP32-Projeto01-Saidas-Independentes)  
Usa um disparo num contador de tempo para controlar várias saídas digitais com acionamentos totalmente independentes.   
Framework/Linguagem: Arduíno.  
Periféricos/Tecnlogias: GPIOs, Disparo em Contagem de Tempo 


[Projeto 02 - Biblioteca para Leitura de Botões](https://github.com/Zebio/ESP32-Projeto02-Biblioteca-para-leitura-de-Botoes)  
Facilita a leitura de entradas digitais de interface com usuários como push-buttons  
Framework/Linguagem: Arduíno.  
Periféricos/Tecnlogias: GPIOs, Disparo em Contagem de Tempo.

[Projeto 03 - Leitura do ADC e Driver de Motor DC 9V com PWM](https://github.com/Zebio/ESP32-Projeto03-ADC-e-Controle-de-Motor-com-PWM)  
Lê o valor de tensão no ADC e o Converte para o duty cicle de um PWM que chaveia um motor DC 9V.  
Framework/Linguagem: Arduíno.  
Periféricos/Tecnlogias: ADC, PWM, Circuito Driver de motor DC.

[Projeto 04 - Gerador de Funções](https://github.com/Zebio/ESP32_Projeto04-Gerador-de-Funcoes)  
Através de uma interface com o usuário contendo um display 16x2 e botões touch, controla 2 canais independentes no DAC que podem gerar as funções Triângulo, Pulso, Seno e Dente-de-Serra  
Framework/Linguagem: Arduíno.  
Periféricos/Tecnlogias: DAC, Interface para o display 16x2, sensores touch, geração de saídas usando "math.h".

[Projeto 05 - Controlador PID](https://github.com/Zebio/ESP32-Projeto05-Controlador-PID)  
Usa controle Proporciona, Integral e Derivativo para controlar uma malha de controle fechada composta por LEDs que têm sua intensidade controlada por PWM e sensores de luminosidade captando a intensidade dos LEDs  
Framework/Linguagem: Arduíno.  
Periféricos/Tecnlogias: Controle PID, PWM, ADC

[Projeto 06 - Web Server para Automação Wireless](https://github.com/Zebio/ESP32-Projeto06-Web-Server)  
Automação Residencial/Industrial onde temos um web server http que controla 2(ou mais) saídas digitais via Wireless.  
Framework/Linguagem: Arduíno.  
Periféricos/Tecnlogias: Wireless, Http server.

[Projeto 07 - Acompanhamento de Nível de Carga de Bateria de Lítio Wireless](https://github.com/Zebio/ESP32-Projeto07-Nivel-de-Carga-Wireless)  
Cria um http server via Wireless na rede para realizar monitoramento da porcentagem estimada de carga de uma bateria Li-ion.    
Framework/Linguagem: Arduíno.  
Periféricos/Tecnlogias: Wireless, Http server.

[Projeto 08 - Acompanhamento de Nível de Carga de Bateria de Lítio Wireless - Framework ESP IDF](https://github.com/Zebio/ESP32-Projeto08-Carga-Wireless)  
Cria um http server via Wireless na rede para realizar monitoramento da porcentagem estimada de carga de uma bateria Li-ion.    
Framework/Linguagem: ESP SDK IDF / C  
Periféricos/Tecnlogias: Wireless, Http server, RTOS tasks.

[Projeto 09 - Web Server para Automação Wireless - Framework ESP IDF](https://github.com/Zebio/ESP32-Projeto09-Http-Server)  
Automação Residencial/Industrial onde temos um web server http que controla 2(ou mais) saídas digitais via Wireless.  
Framework/Linguagem: ESP SDK IDF / C  
Periféricos/Tecnlogias: Wireless, Http server.

[Projeto 10 - Gerador PWM - Framework ESP IDF](https://github.com/Zebio/ESP32-Projeto10-Gerador-PWM) (Projeto Incompleto)  
Cria um http server via Wireless que controla um gerador PWM profissional com 2 canais e regulagens de frequência(resolução do duty adaptável à frequência) e duty cicle.  
Framework/Linguagem: ESP SDK IDF / C  
Periféricos/Tecnlogias: Wireless, Http server, PWM.
