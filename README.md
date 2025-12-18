# MVP_Engenharia_de_Dados
Notebook desenvolvido em atendimento ao MVP da Sprint Engenharia de Dados do curso de Ciência de Dados &amp; Analytics da PUC Rio.

---

# 📊 Análise de Desempenho Acadêmico com Arquitetura Medalhão

## 📌 Visão Geral

Este repositório contém o desenvolvimento de um **MVP de análise de dados educacionais**, estruturado a partir da **arquitetura medalhão (Bronze, Silver e Gold)**. O projeto tem como objetivo transformar dados acadêmicos brutos em **produtos analíticos confiáveis**, permitindo a investigação de padrões de frequência, engajamento e desempenho dos estudantes ao longo de múltiplos semestres.

---

## 🎯 Objetivos do Projeto

* Implementar um pipeline de dados seguindo o padrão medalhão
* Realizar limpeza, padronização, validação e tipagem dos dados
* Construir a camada **Gold** com tabelas de fatos e dimensões em formato **Delta**
* Analisar a relação entre frequência, participação e desempenho acadêmico
* Gerar insumos analíticos para apoio à tomada de decisão educacional

---

## 🏗️ Arquitetura de Dados

O pipeline foi estruturado da seguinte forma:

* **Bronze**: ingestão dos dados brutos, preservando o formato original
* **Silver**: limpeza, padronização, coerção de tipos, validação e enriquecimento
* **Gold**: publicação dos dados em tabelas semânticas (fatos e dimensões), prontas para consumo analítico

> **Silver entrega dados corretos.
> Gold entrega modelos de consumo.**

---

## 🗂️ Estrutura do Repositório

```bash
.
├── data/
│   ├── bronze/          # Dados brutos
│   ├── silver/          # Dados tratados e validados
│   └── gold/            # Tabelas analíticas (Delta)
├── notebooks/
│   └── MVP_Engenharia_de_Dados.ipynb      # Notebook principal do projeto
├── docs/
│   └── relatorio.pdf    # Documento final do trabalho
└── README.md
```

---

## 📈 Principais Resultados

* Frequência média dos alunos em torno de **75%**
* Média das notas finais **abaixo de 50** ao longo de **10 semestres**
* Evidência de que a presença em sala, isoladamente, não garante desempenho acadêmico
* Indícios de um problema estrutural relacionado à qualidade do engajamento e às práticas pedagógicas

---

## 🧠 Metodologia

* Processamento de dados com **Apache Spark**
* Armazenamento em **Delta Lake**
* Modelagem dimensional (fatos e dimensões)
* Análise exploratória e descritiva dos dados
* Discussão dos resultados com base em evidências empíricas

---

## 🚀 Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/marcelegv/MVP_Engenharia_de_Dados/
   ```
2. Abra o notebook principal (`MVP_Engenharia_de_Dados.ipynb`)
3. Execute as células sequencialmente a partir da ingestão dos dados

> Recomenda-se ambiente compatível com Spark e Delta Lake (ex.: Databricks ou Spark local configurado).

---

## ⚠️ Limitações

* Ausência de variáveis qualitativas (socioeconômicas e pedagógicas)
* Análises baseadas em correlação, não em causalidade
* Dados limitados ao contexto acadêmico analisado

---

## 🔮 Trabalhos Futuros

* Inclusão de novas fontes de dados
* Aplicação de modelos preditivos para evasão e baixo desempenho
* Construção de dashboards interativos
* Evolução do modelo Gold para consumo institucional

---

## 👤 Autor

**Marcele G Veiga**
Projeto desenvolvido para fins acadêmicos e demonstrativos.

---

## 📄 Licença

Este projeto é disponibilizado para fins educacionais e acadêmicos. Consulte o arquivo de licença para mais detalhes.

---
