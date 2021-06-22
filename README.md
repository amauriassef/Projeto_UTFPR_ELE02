# Projeto ELE02 

## Universidade Tecnológica Federal do Paraná (UTFPR)

Departamento Acadêmico de Eletrotécnica (DAELT) - Campus Curitiba
Departamento Acadêmico de Eletrônica (DAELN) - Campus Curitiba
Departamento Acadêmico de Eletrônica (DALEN) - Campus Curitiba

## Título: 

Desenvolvimento de um kit microcontrolado de baixo custo para apoio ao ensino remoto - Projeto ELE02 
 
## Descrição: 

Projeto do circuito esquemático e circuito impresso da placa MICROTB_UTFPR utilizando o software [Eagle 9.6.2](https://www.autodesk.com/products/eagle/). A placa MICROTB_UTFPR permite conexão com as placas TIVA™ C Series TM4C123G LaunchPad e Blue Pill para aplicações de automação envolvendo de Sistemas Microcntrolados e IoT.

Projeto aprovado no [Edital 37/2020 PROGRAD – UTFPR – Área temática de Sistemas Microcontrolados](https://sei.utfpr.edu.br/sei/publicacoes/controlador_publicacoes.php?acao=publicacao_visualizar&id_documento=2039976&id_orgao_publicacao=0)

## Equipe: 
 
* Amauri Amorin Assef – Coordenador – http://lattes.cnpq.br/0720172921923496
* Guilherme Luiz Moritz – Colaborador – http://lattes.cnpq.br/0736175449254807
* Delvanei Gomes Bandeira Junior – Colaborador – http://lattes.cnpq.br/2233204054325472
* Guilherme de Santi Peron – Colaborador –  http://lattes.cnpq.br/7845448730478685
* Maurício dos Santos Kaster – Colaborador – http://lattes.cnpq.br/5494434934031784
* Murilo Paulo de Oliveira – Bolsista – http://lattes.cnpq.br/1578999659029568
* Cáled Tarique Pereira – Voluntário – http://lattes.cnpq.br/5596843081337675
 
## Documentação:

* [**BOM_MICROTB**](/BOM_MICROTB) - Lista de material (bill of material) da placa MICRO_TB_UTFPR.
* [**CAD_EAGLE_9_6_2_MICROTB**](/CAD_EAGLE_9_6_2_MICROTB) - Projeto do circuito esquemático e layout da placa MICRO_TB_UTFPR.
* [**LIB_MICROTB**](/LIB_MICROTB) - Biblioteca com os componentes do circuito esquemático e placa MICRO_TB_UTFPR.
* [**PDF_PCB_MICROTB**](/PDF_PCB_MICROTB) - Arquivos em formato PDF para visualização do circuito esquemático e projeto da placa.

Obs: após abrir a PCB no Eagle clicar em Ratsnest para mostrar os planos de GND dos layers *top* e *bottom*.

## Versão do projeto

MICROTB_UTFPR V1.0 - Versão inicial com as seguintes características:

* Permite conexão com as placas TIVA™ C Series TM4C123G LaunchPad e Blue Pill
* 2 Displays de 7 segmentos do tipo catodo comum
* 8 LEDs
* Sensor de temperatura LM35
* Driver L293D para motor de passo e CC
* Conector para placa ESP8266
* Conector para placa Bluetooth HC-05/06
* Conector para servomotor
* Conector para sensor ultrassônico HC-04
* Conector para sensor de sensor de pressão BMP280
* Display LCD 16x2
* Potenciômetro para leitura analógica
* Alimentação pela USB ou fonte externa de 9 V

## Histórico de versão 

V_1.0 - Versão inicial da placa MICROTB_UTFPR 

## Informação de licença 

Esse produto é *open source*!

## Links com informações sobre a placa TIVA™ C Series TM4C123G LaunchPad

* [Tiva™ C Series TM4C123G LaunchPad Evaluation Board User’s Guide](https://www.ti.com/lit/ug/spmu296/spmu296.pdf)
* [Tiva™ TM4C123GH6PM Microcontroller Datasheet](https://www.ti.com/lit/ds/spms376e/spms376e.pdf)
* [Mini Curso - Getting Started with the TIVA™ C Series TM4C123G LaunchPad](http://software-dl.ti.com/trainingTTO/trainingTTO_public_sw/GSW-TM4C123G-LaunchPad/TM4C123G_LaunchPad_Workshop_Workbook.pdf)
* [Site ARM® Cortex®-M4F Based MCU TM4C123G LaunchPad™ Evaluation Kit](https://www.ti.com/tool/EK-TM4C123GXL)
* [TivaWare™ Peripheral Driver Library User's Guide](https://www.ti.com/lit/ug/spmu298d/spmu298d.pdf)
* [Drivers para o TM4C123 - TivaWare for C Series Software (Complete)](https://www.ti.com/tool/download/SW-TM4C)
* [e-Store Texas Instruments para o Launchpad](https://www.ti.com/store/ti/en/p/product/?p=EK-TM4C123GXL)

## Links com informações sobre as placas BluePill e BlackPill

* [ST Flasher](https://github.com/stlink-org/stlink/releases)
* [Bluepill - Informações Gerais](https://stm32-base.org/boards/STM32F103C8T6-Blue-Pill)
* [Bluepill - Esquemático (easyEDA)](https://easyeda.com/r3bers/STM32F103C8T6-Test-Board)
* [Bluepill - Datasheet do STM32F103C8](https://www.st.com/resource/en/datasheet/stm32f103c8.pdf)
* [Bluepill - Reference Manual do STM32F103C8](https://www.st.com/resource/en/reference_manual/cd00171190-stm32f101xx-stm32f102xx-stm32f103xx-stm32f105xx-and-stm32f107xx-advanced-arm-based-32-bit-mcus-stmicroelectronics.pdf)
* [Bluepill - Documentação da API do STM32F1](https://www.st.com/resource/en/user_manual/dm00154093-description-of-stm32f1-hal-and-lowlayer-drivers-stmicroelectronics.pdf)

* [Blackpill - Pinagem (Zephyr Project) e informações Gerais](https://docs.zephyrproject.org/latest/boards/arm/blackpill_f411ce/doc/index.html)
* [Blackpill - Esquemático](https://stm32-base.org/assets/pdf/boards/original-schematic-STM32F411CEU6_WeAct_Black_Pill_V2.0.pdf)
* [Blackpill - Datasheet do STM32F411RE](https://www.st.com/resource/en/datasheet/stm32f411re.pdf)
* [Blackpill - Reference Manual do STM32F411RE](https://www.st.com/resource/en/reference_manual/dm00119316-stm32f411xc-e-advanced-arm-based-32-bit-mcus-stmicroelectronics.pdf)
* [Blackpill - Documentação da API do STM32F4](https://www.st.com/resource/en/user_manual/dm00105879-description-of-stm32f4-hal-and-ll-drivers-stmicroelectronics.pdf)
