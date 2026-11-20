# Feature Engineering — Engenharia de Atributos

## Sobre o projeto

Projeto desenvolvido durante a formação em Análise de Dados da Programaria, com foco na aplicação de técnicas de Feature Engineering para transformar e enriquecer uma base de dados com informações profissionais e demográficas.

O trabalho utiliza Python para criar novas variáveis, categorizar informações, integrar diferentes bases de dados e explorar relações entre atributos.

## Fonte dos dados

Os dados utilizados neste projeto provêm do Instituto Brasileiro de Geografia e Estatística (IBGE), referentes ao período de 2015 a 2021, disponibilizados como material didático no curso de Análise de Dados da Programaria.

## Objetivos

- Transformar variáveis existentes em novos atributos.
- Criar categorias a partir de informações demográficas.
- Integrar diferentes bases de dados utilizando um identificador em comum.
- Identificar características relacionadas à busca por novas oportunidades profissionais.
- Explorar correlações entre variáveis numéricas e categóricas.

## Ferramentas utilizadas

- Python
- Pandas
- NumPy
- SciPy
- Google Colab

## Etapas desenvolvidas

1. Importação e exploração das bases de dados.
2. Criação de uma nova categoria profissional para identificar pessoas gestoras.
3. Transformação de variáveis categóricas utilizando One-Hot Encoding (`get_dummies`).
4. Criação de uma variável para classificação de gerações a partir da idade.
5. Integração de duas bases de dados utilizando `merge` e o identificador `ID`.
6. Criação de indicadores booleanos relacionados à busca por emprego e abertura a oportunidades.
7. Análise de correlação entre idade e salário.
8. Exploração da associação entre variáveis categóricas utilizando o coeficiente V de Cramér.

## Aprendizados

O projeto permitiu praticar técnicas de transformação e criação de
