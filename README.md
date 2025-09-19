#PBL da Primeira Unidade de Circuitos Digitais
# Conversor Binário para Display de Sete Segmentos

## 📖 Descrição do Projeto
Este projeto apresenta o desenvolvimento de um **protótipo funcional** para conversão de entradas binárias em **saídas visuais codificadas**. O sistema utiliza **displays de sete segmentos** para exibir:

- O caractere ASCII correspondente.
- Os dois dígitos hexadecimais (mais significativo e menos significativo).
- O valor binário equivalente, utilizando LEDs.

Além disso, o circuito conta com **sinalização de erro** para entradas inválidas, garantindo maior robustez e confiabilidade.

## 🛠️ Implementação
O projeto foi implementado em **Verilog** utilizando o software **Quartus II** e a placa **DE10-LITE (10M50DAF484C7G)** da Terasic, equipada com um FPGA da família **MAX 10**.

## 🔧 Funcionalidades
- Conversão de entradas binárias em:
  - Caractere ASCII
  - Representação hexadecimal
  - Representação binária via LEDs
- Indicação de erros para entradas inválidas
- Suporte para até **20 caracteres codificados**
- Testes realizados com os caracteres: `H`, `o`, `L`, `l`, `E`

## 📊 Resultados
O relatório inclui:
- Etapas de desenvolvimento do circuito
- Critérios de seleção dos caracteres
- Resultados de simulação
- Validação prática do sistema

## 📌 Objetivo
Fornecer uma **interface eficiente e didática** para a representação de dados binários, hexadecimais e alfanuméricos, facilitando a comunicação entre sistemas digitais e usuários.
