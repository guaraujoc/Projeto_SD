# Projeto de Sistemas Digitais

## Integrantes

&nbsp;&nbsp;&nbsp;&nbsp;Universidade de São Paulo

&nbsp;&nbsp;&nbsp;&nbsp;SEL0628 - Sistemas Digitais

&nbsp;&nbsp;&nbsp;&nbsp;Aluno Gabriel Savassi Engler / 11844771

&nbsp;&nbsp;&nbsp;&nbsp;Aluno Gustavo Carvalho Araújo / 13735630

&nbsp;&nbsp;&nbsp;&nbsp;Aluno Gabriel João Marcelo Moreira Trovão Filho / 13676332

&nbsp;&nbsp;&nbsp;&nbsp;Aluno Oliver Kenzo Kobayashi / 13676930

&nbsp;&nbsp;&nbsp;&nbsp;Aluno Vítor Augusto Paiva de Brito / 13732303

&nbsp;&nbsp;&nbsp;&nbsp;Aluno Yazid Alamou Bouari / 13551034


## Primeira Parte

&nbsp;&nbsp;&nbsp;&nbsp; Nessa etapa, abordaremos a implementação de um decodifcador BCD para um display de 7 segmentos. O decodificador tem como função converter um npumero binário de 4 bits (BDC) em sinais de controle para os segmentos do display, permitindo a exibição do número correspondente.

&nbsp;&nbsp;&nbsp;&nbsp; A implementação desse decodificador é de extrema importância em sistemas digitais que necessitam exibir informações numéricas de forma visual, como em painéis de instrumentos, displays de relógios, calculadora e muitos outros dispositivos. Tal decodificador é uma parte fundamental desses sistemas, pois permite a representação dos números 0 a 9 em um display de segmentos.

&nbsp;&nbsp;&nbsp;&nbsp; Para a sua implementação, iremos apresentar 4 maneiras diferentes de descrição utilizando a linguagem de descrição de hardware (HDL) Verilog, são elas:

- Primitivas ou Rede de ligações (not, and, orr, xor, xnor, nan, nor);
- Declarações Concorrentes com Operadores Lógicos (~ & | ^ ~ ^);
- Declarações Concorrentes com Operador Ternário (?:);
- Declaração Procedural ou Comportamental (always if-else).


&nbsp;&nbsp;&nbsp;&nbsp; Cada uma das técnicas de descrição apresenta suas próprias características e vantagens, permitindo flexibilidade na implementação do circuito lógico.

## Segunda Parte

&nbsp;&nbsp;&nbsp;&nbsp; Nesta etapa, abordaremos a implementação de um contador binário parametrizável de 'width' bits. Esse tipo de contador é amplamente utilizado em sistemas digitais para realizar contagens incrementais de forma síncrona, sendo controlado por um sinal de clock.

&nbsp;&nbsp;&nbsp;&nbsp; Além da contagem binária, o contador contará com recursos adicionais para atender aos requisitos específicos do projeto. Em primeiro lugar, ele será projetado para contar até um valor máximo determinado pelo parâmetro 'max_value'. Quando a contagem atingir esse valor máximo, um sinal de saída denominado 'cnt_max' será ativado, indicando que o limite foi alcançado.

&nbsp;&nbsp;&nbsp;&nbsp; O contador também terá sinais de controle, como 'enb' (habilitação da contagem) e 'rst_s' (reset assíncrono), que permitirão controlar o início, parada e reinício da contagem, respectivamente. Esses sinais de controle fornecem flexibilidade ao contador, permitindo que ele seja adaptado às necessidades do projeto.

A&nbsp;&nbsp;&nbsp;&nbsp; Antes de implementar o contador, será necessário descrever um elemento fundamental chamado Flip-flop tipo D com reset e clock enable. Esse Flip-flop é responsável por armazenar e atualizar o valor do contador a cada pulso de clock, além de fornecer recursos de reset e habilitação da contagem.

&nbsp;&nbsp;&nbsp;&nbsp; Uma vez compreendido o funcionamento do Flip-flop tipo D com reset e clock enable, será possível prosseguir com a implementação do contador. Para isso, serão exploradas diferentes técnicas de descrição de hardware (HDL) Verilog, como a utilização de Flip-flops com generate e Rede de Ligações, bem como a descrição procedural ou comportamental utilizando a estrutura always if-else.

- Assíncrono, utilização de Flip-flops
- Síncrono, com generate e Rede de Ligações;
- Com incremento, utilizando Declaração Procedural ou Comportamental (always if-else).

&nbsp;&nbsp;&nbsp;&nbsp; Essas implementações do contador binário parametrizável nos permitirão criar circuitos flexíveis, capazes de contar de forma síncrona e eficiente, adaptando-se aos requisitos específicos de contagem de cada projeto. A utilização de contadores é essencial em sistemas digitais para realizar tarefas de contagem, controle e sincronização, sendo aplicados em uma ampla variedade de dispositivos e aplicações, como contadores de tempo, contadores de eventos, sequenciadores e muito mais.

## Terceira Parte

&nbsp;&nbsp;&nbsp;&nbsp; Nesta etapa, vamos apresentar a implementação de um contador digital BCD (Binary Coded Decimal) que varia de 000 a 999. Esse tipo de contador é amplamente utilizado para exibir valores decimais em displays de sete segmentos, sendo essencial em aplicações que envolvem exibição de números.

&nbsp;&nbsp;&nbsp;&nbsp; O contador será implementado em Verilog, utilizando os componentes desenvolvidos anteriormente, como o Flip-flop tipo D com reset e clock enable, além do decodificador BCD para display de sete segmentos. Esses componentes serão combinados de forma a criar um circuito que realize a contagem de 000 a 999, representando os valores em formato BCD.

&nbsp;&nbsp;&nbsp;&nbsp; A implementação do contador digital BCD será uma aplicação prática e importante dos conceitos estudados em sistemas digitais, demonstrando a capacidade de criar circuitos complexos utilizando os componentes básicos desenvolvidos anteriormente. Essa implementação é fundamental em projetos que envolvem exibição de números, como displays de relógios, medidores, sistemas de automação e muitas outras aplicações em que a contagem de valores decimais é necessária.

## Quarta Parte

&nbsp;&nbsp;&nbsp;&nbsp; Nesta última etapa, iremos abordar a implementação de uma máquina de estados para controlar um conversor analógico para digital (ADC) do tipo rampa dupla (dual slope). O ADC de rampa dupla é uma técnica amplamente utilizada na conversão de sinais analógicos em sinais digitais, permitindo a medição precisa de valores analógicos.

&nbsp;&nbsp;&nbsp;&nbsp; Esse sistema tem aplicações em áreas como instrumentação e controle, conversores de tensão, sistemas de áudio e vídeo, telecomunicações e monitoramento biomédico. Ele desempenha um papel fundamental na conversão precisa de sinais analógicos em formato digital, permitindo o processamento, controle e transmissão de dados de forma confiável e eficiente. Dessa forma, precisão e confiabilidade são essenciais para garantir um funcionamento adequado dos sistemas e obter resultados precisos em diversas áreas de aplicação.
