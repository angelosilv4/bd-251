# 📄 Prova Prática 01 — Banco de Dados (Chinook)

Este repositório contém a resolução da **Prova Prática 01** da disciplina de Banco de Dados, utilizando o banco **Chinook (versão SQLite)**.

As consultas foram desenvolvidas no **DB Browser for SQLite**, com prints das execuções e os respectivos comandos SQL organizados em PDF.

---

## ✅ Questões da Prova

### 📌 **1)**
> Listar os seguintes dados:
- Da tabela `invoices`: `InvoiceId`, `InvoiceDate`
- Da tabela `invoice_items`: `InvoiceItemId`, `UnitPrice`
- Total da fatura (somatório de todos os `UnitPrice`)

### 📌 **2)**
> Listar os seguintes dados:
- Da tabela `tracks`: `TrackId`, `Name`, `AlbumId`
- Da tabela `albums`: `Title`, `ArtistId`
- Da tabela `artists`: `Name`

### 📌 **3)**
> Listar os seguintes dados:
- Da tabela `tracks`: `TrackId`, `Name`, `Milliseconds`
- Da tabela `media_types`: `MediaTypeId`, `Name`
- Da tabela `genres`: `GenreId`, `Name`
- Selecionar apenas as faixas com `Milliseconds > 2000000`

> ℹ️ Todas as consultas utilizam `JOIN`.

---

## 🛠️ Execução

As queries foram executadas no **DB Browser for SQLite** com o arquivo `Chinook_Sqlite.sqlite`.

---

## 📎 Arquivos

- `prova_pratica_sql.pdf` — PDF com prints da execução e comandos SQL utilizados.
- `README.md` — Este arquivo de instruções e descrição da prova.

---
