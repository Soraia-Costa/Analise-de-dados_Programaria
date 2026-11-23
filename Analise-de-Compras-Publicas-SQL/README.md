# 02 – SQL | Investigação de Compras Públicas Federais

## Sobre o projeto

Atividade prática de análise de dados utilizando SQL para investigar informações sobre Compras Públicas Federais, com base em registros de licitações de dezembro de 2018.

O desafio consistiu em identificar como os valores licitados estão distribuídos e quais estruturas públicas aparecem nos registros, utilizando consultas SQL para explorar, organizar e relacionar informações.

## Objetivo

- Explorar uma base de dados de licitações públicas.
- Identificar a distribuição dos registros por estado (UF).
- Analisar valores e modalidades de licitação.
- Investigar unidades gestoras e estruturas administrativas.
- Relacionar informações de diferentes tabelas utilizando JOIN.
- Interpretar os resultados para responder às perguntas da investigação.

## Tecnologias e ferramentas

- **SQL:** consultas, filtros, agrupamentos e relacionamentos.
- **SQLite:** banco de dados utilizado na atividade.
- **Python:** conexão e manipulação do banco de dados.
- **Google Colab:** ambiente de desenvolvimento.
- **Pandas:** organização e análise dos resultados.

## Base de dados

Banco de dados `compras_publicas_2018.sqlite`, contendo 15.336 registros de licitações.

Principais tabelas utilizadas:

- `licitacoes`
- `modalidades`
- `unidades_gestoras`
- `orgaos`
- `orgaos_superiores`

## Desenvolvimento da atividade

### Etapa 1 – Exploração dos dados

Nesta etapa, foram realizadas consultas para conhecer a estrutura do banco e investigar os registros de licitações.

Principais comandos SQL utilizados:

- SELECT – seleção de informações.
- WHERE – filtragem de registros.
- ORDER BY – ordenação dos resultados.
- COUNT – contagem de registros.
- SUM – soma de valores.
- GROUP BY – agrupamento de informações.

Foram realizadas análises de distribuição das licitações por UF, valores licitados e modalidades de contratação.

### Etapa 2 – Relacionamento e investigação

Na segunda etapa, o objetivo foi aprofundar a investigação por meio do relacionamento entre tabelas.

Foram utilizados comandos JOIN para conectar informações de licitações, unidades gestoras, órgãos e órgãos superiores.

Também foi investigada a concentração de registros por unidade gestora, utilizando agrupamento e ordenação.

Exemplo de consulta utilizada:

```sql
SELECT
    codigo_ug,
    COUNT(*) AS total_licitacoes
FROM licitacoes
GROUP BY codigo_ug
ORDER BY total_licitacoes DESC
LIMIT 5;
```

A consulta permite identificar as cinco unidades gestoras com maior quantidade de registros de licitações.

## Principais aprendizados

Durante a atividade, desenvolvi conhecimentos práticos em:

- Consulta e exploração de bancos de dados relacionais.
- Utilização de funções de agregação.
- Agrupamento e ordenação de dados.
- Relacionamento entre tabelas com JOIN.
- Investigação de padrões e concentração de registros.
- Interpretação de resultados para responder a perguntas de negócio.
- Integração entre SQL, Python e Pandas.

## Conclusão

A atividade demonstrou como o SQL pode ser utilizado para investigar grandes conjuntos de dados, identificar padrões e relacionar informações de diferentes estruturas administrativas.

Além da construção das consultas, o exercício reforçou a importância de interpretar os resultados com cuidado, diferenciando a quantidade de licitações dos valores registrados e evitando tratar valores licitados como valores efetivamente pagos.

---

**Projeto desenvolvido como atividade prática de estudos em Análise de Dados e SQL.**
