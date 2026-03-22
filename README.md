# 🎓 Descrição do Desafio de Modelagem Dimensional

## 🎯 Objetivo
Criar o diagrama dimensional – **Star Schema** – com base no diagrama relacional disponibilizado de uma universidade.

---

## 🖼️ Imagens de Referência
* 📂 [Visualizar Imagem de referência](DOCS/Imagem_referencia_professor.png)
* 📊 [Visualizar Imagem do Modelo Final](DOCS/Universidade_Dimensional.png)

---

## 🔍 Foco: Professor – Objeto de Análise
O esquema em estrela foi montado estrategicamente com o foco na análise dos dados dos **professores**. Sendo assim, a tabela fato reflete diversos indicadores sobre o corpo docente, cursos ministrados e o departamento ao qual fazem parte.

> **⚠️ Atenção:** Conforme os requisitos, não é necessário refletir dados sobre os alunos!

---

## 🚀 O que deve ser feito?

### 1️⃣ Criação da Tabela Fato
Deverá ser criada a tabela **Fato** que contém o contexto analisado. Esta tabela centraliza as métricas de desempenho e a carga horária docente para suporte à decisão.

### 2️⃣ Criação das Tabelas Dimensão
As tabelas dimensão são compostas pelos detalhes relacionados ao contexto, permitindo filtros avançados por:

* 👨‍🏫 **Professor:** Dados detalhados do docente.
* 📚 **Disciplina:** Informações sobre as matérias oferecidas.
* 🏫 **Curso:** Detalhes do curso e departamento vinculado.

### 3️⃣ Dimensão de Datas 📅
Adição de uma tabela dimensão de datas para suportar toda a análise temporal do projeto.

* **Granularidade:** Dia / Mês / Ano (DD/MM/AAAA) (ex: 18/03/2026).
* **📅 Ano Base:** A partir de 2026.
* **📂 Hierarquia:** Ano ➡️ Trimestre ➡️ Mês ➡️ Dia.

---
✨ *Projeto desenvolvido como parte do desafio de especialização em análise de dados.*
