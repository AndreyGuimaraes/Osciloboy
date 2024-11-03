# Osciloboy

> Este projeto será feito como Trabalho de Conclusão de Curso para o curso de Engenharia Elétrica da Universidade Tencológica Federal do Paraná - campus Curitiba. Sua previsão de conclusão é para o mês de Dezembro de 2023.

## Descrição
Este projeto consiste em um instrumento de medição de tensão e corrente elétricas de três canais, que será montado em bancadas pré-fabricadas e adaptado para o uso nos laboratórios das disciplinas de Circuitos A e B e Eletricidade e Magnetismo. Possuirá conexão com um smartphone ou computador, exibirá as formas de onda obtidas através de conexão sem fio , e contará com proteção contra curto-circuito e sobretensão.

## Motivação
A Universidade Tecnológica Federal do Paraná - campus Curitiba, possui dois laboratórios de ensino para as disciplinas de Eletricidade e Magnetismo, Circuitos A e B, ofertadas por diversos cursos da universidade. Os laboratórios são salas com bancadas de testes para circuitos eletrônicos que possuem fontes de tensão e corrente, bem como módulos de medidores para diversos fins. Esses medidores, porém, são completamente analógicos, possuem fundo de escala que não condizem necessariamente com os testes que precisam ser realizados durante as aulas e, muitas vezes, não estão em condições adequadas de funcionamento. Isso se dá em grande parte por sua complexidade de reparos: tanto por precisarem de peças antigas para reposição, quanto por possuírem diversas peças mecânicas em seu interior que dificultam o processo de reparação, necessitando de tempo e testes, bem como calibração posterior; além de não possuírem sistemas de proteção adequados para o uso em sala de aula – local em que o aparelho sofre desgaste por erros comuns da prática de discentes. Além dos problemas de reparos destes equipamentos, há também a questão de custos de aquisição de módulos novos que se adequem às bancadas utilizadas nos laboratórios e ao tipo de uso. Há uma grande limitação de verbas para esse processodado os valores de medidores encontrados no mercado e disponibilidade de recursos da universidade.

## Ferramentas Utilizadas

### Modelagem 3D
- SolidWorks student version
- Freecad (caso não seja possível)

### Design PCB
- KICAD

### Programação

#### Firmware
- Arduino IDE 2.0

#### WebApp (caso necessário)
- Javascript ou
- Typescript

### Hardware base
- Esp32 (standalone ou devkit)
- *Switch Analógico* (colocar nome certo)
- *ADC diferencial* (colocar nome certo)

----

## Resumo do Projeto (TLDR)
- Osciloscópio didático montado em bancada;
- 3 canais para leitura de tensão e 3 para corrente;
- Proteção contra tensão e corrente;
- Conexão com smartphone ou computador por Wi-Fi;
- Projeto da PCB, case e código;
- Baixo custo, facilidade de reparo e obtenção de peças no Brasil (Curitiba).