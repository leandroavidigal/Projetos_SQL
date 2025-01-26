## Projetos SQL: Análises de Dados Reais com SQL

Este repositório contém uma série de projetos focados na utilização prática do SQL (Structured Query Language) para análise de dados reais, orientada para aplicações empresariais. Aqui, você encontrará exemplos detalhados de como o SQL pode ser utilizado para tomada de decisões estratégicas e como essa linguagem é uma ferramenta essencial para Cientistas de Dados e Engenheiros de Dados.

### **Visão Geral**

O objetivo deste repositório é demonstrar o uso de SQL para resolver problemas do mundo real, abrangendo desde a manipulação básica de dados até análises avançadas e técnicas de otimização em ambientes empresariais. Cada projeto é projetado para ser aplicado diretamente em cenários práticos, gerando insights valiosos a partir de dados estruturados e auxiliando na tomada de decisões.

### **Projetos Incluídos**

### 1. **Introdução ao SQL com Análises de Dados Reais**

Neste projeto, exploramos as funcionalidades básicas de SQL para:
- Análise de perfis de clientes e limites de crédito;
- Uso de consultas SQL para analisar variáveis como **idade**, **escolaridade** e **número de dependentes**;
- Criação de visualizações a partir de dados para orientar decisões de negócios.

[Veja o artigo completo sobre este projeto no Medium](https://medium.com/@leandro.vidigal/introdu%C3%A7%C3%A3o-ao-sql-com-an%C3%A1lises-de-dados-reais-d9ec1d902053)

---

### 2. **Integração com AWS S3 e Athena**

Este projeto aborda a integração prática de SQL com serviços da AWS, incluindo o armazenamento no S3 e consultas no Athena.

**Destaques:**
- Configuração de buckets no AWS S3 para armazenamento de dados e resultados.
- Criação de tabelas externas no Athena para acesso eficiente aos dados armazenados no S3.
- Consultas avançadas no Athena para análise de dados como média de idade por sexo, filtros e ordenação.
- Aplicação prática de SQL em um ambiente escalável, demonstrando como gerenciar grandes volumes de dados de forma eficiente.

---

### 3. **Análise e Manipulação de Dados com SQL**

Neste projeto, aprofundamos a manipulação de dados com SQL, abordando:
- **Seleção de dados** com comandos como `SELECT` e aplicação de alias (`AS`) para tornar resultados mais compreensíveis;
- **Ordenação** de resultados utilizando `ORDER BY` para organizar dados de maneira eficiente;
- **Limitação de resultados** com `LIMIT`, exibindo apenas os registros mais relevantes;
- Práticas no AWS Athena para consultas otimizadas em dados armazenados no S3.

---

### 4. **Filtros e Seleção Condicional em SQL**

Este projeto explora o uso de filtros avançados e seleção condicional, abordando:
- **Filtros com AND, OR, IN e BETWEEN** para refinar consultas de acordo com várias condições;
- **Padrões com LIKE e wildcards** para localizar valores baseados em correspondências parciais;
- **Seleção condicional com CASE**, criando categorias dinâmicas para os dados com base em condições específicas;
- Práticas aplicadas no AWS Athena com consulta de dados em S3, demonstrando o poder do SQL em manipular e categorizar dados complexos.

---

### 5. **Análise Avançada de Dados de Saúde com SQL**

Neste projeto, exploramos funções de agregação e cláusulas avançadas, abordando:
- **Funções de Agregação** como `SUM`, `AVG`, `MIN`, `MAX` e `COUNT` para sumarizar dados;
- **Cláusula HAVING**, utilizada para filtrar grupos criados pelo comando `GROUP BY`;
- Análises aplicadas em um conjunto de dados relacionado a ataques cardíacos, demonstrando como extrair insights importantes sobre saúde;
- Práticas realizadas no AWS Athena com dados armazenados no S3, utilizando queries estruturadas para manipular e interpretar dados complexos.

---

### 6. **Combinações e Junções de Tabelas em SQL**

Neste projeto, exploramos diferentes técnicas de combinação e junção de tabelas, abordando:
- **Operações UNION e UNION ALL**, utilizadas para combinar resultados de consultas eliminando ou preservando duplicatas;
- **Junções INNER JOIN e CROSS JOIN**, aplicadas para identificar relações entre tabelas e realizar cruzamentos completos de dados;
- **Junções LEFT JOIN e RIGHT JOIN**, que garantem a visualização de todos os registros de uma tabela principal e apenas os correspondentes da outra tabela;
- Práticas aplicadas no AWS Athena para consolidar informações de múltiplas tabelas, demonstrando a importância das relações em bases de dados complexas.

---

### 7. **SQL Avançado: Subqueries, Particionamento e Visões**

Neste projeto, exploramos técnicas avançadas de consulta e organização de dados, abordando:
- **Subqueries**: consultas aninhadas para condições dinâmicas e seleções condicionais;
- **Particionamento**: estruturação de dados em pastas hierárquicas no AWS S3 para otimização de consultas no Athena;
- **Visões**: criação de tabelas virtuais para simplificar consultas complexas e melhorar a reutilização de código SQL;
- Práticas no AWS Athena demonstrando como essas técnicas aumentam a performance e reduzem custos em ambientes de dados complexos.

---

### 8. **Análise Avançada de Clientes Bancários**

Neste projeto, realizamos uma análise exploratória detalhada de um conjunto de dados financeiros para entender o comportamento dos clientes bancários. As principais análises incluem:
- **Distribuição demográfica**: faixas salariais, distribuição por gênero e características de idade;
- **Comportamento financeiro**: valores mínimos e máximos de transações, limites de crédito e padrões de gasto;
- **Impacto do salário no limite de crédito**: análise das correlações entre renda e comportamento de consumo;
- Insights direcionados para decisões estratégicas no setor bancário.
- **Ferramentas utilizadas**: AWS Athena e SQL.

**Destaques:**
- Aplicação prática de funções de agregação, condições e ordenação para análise financeira detalhada.
- Segmentação baseada em comportamento financeiro e perfil demográfico para estratégias de negócios.
