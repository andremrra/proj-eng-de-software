# ANÁLISE DE REGISTROS DE SAÚDE DE POSTO MÉDICO


1. Contexto e Justificativa

O projeto tem como base o Objetivo de Desenvolvimento Sustentável (ODS) nº 3 da Agenda 2030 da ONU: Saúde e Bem-Estar. Esse objetivo visa assegurar uma vida saudável e promover o bem-estar para todos, em todas as idades. No Brasil, um dos desafios enfrentados está relacionado à falta de acesso equitativo a serviços de saúde, à subnotificação de doenças e à carência de ferramentas que auxiliem na análise de dados sobre a saúde pública.

Diante desse cenário, o grupo propõe o desenvolvimento de uma plataforma de análise e visualização de dados de saúde pública, utilizando dados disponibilizados pelo IBGE e DATASUS, com foco em indicadores como vacinação, incidência de doenças e acesso a serviços médicos. Essa solução permitirá uma análise mais profunda da distribuição dos recursos e das desigualdades regionais no país.

2. Definição do Problema

Apesar de existirem diversas bases de dados públicas, o acesso e a interpretação das informações de saúde ainda são limitados. Profissionais e gestores muitas vezes encontram dificuldade em compreender padrões e tendências de saúde pública devido à fragmentação das informações e à falta de ferramentas acessíveis de visualização e análise.

Problema identificado:

A dificuldade de acesso, integração e interpretação dos dados públicos de saúde, que impede a elaboração de políticas mais eficazes e o acompanhamento adequado dos indicadores de saúde.

3. Proposta de Solução

Desenvolver uma plataforma interativa de Business Intelligence (BI) que reúna, trate e visualize os principais indicadores de saúde pública brasileiros. O sistema permitirá que usuários analisem a distribuição de vacinas, incidência de doenças, número de leitos hospitalares, entre outros indicadores, por estado e município.

Recursos previstos:

Extração automática de dados do IBGE e DATASUS.

Criação de um pipeline ETL para limpeza e integração das informações.

Visualizações interativas em dashboards (Power BI ou Looker Studio).

Exportação de relatórios personalizados.

4. Objetivos do Projeto

Objetivo Geral: Desenvolver uma solução de análise de dados que auxilie na compreensão e monitoramento dos indicadores de saúde pública no Brasil.

Objetivos Específicos:

Integrar bases públicas de dados sobre saúde (IBGE, DATASUS, PNI).

Estruturar um processo de ETL automatizado.

Criar dashboards que evidenciem desigualdades regionais e tendências temporais.

Gerar relatórios analíticos para apoio à tomada de decisão.

5. Requisitos do Sistema

Requisitos Funcionais:

O sistema deve permitir a importação e atualização periódica dos dados públicos de saúde.

O sistema deve processar e armazenar os dados em um banco relacional.

O sistema deve disponibilizar visualizações interativas (gráficos, mapas e tabelas dinâmicas).

O sistema deve permitir o download de relatórios consolidados.

Requisitos Não Funcionais:

A plataforma deve ter boa usabilidade e desempenho.

O sistema deve utilizar tecnologias abertas e gratuitas.

O banco de dados deve garantir integridade e consistência das informações.

O dashboard deve ser acessível por diferentes dispositivos.

