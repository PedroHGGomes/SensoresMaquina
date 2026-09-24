**Sistema de Manutenção Preditiva**

Sistema desenvolvido em C#, .NET e ML.NET para monitoramento de uma máquina industrial através de sensores, com o objetivo de identificar condições anormais de funcionamento e auxiliar na prevenção de falhas.

**Sobre o projeto**

Este projeto surgiu a partir de uma situação real em ambiente industrial, onde uma máquina apresentava paradas inesperadas durante períodos importantes de produção.

A proposta foi desenvolver um sistema capaz de monitorar diferentes parâmetros da máquina através de sensores e utilizar os dados coletados para identificar possíveis condições de falha.

Entre os principais parâmetros monitorados estão:

Temperatura;

Fluxo de ar;

Consumo e comportamento elétrico;

Estado de funcionamento da máquina.

A partir desses dados, o sistema consegue analisar as condições de operação e identificar situações que possam indicar necessidade de manutenção.

**Objetivo**

O principal objetivo do projeto é reduzir a ocorrência de paradas inesperadas da máquina, utilizando dados dos sensores para apoiar uma estratégia de manutenção preventiva e preditiva.

Problemas desse tipo podem gerar:

Atrasos na produção;

Perda de produtividade;

Custos adicionais de manutenção;

Danos aos equipamentos;

Necessidade de manutenção emergencial.

Em vez de realizar uma intervenção apenas depois que uma falha ocorre, o sistema busca identificar sinais anormais antecipadamente.

**Funcionamento**

O sistema recebe informações provenientes dos sensores instalados na máquina.

Esses dados são processados pela aplicação desenvolvida em C# e .NET, que avalia as condições atuais de funcionamento.

O fluxo geral da aplicação pode ser representado da seguinte maneira:

Máquina
   ↓
Sensores
   ↓
Coleta de Dados
   ↓
Aplicação C# / .NET
   ↓
Processamento dos Dados
   ↓
Análise / ML.NET
   ↓
Avaliação do Estado da Máquina
   ↓
Alerta de Manutenção

Caso seja detectado algum comportamento considerado anormal, o sistema pode gerar um alerta indicando que a máquina precisa ser verificada.

**Machine Learning**

Para complementar o monitoramento dos sensores, o projeto utiliza ML.NET, biblioteca de Machine Learning da Microsoft integrada ao ecossistema .NET.

O objetivo do Machine Learning é utilizar dados históricos da máquina para identificar relações entre os valores registrados pelos sensores e possíveis condições de falha.
