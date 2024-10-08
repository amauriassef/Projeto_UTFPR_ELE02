<p align="center">
  <img src="https://github.com/amauriassef/Projeto_UTFPR_ELE02/blob/main/Figuras/Placa_Micro_TB_montada.jpg"/>
  <img src="https://github.com/amauriassef/Projeto_UTFPR_ELE02/blob/main/Figuras/Placa_Micro_TB_BluePill.jpg"/>
</p>

- [1. Projeto UTFPR ELE02](#1-Projeto-UTFPR-ELE02)
   * [1.1 Universidade Tecnológica Federal do Paraná](#11-Universidade-Tecnológica-Federal-do-Paraná)
   * [1.2 Título](#12-Título)
   * [1.3 Descrição](#13-Descrição)
   * [1.4 Equipe](#14-Equipe)
   * [1.5 Documentação](#15-Documentação)
     + [1.5.1 Características](#151-Características)
     + [1.5.2 Versão do projeto](#152-Versão-do-projeto)
     + [1.5.3 Histórico de versão](#153-Histórico-de-versão)
     + [1.5.4 Informações para fabricação da placa](#154-Informações-para-fabricação-da-placa)
   * [1.6 Pinagem do kit](#16-Pinagem-do-kit)
     + [1.6.1 Descrição dos sinais da placa MICROTB_UTFPR](#161-Descrição-dos-sinais-da-placa-MICROTB_UTFPR)
     + [1.6.2 Descrição dos sinais por funcionalidade](#162-Descrição-dos-sinais-por-funcionalidade) 
        + [1.6.2.1 LEDs](#1621-LEDs) 
        + [1.6.2.2 Chaves push-button](#1622-Chaves-push-button) 
        + [1.6.2.3 Displays de 7 segmentos multiplexados](#1623-Displays-de-7-segmentos-multiplexados) 
        + [1.6.2.4 Display LCD 16x2](#1624-Display-LCD-16x2)
        + [1.6.2.5 Motor de passo e servomotor](#1625-Motor-de-passo-e-servomotor)
        + [1.6.2.6 Módulo sensor de ultrassom HC-04](#1626-Módulo-sensor-de-ultrassom-HC-04)
        + [1.6.2.7 Módulo Bluetooth HC-05 ou HC-06](#1627-Módulo-Bluetooth-HC-05-ou-HC-06)
        + [1.6.2.8 Módulo WiFi ESP8266](#1628-Módulo-WiFi-ESP8266)
        + [1.6.2.9 Módulo I2C sensor de pressão BMP280](#1629-Módulo-I2C-sensor-de-pressão-BMP280)
        + [1.6.2.10 Sinais analógicos](#16210-Sinais-analógicos)
        + [1.6.2.11 Jumpers](#16211-Jumpers)
        + [1.6.2.12 Conectores](#16212-Conectores)
        + [1.6.2.13 Sinais não conectados da placa Tiva LaunchPad](#16213-Sinais-não-conectados-da-placa-Tiva-LaunchPad)
        + [1.6.2.14 Sinais não conectados da placa Blue Pill](#16214-Sinais-não-conectados-da-placa-Blue-Pill)
- [2. Links com informações sobre as placas de avaliação compatíveis](#2-Links-com-informações-sobre-as-placas-de-avaliação-compatíveis)
   * [2.1 Placa TIVA C Series TM4C123G LaunchPad](#21-placa-TIVA-C-Series-TM4C123G-LaunchPad)
     + [2.1.1 Links do professor Jonathan W Valvano](#211-Links-do-professor-Jonathan-W-Valvano)
   * [2.2 Placa Blue Pill](#22-placa-Blue-Pill)
   * [2.3 Placa Black Pill](#23-placa-Black-Pill)
- [3. Site para download do software Eagle](#3-Site-para-download-do-software-Eagle)
- [4. Site do projeto](#4-Site-do-projeto)  
- [5. Como citar este trabalho](#5-Como-citar-este-trabalho)  
- [6. Informação de licença](#6-Informação-de-licença)  

# 1. Projeto UTFPR ELE02 

## 1.1 Universidade Tecnológica Federal do Paraná

![UTFPR Logo](/Figuras/UTFPR1.png)

* Departamento Acadêmico de Eletrotécnica (DAELT) - Campus Curitiba
* Departamento Acadêmico de Eletrônica (DAELN) - Campus Curitiba
* Departamento de Eletrônica (DAELE) - Campus Ponta Grossa
* Link: http://www.utfpr.edu.br/

## 1.2 Título 

Desenvolvimento de um kit microcontrolado de baixo custo para apoio ao ensino remoto - Projeto ELE02 
 
## 1.3 Descrição 

Projeto do circuito esquemático e *layout* da placa de circuito impresso (PCB) **MICROTB_UTFPR** utilizando o software [Eagle 9.6.2](https://www.autodesk.com/products/eagle/). A placa **MICROTB_UTFPR** permite conexão com a placa TIVA™ C Series TM4C123G LaunchPad ou Blue-Pill para aplicações de Sistemas Microcontrolados envolvendo automação, controle e IoT, entre outras.

Projeto aprovado no [Edital 37/2020 PROGRAD – UTFPR – Área temática de Sistemas Microcontrolados](http://portal.utfpr.edu.br/editais/graduacao-e-educacao-profissional/reitoria/edital-37-2020-prograd) como apoio no desenvolvimento dos Recursos Educacionais Abertos (REA).

Para fins do Edital 37/2020, entende-se que Recursos Educacionais Abertos (REA) “são materiais de aprendizado, ensino e pesquisa em qualquer formato e mídia de domínio público ou com direitos autorais liberados sob uma licença aberta, que permitem acesso, reutilização sem custo, adaptação e redistribuição gratuita” [(UNESCO, 2019)](http://www.unesco.org/new/fileadmin/MULTIMEDIA/HQ/CI/CI/pdf/publications/oer_guidelines_pt.pdf).

## 1.4 Equipe 
 
* Amauri Amorin Assef – Coordenador – http://lattes.cnpq.br/0720172921923496
* Guilherme Luiz Moritz – Colaborador – http://lattes.cnpq.br/0736175449254807
* Delvanei Gomes Bandeira Junior – Colaborador – http://lattes.cnpq.br/2233204054325472
* Guilherme de Santi Peron – Colaborador –  http://lattes.cnpq.br/7845448730478685
* Maurício dos Santos Kaster – Colaborador – http://lattes.cnpq.br/5494434934031784
* Murilo Paulo de Oliveira – Bolsista – http://lattes.cnpq.br/1578999659029568
* Cáled Tarique Pereira – Voluntário – http://lattes.cnpq.br/5596843081337675
 
## 1.5 Documentação

* [**BOM_MICROTB**](/BOM_MICROTB) - Lista de material (*bill of material*) da placa MICROTB_UTFPR.
* [**CAD_EAGLE_9_6_2_MICROTB**](/CAD_EAGLE_9_6_2_MICROTB) - Projeto do circuito esquemático e *layout* da placa MICROTB_UTFPR.
* [**LIB_MICROTB**](/LIB_MICROTB) - Biblioteca com os componentes do circuito esquemático e placa MICROTB_UTFPR.
* [**PDF_MICROTB**](/PDF_MICROTB) - Arquivos em formato PDF para visualização do circuito esquemático e projeto da placa.

Obs: após abrir o arquivo da placa (board) no software Autodesk Eagle versão 9.6.2 (© 2020 Autodesk, Inc.), clicar em **Ratsnest** para mostrar os planos de GND dos layers *top* e *bottom*.

### 1.5.1 Características

* Permite conexão com as placas TIVA™ C Series TM4C123G LaunchPad e Blue Pill
* 2 displays de 7 segmentos tipo catodo comum multiplexados
* 8 LEDs para controle lógico visual
* Sensor de temperatura LM35
* Potenciômetro para leitura analógica
* Driver ponte-H dupla L293D para controle de motor de passo e CC
* Conector para módulo WiFi ESP8266
* Conector para módulo Bluetooth HC-05/06
* Conector para controle de micro servomotor de 3 fios com sinal PWM
* Conector para módulo sensor ultrassônico HC-04
* Conector para módulo sensor de sensor de pressão BMP280
* Display alfanumérico LCD 16x2 no modo de 4 bits
* Alimentação pela USB ou fonte externa de 9 V/1 A com conector do tipo P4 (2,5 x 5,5 mm)

### 1.5.2 Versão do projeto

**MICROTB_UTFPR V1.0** - Versão inicial do projeto

### 1.5.3 Histórico de versão 

**V1.0** - Versão inicial da placa MICROTB_UTFPR 

### 1.5.4 Informações para fabricação da placa

* Material: Dupla face FR4
* Dimensão da placa: 100 x 80 (mm2)
* Espessura da PCI: 1,60 mm
* Acabamento Superficial: HAL (Sn/Pb)
* Espessura final do cobre externo (Base + Plating): 1.0oz
* Cor da máscara de solda (top): Verde
* Cor da máscara de componentes (top): Branca
* Menor pista: 0,28 mm (11 mil)
* Menor isolação: 0,305 mm (12 mil)

<p align="center">
  <img src="https://github.com/amauriassef/Projeto_UTFPR_ELE02/blob/main/Figuras/Propriedades_microtb_utfpr_v1_pcb.png"/>
</p>

## 1.6 Pinagem do kit

### 1.6.1. Descrição dos sinais da placa MICROTB_UTFPR

|Conector TIVA|	Pino do conector M1 (Tiva)|	Sinal Tiva|	Pino do conector M2 (Blue Pill)|	Sinal Blue Pill|	Sinal Black Pill |Nome do sinal final|	Interface  |	Direção    |
|:---:        |:---:                      |:---:      |:---:                           |:---:            |:---:              |:---:              |:---:        |:---:        |
|J1-1	        |1                          |	3,3 V     |	18, 21                         |	3,3 V          |	3,3 V            |	+3V3(TB)         |	Alimentação|	Alimentação|
|J1-2         |3                          |	PB5       |	10                             |	PA5            |	PA6              |	PB5_PA5          |	LED6, SEG_F e LCD_D5       | OUT    |  
|J1-3       	|5	                        |PB0	      |5	                             |PA0	|NRST	|PB0_PA0	|LED1 e SEG_A|	OUT/NC|
|J1-4	|7	|PB1	|6	|PA1	|PA0  |PB1_PA1	|LED2 e SEG_B|	OUT|
|J1-5	|9	|PE4	|16	|PB11	|PB2 |PE4_PB11	|ESP_TX, BLUETOOTH_TX e BMP280	|IN|
|J1-6	|11	|PE5	|15	|PB10	|PB1 |PE5_PB10	|ESP_RX, BLUETOOTH_RX e BMP280	|OUT|
|J1-7	|13	|PB4	|6	|PA4 |PA3	|PB4_PA4	|LED5, SEG_E e LCD_D4	|OUT|
|J1-8	|15	|PA5	|34	|PA10 |PA10	|PA5_PA10	|EN_DISP1	|OUT|
|J1-9	|17	|PA6	|31	|PA15 |PA15	|PA6_PA15	|EN_DISP2	|OUT|
|J1-10	|19	|PA7| PA6|	-|	-	|	-	|-|	-	|NC|
|J2-1	|22	|GND	|19, 22|	GND	|	GND |GND	|Alimentação	|Alimentação|
|J2-2	|24	|PB2	|7	|PA2	|PA1 |PB2_PA2	|LED3 e SEG_C|	OUT|
|J2-3	|26	|PE0	|29	|PB4	|PB4 |PE0_PB4	|ESP_GPIO02	|IN/OUT|
|J2-4	|28	|PF0	|24	|PB9	|PB9 |PF0_PB9	|SW2	|IN|
|J2-5	|30	|RESET	|-	|-	 |-	|-	|-	|NC
|J2-6	|32	|PB7/PD1	|12	|PA7	|PA6 |PB7_PA7	|LED8, SEG_DP e LCD_D7	|OUT|
|J2-7	|34	|PB6/PD0	|11	|PA6	|PA5 |PB6_PA6	|LED7, SEG_G e LCD_D6	|OUT|
|J2-8	|36	|PA4	|28	|PB5	|PB5 |PA4_PB5	|EN_LEDS	|OUT|
|J2-9	|38	|PA3	|40	|PB12	|PB12 |PA3_PB12	|LCD_E	|OUT|
|J2-10	|40	|PA2	|39	|PB13	|PB13 |PA2_PB13	|LCD_RS	|OUT|
|J3-1	|2	|5,0 V	|23	|5,0 V	|5,0 V |+5V(TB)	|Alimentação	|Alimentação|
|J3-2	|4	|GND	|19, 22	|GND	|GND |GND	|Alimentação	|Alimentação|
|J3-3	|6	|PD0/PB6	|-	|-	|-	|-	|-	|NC|
|J3-4	|8	|PD1/PB7	|-	|-	|-	|-	|-	|NC|
|J3-5	|10	|PD2	|36	|PA8	|PA8 |PD2_PA8	|L293D_M3	|OUT|
|J3-6	|12	|PD3	|35	|PA9	|PA9 |PD3_PA9	|L293D_M4	|OUT|
|J3-7	|14	|PE1	|30	|PB3	|PB3 |PE1_PB3	|ESP_RST	| OUT|
|J3-8	|16	|PE2	|14	|PB1	|PB0 |PE2_PB1	|LM35	|IN (ADC)|
|J3-9	|18	|PE3	|13	|PB0	|PA7 |PE3_PB0	|Trimpot	|IN (ADC)|
|J3-10	|20	|PF1	|2	|PC13	|PC13 |PF1_PC13	|US_TRIGGER	|OUT|
|J4-1	|21	|PF2	|-	|-	|-	|-	|NC|
|J4-2	|23	|PF3	|-	|-	|-	|-	|NC|
|J4-3	|25	|PB3	|8	|PA3	|PA2 |PB3_PA3	|LED4 e SEG_D	|OUT|
|J4-4	|27	|PC4	|27|	PB6	|	PB6 |PC4_PB6	|US_ECO	|IN|
|J4-5	|29	|PC5	|26	|PB7	|PB7 |PC5_PB7	|SERVO e L293D_EN	|OUT (PWM)|
|J4-6	|31	|PC6	|38	|PB14 |PB14	|PC6_PB14	|L293D_M1	|OUT|
|J4-7	|33	|PC7	|37	|PB15	|PB15 |PC7_PB15	|L293D_M2	|OUT|
|J4-8	|35	|PD6	|-	|-	|-	|-	|-	|NC|
|J4-9	|37	|PD7	|-	|-	|-	|-	|-	|NC|
|J4-10	|39	|PF4	|25	|PB8	|PB8 |PF4_PB8	|SW1	|IN|

NC - não conectado. 

### 1.6.2. Descrição dos sinais por funcionalidade

#### 1.6.2.1 LEDs

|Conector TIVA|	Pino do conector M1 (Tiva)|	Sinal Tiva|	Pino do conector M2 (Blue Pill)|	Sinal Blue Pill|	Sinal Black Pill | Nome do sinal final|	Interface  |	Direção    |
|:---:        |:---:                      |:---:      |:---:                          |:---:          |:---:           |:---:      |:---:        |:---:        |
|J2-8	|36	|PA4	|28	|PB5	|PB5 |PA4_PB5	|EN_LEDS	|OUT|
|J1-3	|5	|PB0	|5	|PA0	|NRST |PB0_PA0	|LED1	|OUT/NC|
|J1-4	|7	|PB1	|6	|PA1	|PA0 |PB1_PA1	|LED2	|OUT|
|J2-2	|24	|PB2	|7	|PA2	|PA1 |PB2_PA2	|LED3	|OUT|
|J4-3	|25	|PB3	|8	|PA3	|PA2 |PB3_PA3	|LED4	|OUT|
|J1-7	|13	|PB4	|6	|PA4	|PA3 |PB4_PA4	|LED5	|OUT|
|J1-2	|3	|PB5	|10	|PA5	|PA4 |PB5_PA5	|LED6	|OUT|
|J2-7	|34	|PB6/PD0	|11	|PA6	|PA5 |PB6_PA6	|LED7	|OUT|
|J2-6	|32	|PB7/PD1	|12	|PA7	|PA6 |PB7_PA7	|LED8	|OUT|

#### 1.6.2.2 Chaves push-button

|Conector TIVA|	Pino do conector M1 (Tiva)|	Sinal Tiva|	Pino do conector M2 (Blue Pill)|	Sinal Blue Pill|	Sinal Black Pill | Nome do sinal final|	Interface  |	Direção    |
|:---:        |:---:                      |:---:      |:---:                          |:---:          |:---:           |:---:      |:---:        |:---:        |
|J4-10	      |39	                         |PF4	         |25	                              |PB8	            |PB8               |PF4_PB8	             |SW1	         |IN         |
|J2-4	|28	|PF0	|24	|PB9	|PB9 |PF0_PB9	|SW2	|IN|

#### 1.6.2.3 Displays de 7 segmentos multiplexados
 
|Conector TIVA|	Pino do conector M1 (Tiva)|	Sinal Tiva|	Pino do conector M2 (Blue Pill)|	Sinal Blue Pill|	Sinal Black Pill | Nome do sinal final|	Interface  |	Direção    |
|:---:        |:---:                      |:---:      |:---:                          |:---:          |:---:           |:---:      |:---:        |:---:        |
|J1-8	|15	|PA5	|34	|PA10	|PA10 |PA5_PA10	|EN_DISP1	|OUT|
|J1-9	|17	|PA6	|31	|PA15 |PA15	|PA6_PA15	|EN_DISP2	|OUT|
|J1-3	|5	|PB0	|5	|PA0	|NRST |PB0_PA0	|SEG_A	|OUT/NC|
|J1-4	|7	|PB1	|6	|PA1	|PA0 |PB1_PA1	|SEG_B	|OUT|
|J2-2	|24	|PB2	|7	|PA2	|PA1 |PB2_PA2	|SEG_C	|OUT|
|J4-3	|25	|PB3	|8	|PA3	|PA2 |PB3_PA3	|SEG_D	|OUT|
|J1-7	|13	|PB4	|6	|PA4	|PA3 |PB4_PA4	|SEG_E	|OUT|
|J1-2	|3	|PB5	|10	|PA5	|PA4 |PB5_PA5	|SEG_F	|OUT|
|J2-7	|34	|PB6/PD0	|11	|PA6	|PA5 |PB6_PA6	|SEG_G	|OUT|
|J2-6	|32	|PB7/PD1	|12	|PA7	|PA6 |PB7_PA7	|SEG_DP	|OUT|

#### 1.6.2.4 Display LCD 16x2

|Conector TIVA|	Pino do conector M1 (Tiva)|	Sinal Tiva|	Pino do conector M2 (Blue Pill)|	Sinal Blue Pill|	Sinal Black Pill | Nome do sinal final|	Interface  |	Direção    |
|:---:        |:---:                      |:---:      |:---:                          |:---:          |:---:           |:---:      |:---:        |:---:        |
|J2-9	|38	|PA3	|40	|PB12	|PB12 |PA3_PB12	|LCD_E	|OUT|
|J2-10	|40	|PA2	|39	|PB13	|PB13 |PA2_PB13	|LCD_RS	|OUT|
|J1-7	|13	|PB4	|6	|PA4	|PA3 |PB4_PA4	|LCD_D4	|OUT|
|J1-2	|3	|PB5	|10	|PA5	|PA4 |PB5_PA5	|LCD_D5	|OUT|
|J2-7	|34	|PB6/PD0	|11	|PA6	|PA5 |PB6_PA6	|LCD_D6	|OUT|
|J2-6	|32	|PB7/PD1	|12	|PA7	|PA6 |PB7_PA7	|LCD_D7	|OUT|

#### 1.6.2.5 Motor de passo e servomotor

|Conector TIVA|	Pino do conector M1 (Tiva)|	Sinal Tiva|	Pino do conector M2 (Blue Pill)|	Sinal Blue Pill|	Sinal Black Pill | Nome do sinal final|	Interface  |	Direção    |
|:---:        |:---:                      |:---:      |:---:                          |:---:          |:---:           |:---:      |:---:        |:---:        |
|J4-5	|29	|PC5	|26	|PB7	|PB7 |PC5_PB7	|SERVO e L293D_EN	|OUT (PWM)|
|J4-6	|31	|PC6	|38	|PB14	|PB14 |PC6_PB14	|L293D_M1	|OUT|
|J4-7	|33	|PC7	|37	|PB15 |PB15	|PC7_PB15	|L293D_M2	|OUT|
|J3-5	|10	|PD2	|36	|PA8	|PA8	|PD2_PA8	|L293D_M3	|OUT|
|J3-6	|12	|PD3	|35	|PA9	|PA9	|PD3_PA9	|L293D_M4	|OUT|

#### 1.6.2.6 Módulo sensor de ultrassom HC-04

|Conector TIVA|	Pino do conector M1 (Tiva)|	Sinal Tiva|	Pino do conector M2 (Blue Pill)|	Sinal Blue Pill|	Sinal Black Pill | Nome do sinal final|	Interface  |	Direção    |
|:---:        |:---:                      |:---:      |:---:                          |:---:          |:---:           |:---:      |:---:        |:---:        |
|J3-10	|20	|PF1	|2	|PC13	|PC13 |PF1_PC13	|US_TRIGGER	|OUT|
|J4-4	|27	|PC4	|27	|PB6	|PB6 |PC4_PB6	|US_ECO	|IN|

#### 1.6.2.7 Módulo Bluetooth HC-05 ou HC-06

|Conector TIVA|	Pino do conector M1 (Tiva)|	Sinal Tiva|	Pino do conector M2 (Blue Pill)|	Sinal Blue Pill|	Sinal Black Pill | Nome do sinal final|	Interface  |	Direção    |
|:---:        |:---:                      |:---:      |:---:                          |:---:          |:---:           |:---:      |:---:        |:---:        |
|J1-5	|9	|PE4	|16	|PB11	|PB2 |PE4_PB11	|BLUETOOTH_TX	|IN|
|J1-6	|11	|PE5	|15	|PB10	|PB1 |PE5_PB10	|BLUETOOTH_RX	|OUT|

#### 1.6.2.8 Módulo WiFi ESP8266

|Conector TIVA|	Pino do conector M1 (Tiva)|	Sinal Tiva|	Pino do conector M2 (Blue Pill)|	Sinal Blue Pill|	Sinal Black Pill | Nome do sinal final|	Interface  |	Direção    |
|:---:        |:---:                      |:---:      |:---:                          |:---:          |:---:           |:---:      |:---:        |:---:        |
|J2-3	|26	|PE0	|29	|PB4	|PB4	|PE0_PB4	|ESP_GPIO02	|OUT|
|J3-7	|14	|PE1	|30	|PB3	|PB3	|PE1_PB3	|ESP_RST	|OUT|
|J1-5	|9	|PE4	|16	|PB11	|PB2	|PE4_PB11	|ESP_TX	|IN|
|J1-6	|11	|PE5	|15	|PB10	|PB1 |PE5_PB10	|ESP_RX	|OUT|

#### 1.6.2.9 Módulo I2C sensor de pressão BMP280

|Conector TIVA|	Pino do conector M1 (Tiva)|	Sinal Tiva|	Pino do conector M2 (Blue Pill)|	Sinal Blue Pill|	Sinal Black Pill | Nome do sinal final|	Interface  |	Direção    |
|:---:        |:---:                      |:---:      |:---:                          |:---:          |:---:           |:---:      |:---:        |:---:        |
|J1-5	|9	|PE4	|16	|PB11	|PB2 |PE4_PB11	|BMP280_SCL	|IN
|J1-6	|11	|PE5	|15	|PB10	|PB1 |PE5_PB10	|BMP280_SDA	|OUT

**Observação**: Inverter os sinais PE4_PB11 e PE5_PB10 para funcionamento do BMP280 com a placa Blue-Pill (PB10 – SCL e PB11 – SDA)

#### 1.6.2.10 Sinais analógicos

|Conector TIVA|	Pino do conector M1 (Tiva)|	Sinal Tiva|	Pino do conector M2 (Blue Pill)|	Sinal Blue Pill|	Sinal Black Pill | Nome do sinal final|	Interface  |	Direção    |
|:---:        |:---:                      |:---:      |:---:                          |:---:          |:---:           |:---:      |:---:        |:---:        |
|J3-8	|16	|PE2	|14	|PB1	|PB0 |PE2_PB1	|LM35	|IN (ADC)|
|J3-9	|18	|PE3	|13	|PB0	|PA7 |PE3_PB0	|Trimpot	|IN (ADC)|

#### 1.6.2.11 Jumpers

|Jumper|	Pinos |	Descrição|
|:---: |:---:   |:---:     |
|JP1	|1-2	|Alimentação pela USB (padrão)|
|JP1	|2-3	|Alimentação por fonte externa| 
|JP2	|1-2	|Utilizado para teste da placa MICROTB_UTFPR |
|JP2	|2-3	|Alimentação pelo regulador de 3,3 V da placa (padrão)|

#### 1.6.2.12 Conectores

|Posição	|Conexão|
|:---:    |:---:  |
|LCD1	|LCD 16x2|
|M1	|Placa Tiva LaunchPad|
|M2	|Placa Blue Pill|
|P1	|Servomotor|
|P2	|Motor de passo unipolar ou até dois motores CC|
|P3	|ESP8266|
|P4	|Módulo Bluetooth HC-05/HC-06|
|P5	|Módulo de pressão BPM280|
|P6	|Módulo sensor ultrassônico HC-04|
|U1	|Entrada da alimentação de 9 V|

#### 1.6.2.13 Sinais não conectados da placa Tiva LaunchPad

|Pino do conector M1	|Sinal Tiva	|Descrição|
|:---:                |:---:          |:---:    |
|19 (J1-10)	|PA7	|I/O|
|6 (J3-3)	|PD0	|Conectado por um resistor de 0R no PB6|
|8 (J3-4)	|PD1	|Conectado por um resistor de 0R no PB7|
|21 (J4-1)	|PF2	|LED Azul da placa Tiva|
|23 (J4-2)	|PF3	|LED Verde da placa Tiva|
|35 (J4-8)	|PD6	|I/O|
|37 (J4-9)	|PD7	|I/O NMI|
|30 (J2-5)	|RESET	|RESET|


#### 1.6.2.14 Sinais não conectados da placa Blue Pill

|Pino do conector M2	|Sinal Blue Pill	|Descrição|
|:---:                |:---:          |:---:    |
|3	|PC14	|OSC32IN|
|4	|PC15	|OSC32OUT|
|17	|NRST	|RESET BUTTON|
|20	|\*GND	|GND|
|32	|PA12	|USB+|
|33	|PA11	|USB+|

\*Sinal não conectado para compatibilidade com a placa BlackPill.

NRST - cortar o pino NRST

#### 1.6.2.15 Sinais não conectados da placa Black Pill

|Pino do conector M2	|Sinal Black Pill	|Descrição|
|:---:                |:---:          |:---:    |
|3	|PC14	|OSC32IN|
|4	|PC15	|OSC32OUT|
|5	|NRST	|RESET BUTTON|
|20	|+5V	|+5V|
|32	|PA12	|USB+|
|33	|PA11	|USB+|

NRST - cortar o pino NRST

# 2. Links com informações sobre as placas de avaliação compatíveis

## 2.1 Placa TIVA C Series TM4C123G LaunchPad

![Tiva Logo](/Figuras/Tiva1.jpg)

* [Página WEB da Texas Instruments](https://www.ti.com)
* [Tiva™ C Series TM4C123G LaunchPad Evaluation Board User’s Guide](https://www.ti.com/lit/ug/spmu296/spmu296.pdf)
* [Tiva™ TM4C123GH6PM Microcontroller Datasheet](https://www.ti.com/lit/ds/spms376e/spms376e.pdf)
* [Mini Curso - Getting Started with the TIVA™ C Series TM4C123G LaunchPad](http://software-dl.ti.com/trainingTTO/trainingTTO_public_sw/GSW-TM4C123G-LaunchPad/TM4C123G_LaunchPad_Workshop_Workbook.pdf)
* [Site ARM® Cortex®-M4F Based MCU TM4C123G LaunchPad™ Evaluation Kit](https://www.ti.com/tool/EK-TM4C123GXL)
* [TivaWare™ Peripheral Driver Library User's Guide](https://www.ti.com/lit/ug/spmu298d/spmu298d.pdf)
* [Drivers para o TM4C123 - TivaWare for C Series Software (Complete)](https://www.ti.com/tool/download/SW-TM4C)
* [e-Store Texas Instruments para o Launchpad](https://www.ti.com/store/ti/en/p/product/?p=EK-TM4C123GXL)

### 2.1.1 Links do professor Jonathan W Valvano

* [Página pessoal do professor Jonathan W. Valvano - Univerdidade do Texas em Austin](http://users.ece.utexas.edu/~valvano/)
* [Página do curso Embedded Systems - Shape the World: Microcontroller I/O](https://www.edx.org/course/embedded-systems-shape-the-world-microcontroller-i)
* [Página do curso Embedded Systems - Shape the World: Multi Threaded I/O](https://www.edx.org/course/embedded-systems-shape-the-world-multi-threaded-in)
* [Página do curso Embedded System no EDx (kit e softwares)](http://edx-org-utaustinx.s3.amazonaws.com/UT601x/index.html)


## 2.2 Placa Blue Pill

![Bluepill Logo](/Figuras/BluePill1.jpg)

* [Página WEB da STMicroelectronics](https://www.st.com/content/st_com/en.html)
* [Canal da STMicroelectronics no Youtube](https://www.youtube.com/c/stmicroelectronics/videos)
* [STM32world.com wiki](https://stm32world.com/wiki/Main_Page)
* [ST Flasher](https://github.com/stlink-org/stlink/releases)
* [Blue Pill - Informações Gerais](https://stm32-base.org/boards/STM32F103C8T6-Blue-Pill)
* [Blue Pill - Circuito esquemático (easyEDA)](https://easyeda.com/r3bers/STM32F103C8T6-Test-Board)
* [Blue Pill - Datasheet do STM32F103C8](https://www.st.com/resource/en/datasheet/stm32f103c8.pdf)
* [Blue Pill - Reference Manual do STM32F103C8](https://www.st.com/resource/en/reference_manual/cd00171190-stm32f101xx-stm32f102xx-stm32f103xx-stm32f105xx-and-stm32f107xx-advanced-arm-based-32-bit-mcus-stmicroelectronics.pdf)
* [Blue Pill - Documentação da API do STM32F1](https://www.st.com/resource/en/user_manual/dm00154093-description-of-stm32f1-hal-and-lowlayer-drivers-stmicroelectronics.pdf)
* [Página embeddedexpert.io - Exemplos de códigos](https://embeddedexpert.io/)
* [Tutorial de instalação do ambiente de dupuração/programação - Prof. Guilherme L. Moritz](https://drive.google.com/file/d/1uLPW_LXY3d8g-7BL5YjpZ9rex4Q9JGck/view?usp=sharing)
* [Vídeo tutorial de instalação do ambiente de dupuração/programação - Prof. Guilherme L. Moritz](https://youtu.be/wEANQKCs-E4)

## 2.3 Placa BlackPill

* [Blackpill - Pinagem (Zephyr Project) e informações Gerais](https://docs.zephyrproject.org/latest/boards/arm/blackpill_f411ce/doc/index.html)
* [Blackpill - Circuito esquemático](https://stm32-base.org/assets/pdf/boards/original-schematic-STM32F411CEU6_WeAct_Black_Pill_V2.0.pdf)
* [Blackpill - Datasheet do STM32F411RE](https://www.st.com/resource/en/datasheet/stm32f411re.pdf)
* [Blackpill - Reference Manual do STM32F411RE](https://www.st.com/resource/en/reference_manual/dm00119316-stm32f411xc-e-advanced-arm-based-32-bit-mcus-stmicroelectronics.pdf)
* [Blackpill - Documentação da API do STM32F4](https://www.st.com/resource/en/user_manual/dm00105879-description-of-stm32f4-hal-and-ll-drivers-stmicroelectronics.pdf)

# 3. Site para download do software Eagle

* Link: https://www.autodesk.com/products/eagle/free-download

# 4. Site do projeto

O site do projeto foi desenvolvido pelo estudante *Cáled Tarique Pereira* do curso de Engenharia de Controle e Automação da UTFPR Campus Cornélio Procópio.
* Link: https://ele002.wordpress.com/   

# 5. Como citar este trabalho

ASSEF, Amauri Amorin; MORITZ, Guilherme Luiz; BANDEIRA JUNIOR, Delvanei Gomes; PERON, Guilherme de Santi; KASTER, Maurício dos Santos; OLIVEIRA, Murilo Paulo de; PEREIRA, Cáled Tarique. Projeto aberto da placa MICROTB_UTFPR (V1.0) para conexão com as plataformas de avaliação de microcontroladores baseados em ARM Tiva LaunchPad e Blue Pill. Curitiba: UTFPR, 2021. 

# 6. Informação de licença 

![Licença Logo](/Figuras/by-nc-sa.png)

Esta obra está licenciada com uma Licença Creative Commons BY-NC-SA 4.0. Esta licença permite que outros remixem, adaptem e criem a partir do trabalho para fins não comerciais, desde que atribuam o devido crédito e que licenciem as novas criações sob termos idênticos. Conteúdos elaborados por terceiros, citados e referenciados nesta obra não são cobertos pela licença. Para ver uma cópia da licença, visite http://creativecommons.org/licenses/by-nc-sa/4.0/
