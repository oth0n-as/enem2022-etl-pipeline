# Projeto Data Major – Pipeline ETL com Microdados do ENEM 2022

## 📖 Sobre o projeto
Este projeto foi desenvolvido para a disciplina Tópicos de Banco de Dados do Centro Universitário IESB[cite: 1].

O objetivo é construir um pipeline ETL completo utilizando os microdados do ENEM 2022, desde a coleta automatizada dos dados até a etapa de mineração, buscando analisar como fatores socioeconômicos e demográficos influenciam o desempenho dos participantes[cite: 1].

## 🎯 Objetivo
Investigar a relação entre características dos candidatos e sua nota final no ENEM por meio de um pipeline composto pelas etapas de[cite: 1]:
* **Extract**[cite: 1]
* **Transform**[cite: 1]
* **Load**[cite: 1]
* **Data Mining**[cite: 1]

## 🛠 Tecnologias utilizadas
* **Linguagem:** Python[cite: 1]
* **Ambiente:** Google Colab[cite: 1]
* **Manipulação e Análise de Dados:** Pandas, NumPy[cite: 1]
* **Processamento Distribuído:** Apache Spark (PySpark)[cite: 1]
* **Armazenamento:** Parquet, Snappy, Google Drive[cite: 1]
* **Machine Learning / Estatística:** Scikit-learn[cite: 1]

## 📂 Estrutura do projeto
```text
.
├── projeto_datamajor.ipynb
├── README.md
├── raw/
├── processed/
├── load/
└── metadata/

```

## 🔄 Pipeline ETL

### 📥 Extract

* Download automático dos microdados do ENEM 2022.

* Verificação da integridade do arquivo utilizando hash SHA-256.

* Extração automatizada do conteúdo.

* Registro detalhado de metadados.

### ⚙️ Transform

* Seleção seletiva das variáveis relevantes (otimização de memória).

* Tratamento de dados ausentes e inconsistentes.

* Remoção de registros inválidos.

* Engenharia de atributos (criação de novas features).

* Conversão e preparação dos dados para o formato Parquet.

### 📤 Load

* Armazenamento de alta performance utilizando Apache Spark.

* Particionamento estratégico do dataset.

* Compressão utilizando algoritmo Snappy.

* Geração de metadados finais.

### 🧠 Mineração de Dados (Data Mining)

Aplicação de um modelo de **Regressão Linear Múltipla** para analisar e mensurar o impacto real de variáveis demográficas e socioeconômicas sobre a nota final obtida no ENEM.

## 📊 Base de dados

* **Fonte oficial:** INEP – Microdados ENEM 2022
* [Link para o portal do INEP](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem)

## 👥 Equipe

| Integrante | Responsabilidade |
| --- | --- |
| **Othon Flávio Alves de Sales** | Extract

 |
| **Mariana Paiva de Souza Moreira** | Transform

 |
| **Nikolas Silva de Sousa** | Load

 |
| **Matheus de Paula Machado Turturro** | Mineração

 |

## 🚀 Como executar

1. Clone o repositório:

```bash
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)

```

2. Abra o arquivo `projeto_datamajor.ipynb` no Google Colab.

3. Monte o seu Google Drive para estruturar as pastas.

4. Execute as células na ordem apresentada.

## 📈 Resultados

O pipeline realiza todas as etapas do processo ETL com sucesso e produz um conjunto de dados tratado, otimizado e armazenado em formato Parquet, pronto para análises estatísticas profundas e modelagem preditiva.

## 📄 Licença

Projeto desenvolvido exclusivamente para fins acadêmicos.

```

```
