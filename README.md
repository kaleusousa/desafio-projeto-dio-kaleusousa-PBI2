# desafio-projeto-dio-kaleusousa-PBI2

Objetivo
Executar uma das etapas do Curso Santander Bootcamp 2023 - Ciência de Dados com Python com o intuito de desenvolver, de modo prático, os temas abordados no conjunto "Visualização e Análise de Dados com Power BI" - Desafio de Projeto: Processando e Transformando Dados com Power BI.

Procedimentos realizados
Criação do banco de dados de MySQL no cloud Azure;
Integração do banco de dados com o Power BI;
Análise dos cabeçalhos;
Valor de salário ajustado para tipo moeda;
Foi identificado apenas 
Foi duplicado a consulta "azure_company employee" e renomeada para "Gerente" onde foi filtrado os itens nulos na coluna "Super_snn" e identificado o gerente da commpanhia;
Na consulta "azure_company departament", coluna "azure_company.employee(Mgr_ssn)" foi selecionado os campos "Fname" e "Lname" para apresenta o primeiro e último nome dos gerentes responsáveis pelos departamentos com base na coluna "Mgr_ssn" da tabela - Não foram identificados departamentos sem geerentes atrelados;
Na consulta "azure_company project", coluna "azure_company.works_on" foi selecionado o campo "Hours", após isso os campos foram agrupados para apresentar a soma do campo "Hours" demonstrando o total de cada projeto;
Na consulta "azure_company employee" a coluna "Address" foi separada em 3 colunas com base no hífen separando o número, endereço e estado;
Foi criado uma nova consulta mesclando as consultas "azure_company employee - campo Dno" e "azure_company departament - campo Dnumber" para vincular os empregados aos respectivos departamentos;
Para adição da informação do nome do gerente foi realizado a mescla da consulta "azure_company employee" na consulta onde as informações estão sendo tratadas;
Foi mesclado os campos nos nomes dos empregados e gerentes com o espaço como divisor, sendo que no caso do gerente geral foi deixado o campo como nulo;
Eliminado as colunas desnecessárias.
