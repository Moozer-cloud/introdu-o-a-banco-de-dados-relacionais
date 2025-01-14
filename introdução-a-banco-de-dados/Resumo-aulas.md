Resumos das Aulas

Introdução à Banco de Dados
1. O que são dados?

Dados != de Informação
Qual o poder dos dados?
Ter as informações mais assertivas.

Segurança e persistência dos dados


2. O que são Banco de Dados?
Dados são fatos = Diamante bruto
Database = conjunto de dados que transmitem informação, um sistema próprio para isso.
Podemos considerar que uma coleção de palavras, que dentre elas há relacionamentos entre dados, constituindo então um banco de dados.

Contexto - Representação do mundo real
Coerência
Propósito
Na maioria das situações o acesso ao banco de dados é por API.


3. Sistema de Gerenciamento de BDs?
Definição: Tipo de dados / Estrutura / Diretrizes

Construção: Inserção de Dados

Manipulação: Recuperação / Relatórios

Compartilhamento: Simultaneidade / Acesso


4. Histórico de SGBDs
Modelo relacional de BDs 1960/1970 IBM
1960 - Qual foi a motivação? Diminuir custos com pessoal!
Modelo baseado em sistemas de arquivos
Modelo em rede / Modelo hierárquico / Modelo Relacional (1970)
1970 - Cálculo e Álgebra Relacional (Criador: Ted Codd)

1970 SQL / 1976 DB Honeywell Information Systems Inc / 1980 Oracle 2 & IBM SQL/DS/ 1983 Oracle 3


5. Modelo de banco de dados relacionais
Características: Álgebra Relacional, Relações, TAD para armazenamento e Transparência

6. SGBDs utilizados pelo mercado
1 Oracle - Foi o primeiro a ser criado
2 MySQL - Solução de código aberto / Aplicações web
3 SQL Server - Aplicações críticas / Integração com BI e Excel
4 PostgreSQL - Normalmente a escolha de programadores de Python / Open Source
5 mongoDB - NoSQL / Armazena dados em blocos
6 Redis - NoSQL / Achar valor
7 ElasticSearch - NoSQL / Mecanismo de busca / Análise de Logs / Escalável
9 Acess - NoSQL / Leve
11 Cassandra - NoSQL / Open Source / Ambiente de dados de larga escala
12 MariaDB - Mesma estrutura do MySQL 


7. Era dos Dados e Futuro da Modelagem
Contexto majoritário: Modelo Relacional 95%
Pesquisa Científica: Grande volume de dados, Heterogeneidade (Diversas fontes diferentes/ Estruturas diferentes), Computação paralela e distribuída (Maior complexidade)
4º Paradigma: Científico - 1º Experimental / 2º Teórica da ciência / 3º Computacional, Simulações / 4º Ciência baseada em dados (IA...) Velocidade/Variedade/Volume
Requisitos 4º Paradigma: Composição - Execução - Análise - Abstração - Reprodutividade - Reutilização - Escalabilidade
Experimentos realizados em larga escala -> Paralelismo (Múltiplos processadores operando concorrentemente) - Big Data (Processamento paralelo de dados  persistentes e particionados) - Cloud (Recursos de terceiros - Soluções de tecnologia como serviço)

8. HPC e Big Data: 
HPC Apenas processa

9. Novo cenário e novas tecnologias - E agora?
Data Carrier: Mercado de Data: Engenheiro de dados (Desenho/Construção) / Analista de dados (Criação de dashboards / Apresentação visual dos dados) / Cientista de dados (Modelagem e Reconhecimento de padrões/Predição)

Decisões - Data-driven: Analise - Entenda - Decide

Modelos NoSQL:
- Documentos [mongo DB] -> (Baixa curva de aprendizado - Baseado em JSON, Escalabilidade horizontal - Multiplataforma - Transações ACID - Consultas: Suporte javascript)
- Wide-Columns [cassandra] -> (Origem: Facebook - Open-source: 2008 - Performático - Descentralizado - Consultas: CQL)
- Key-Value [redis] -> (2009 Escrito em C - Compatível com outras linguagens - Performático - Suporta: Strings, list, maps, sets, JSON, Graphs...)
- Grafos [neo4j] -> (2007 escrito em java - TAD: grafos - Cypher: query para grafos - Data science - Compatível: Python, NodeJS, GO, .NET e Java...)
- Orientação à Objetos [db4objects by versant] -> (2008 Open-source - Escrito em .NET e Java - Cross-plataform)

NoSQL = Not Only SQL

SGBDs na Cloud: 
AmazonRDS, Azure BD, Amazon Aurora, DynamoDB

Mundo Real:


