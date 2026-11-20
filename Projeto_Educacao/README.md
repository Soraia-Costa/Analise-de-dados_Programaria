# Análise de Dados: Educação — Participação e Permanência Estudantil

## Sobre o projeto

Este projeto tem como objetivo explorar dados educacionais para compreender padrões relacionados ao desempenho acadêmico, à permanência e à evasão de estudantes.

A análise utiliza dados de estudantes de uma instituição de ensino superior, buscando identificar diferenças entre os grupos de estudantes que concluíram o curso, permaneceram matriculados ou abandonaram os estudos.

O projeto foi desenvolvido como um mini projeto prático, aplicando conceitos de análise e manipulação de dados com Python.

## Fonte dos Dados

Os dados utilizados neste projeto foram extraídos do **UCI Machine Learning Repository**, referentes ao conjunto **Predict Students' Dropout and Academic Success** (Dataset #697).

- **Fonte principal:** [UCI Machine Learning Repository — Dataset 697](https://archive.ics.uci.edu/static/public/697/data.csv)
- **Data de extração / referência:** Novembro de 2026
  
## Objetivos

- Explorar uma base de dados educacionais.
- Identificar características relacionadas à trajetória acadêmica dos estudantes.
- Analisar indicadores de aprovação nos dois primeiros semestres.
- Comparar o desempenho acadêmico entre os diferentes resultados dos estudantes.
- Criar novas variáveis para facilitar a interpretação dos dados.

## Base de dados

A base utilizada foi obtida no **UCI Machine Learning Repository**, no conjunto de dados *Predict Students' Dropout and Academic Success*.

- Registros: 4.424 estudantes.
- Variáveis: 37 colunas.
- Fonte: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)

A variável de resultado acadêmico (*Target*) apresenta três categorias:

- Graduate: estudantes que concluíram o curso.
- Dropout: estudantes que abandonaram o curso.
- Enrolled: estudantes que permaneceram matriculados.

## Tecnologias e bibliotecas

- **Python:** linguagem utilizada no desenvolvimento.
- **Pandas:** leitura, manipulação e análise dos dados.
- **Matplotlib:** biblioteca utilizada para visualização de dados.
- **Google Colab:** ambiente utilizado para desenvolver e executar o notebook.

## Etapas do desenvolvimento

### 1. Carregamento dos dados

Importação das bibliotecas e leitura da base de dados diretamente da fonte UCI, com uma fonte alternativa configurada para situações de indisponibilidade.

### 2. Exploração dos dados

Análise inicial da estrutura da base, quantidade de registros, variáveis e distribuição dos resultados acadêmicos.

### 3. Preparação e manipulação dos dados

Organização das informações e seleção de variáveis relacionadas ao desempenho acadêmico e à trajetória dos estudantes.

### 4. Feature Engineering

Criação de novas variáveis para aprofundar a análise:

- Taxa de aprovação no primeiro semestre.
- Taxa de aprovação no segundo semestre.
- Evolução das notas entre os semestres.
- Classificação do aproveitamento acadêmico em categorias: alto, médio, baixo e sem carga.

### 5. Comparação dos indicadores

Agrupamento dos estudantes de acordo com o resultado acadêmico (Target), permitindo comparar as taxas de aprovação e a evolução das notas entre os grupos.

## Principais resultados observados

A comparação dos indicadores médios apresentou diferenças entre os grupos:

- **Graduate:** apresentou taxas médias de aprovação de aproximadamente 93,5% no primeiro semestre e 93,2% no segundo semestre.
- **Enrolled:** apresentou taxas médias de aproximadamente 71,4% no primeiro semestre e 67,3% no segundo semestre.
- **Dropout:** apresentou taxas médias de aproximadamente 40,6% no primeiro semestre e 31,0% no segundo semestre.

Os resultados mostram diferenças nos indicadores acadêmicos entre os grupos analisados, especialmente nas taxas de aprovação.

Essas associações são descritivas e não permitem, isoladamente, afirmar que um determinado fator causou a evasão ou a conclusão do curso.

## Aprendizados

Durante o desenvolvimento deste projeto, foram trabalhados conceitos importantes de análise de dados:

- Leitura e exploração de bases de dados.
- Manipulação de DataFrames com Pandas.
- Criação de indicadores e novas variáveis.
- Aplicação de funções e condições em Python.
- Tratamento de valores ausentes.
- Agrupamento e comparação de dados.
- Interpretação de resultados estatísticos descritivos.

## Como executar o projeto

1. Acesse o notebook disponível neste repositório.
2. Abra o arquivo utilizando o Google Colab.
3. Execute as células em sequência.
4. A base de dados será carregada diretamente da fonte UCI.

## Acesso ao projeto

[Visualizar notebook no GitHub][https://github.com/Soraia-Costa/Analise-de-dados_Programaria/blob/main/Projeto_Educacao/Mini_projeto_%E2%80%94_Educa%C3%A7%C3%A3o_entender_padr%C3%B5es_de_participa%C3%A7%C3%A3o_e_perman%C3%AAncia_estudantil_.ipynb)]

---

**Projeto desenvolvido para fins de aprendizado e prática em Análise de Dados.**
