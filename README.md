# 🧠 Projeto de Análise e Preparação de Dados com PySpark

Olá! 👋 Meu nome é Jefferson e este repositório foi criado como parte do meu aprendizado no mundo da **Análise de Dados**, utilizando **PySpark** para manipulação e transformação de dados em grande escala.

O projeto está dividido em quatro etapas principais, cada uma representada por um notebook. Abaixo explico cada etapa de forma simples e direta.

---

## 📁 Arquivos do Projeto

### 1. `preparacao.ipynb` – **Preparação dos Dados**
> 🔹 **Objetivo**: Ler os arquivos brutos e preparar o ambiente para análise.

- Leitura de arquivos CSV e Parquet.
- Criação da sessão Spark.
- Visualização inicial dos dados.
- Ajustes básicos como renomear colunas e remover colunas desnecessárias.

🛠️ É o primeiro passo: organizar os dados e preparar o ambiente.

---

### 2. `tratamento.ipynb` – **Limpeza e Tratamento dos Dados**
> 🔹 **Objetivo**: Tratar dados inconsistentes ou nulos.

- Remoção de colunas irrelevantes (`_c0`, por exemplo).
- Verificação e remoção de valores nulos.
- Conversão de tipos de dados (por exemplo, transformar strings em datas).
- Criação de colunas auxiliares como `Year`, `Month` e `Day`.

🧹 Essa etapa é fundamental para garantir a qualidade dos dados antes de qualquer análise.

---

### 3. `agregacao.ipynb` – **Agregações e Análises Exploratórias**
> 🔹 **Objetivo**: Realizar agrupamentos e análises iniciais.

- Agrupamento de dados por colunas como `Keyword`, `Category`, etc.
- Cálculo de métricas como contagem, médias e valores máximos.
- Criação de colunas como `Interaction` (soma de curtidas + comentários).
- Uso de funções de janela (Window Functions) para rankeamento.

📊 Aqui começam as descobertas e os insights sobre os dados.

---

### 4. `otimizacao.ipynb` – **Otimização e Performance**
> 🔹 **Objetivo**: Melhorar a performance dos processos no PySpark.

- Particionamento de dados para escrita otimizada.
- Uso de `.repartition()` e `.coalesce()` para controlar paralelismo.
- Salvamento em formato Parquet com compressão.

⚙️ Essa parte ajuda a preparar os dados para uso em pipelines maiores ou ambientes de produção.

---

## 🚀 Tecnologias Utilizadas

- Python 🐍  
- Apache Spark (PySpark) ⚡  
- Google Colab 💻  
- Formatos de dados: CSV, Parquet 
