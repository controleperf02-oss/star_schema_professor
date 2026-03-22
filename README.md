# Descrição do Desafio de Modelagem Dimensional

## Objetivo
Criar o diagrama dimensional – **star schema** – com base no diagrama relacional disponibilizado.

## Imagens de Referência
* [Imagem de referência](DOCS/Imagem_referencia_professor.png)
* [Imagem do Modelo Final](DOCS/Universidade_Dimensional.png)

## Foco: Professor – Objeto de Análise
O esquema em estrela foi montado com o foco na análise dos dados dos **professores**. Sendo assim, a tabela fato reflete diversos dados sobre professor, cursos ministrados e departamento ao qual faz parte.

> **Atenção:** Não é necessário refletir dados sobre os alunos!

## O que deve ser feito?

### 1. Criação da Tabela Fato
Deverá ser criada a tabela **Fato** que contém o contexto analisado. Esta tabela centraliza as métricas de desempenho e carga horária docente.

### 2. Criação das Tabelas Dimensão
As tabelas dimensão são compostas pelos detalhes relacionados ao contexto, permitindo filtros por:

* **Professor:** Dados detalhados do docente.
* **Disciplina:** Informações sobre as matérias.
* **Curso:** Detalhes do curso e departamento.

### 3. Dimensão de Datas
Adição de uma tabela dimensão de datas para suportar a análise temporal.

* **Granularidade:** Dia / Mês / Ano (DD/MM/AAAA) (ex: 18/03/2026).
* **Ano Base:** A partir de 2026.
* **Hierarquia:** Ano, Trimestre, Mês, Dia.
