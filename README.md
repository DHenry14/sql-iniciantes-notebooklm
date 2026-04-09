<p align="center">
  <img src="https://img.shields.io/badge/SQL-Iniciantes-blue?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL Badge"/>
</p>

<h1 align="center">📊 SQL para Iniciantes</h1>
<h3 align="center">Guia Prático e Estruturado</h3>

<p align="center">
  <em>Projeto desenvolvido para o desafio da DIO utilizando NotebookLM como ferramenta de apoio ao aprendizado</em>
</p>

---

## 📋 Índice

- [Visão Geral](#-visão-geral)
- [Objetivos de Estudo](#-objetivos-de-estudo)
- [Principais Conceitos](#-principais-conceitos-de-sql)
- [Exemplo Prático](#-exemplo-prático)
- [Glossário](#-glossário)
- [Prompts Reutilizáveis](#-prompts-reutilizáveis)
- [Curadoria de Fontes](#-curadoria-de-fontes)
- [Próximos Passos](#-próximos-passos)

---

## 🎯 Visão Geral

Este projeto é um **caderno temático** focado no aprendizado de SQL para iniciantes. O objetivo é apresentar os principais conceitos de forma clara, prática e estruturada, combinando teoria, exemplos e aplicação real.

Ao longo do material, são explorados desde comandos básicos até a construção de consultas mais completas, utilizando **boas práticas de aprendizado com apoio de Inteligência Artificial**.

---

## 🎓 Objetivos de Estudo

| # | Objetivo |
|---|----------|
| 1 | Compreender os fundamentos de SQL e bancos de dados relacionais |
| 2 | Aprender a escrever consultas utilizando `SELECT` |
| 3 | Utilizar filtros com `WHERE` e ordenação com `ORDER BY` |
| 4 | Entender o funcionamento de `JOIN` entre tabelas |
| 5 | Desenvolver base prática para uso de SQL no mercado |

---

## 💡 Principais Conceitos de SQL

### `SELECT`
> Utilizado para consultar dados em uma tabela.

```sql
SELECT nome FROM clientes;
```

### `WHERE`
> Filtra os dados retornados.

```sql
SELECT * FROM clientes WHERE cidade = 'São Paulo';
```

### `ORDER BY`
> Organiza os resultados.

```sql
SELECT * FROM clientes ORDER BY nome ASC;
```

### `JOIN`
> Permite juntar dados de múltiplas tabelas.

```sql
SELECT clientes.nome, pedidos.valor
FROM clientes
INNER JOIN pedidos
ON clientes.id = pedidos.cliente_id;
```

### `CREATE TABLE`
> Cria estruturas no banco de dados.

```sql
CREATE TABLE clientes (
  id INT PRIMARY KEY,
  nome VARCHAR(100),
  email VARCHAR(100)
);
```

---

## 🔬 Exemplo Prático

**Cenário:** Listar clientes de São Paulo ordenados por nome.

```sql
SELECT nome, cidade
FROM clientes
WHERE cidade = 'São Paulo'
ORDER BY nome;
```

> 💡 Esse exemplo mostra como combinar **seleção**, **filtro** e **ordenação** em uma única consulta.

---

## 📖 Glossário

| Termo | Definição |
|-------|-----------|
| `SELECT` | Consulta dados |
| `WHERE` | Filtra dados |
| `ORDER BY` | Ordena resultados |
| `GROUP BY` | Agrupa dados |
| `JOIN` | Junta tabelas |
| `PRIMARY KEY` | Identificador único |
| `FOREIGN KEY` | Relacionamento entre tabelas |
| `TABLE` | Estrutura de dados |
| `QUERY` | Consulta SQL |

---

## 🤖 Prompts Reutilizáveis

Durante o desenvolvimento, foi possível perceber a evolução na qualidade das respostas conforme os prompts eram refinados.

### Aprendizados sobre Engenharia de Prompts

> - ❌ Perguntas genéricas geram respostas superficiais
> - ✅ Estruturar a pergunta melhora a clareza
> - ✅ Pedir exemplos práticos aumenta muito o aprendizado
> - ✅ Definir formato (passo a passo) gera respostas aplicáveis

### Templates de Prompts

<details>
<summary><strong>📚 Aprender conceito</strong></summary>

```
Explique [COMANDO SQL] com definição, exemplo e erros comuns
```
</details>

<details>
<summary><strong>✏️ Praticar</strong></summary>

```
Crie um exercício de SQL com solução comentada
```
</details>

<details>
<summary><strong>⚖️ Comparar</strong></summary>

```
Explique a diferença entre [COMANDO A] e [COMANDO B]
```
</details>

<details>
<summary><strong>🏢 Aplicar</strong></summary>

```
Crie um cenário real usando SQL com exemplos de consultas
```
</details>

---

## 📚 Curadoria de Fontes

As fontes abaixo foram utilizadas para garantir um aprendizado consistente e confiável:

| Fonte | Link |
|-------|------|
| Documentação Snowflake | [docs.snowflake.com](https://docs.snowflake.com/pt/sql-reference/sql-all) |
| DevMedia — Guia Completo | [devmedia.com.br](https://www.devmedia.com.br/guia/guia-completo-de-sql/38314) |
| DataCamp — SQL Tutorials | [datacamp.com](https://www.datacamp.com/pt/tutorial/category/sql) |
| Microsoft Learn | [learn.microsoft.com](https://learn.microsoft.com/pt-br/sql/sql-server/educational-sql-resources) |
| Guru99 — SQL Tutorial | [guru99.com](https://www.guru99.com/pt/sql.html) |
| Curso de SQL (YouTube) | [youtube.com](https://youtu.be/Lr0E8EFbmBE) |

---

## 🚀 Próximos Passos

- [ ] Praticar consultas diariamente
- [ ] Criar pequenos projetos com banco de dados
- [ ] Aprender JOINs mais avançados
- [ ] Estudar modelagem de dados

---

## 📝 Conclusão

O aprendizado de SQL se torna muito mais eficiente quando combinado com **prática** e **uso inteligente de prompts**. Mesmo conceitos simples podem resolver problemas reais quando bem aplicados.

Mapa mental gerado pelo notebookLM:

<p align="center">
  <img src="https://github.com/user-attachments/assets/a6ab0776-e517-4cee-8d0c-81a4bb35f95a" alt="NotebookLM Mind Map" width="800"/>
</p>

---

## 📌 Sobre o Projeto

| Item | Detalhe |
|------|---------|
| **Desafio** | DIO — Caderno Temático com IA |
| **Plataforma** | NotebookLM |
| **Tema** | SQL para iniciantes |
| **Autor** | Denyel Feitosa |

