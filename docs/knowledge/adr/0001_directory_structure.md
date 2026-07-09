# ADR-0001 ディレクトリ構成

## 日付

2025-07-09

---

## 状況

AI System Analyst を開発するにあたり、
ソースコードだけではなく、
設計書・ナレッジ・サンプルプロジェクトを
同一リポジトリで管理したい。

---

## 検討した案

### 案1

docsを作らない

却下

理由

設計書が散らばる。

---

### 案2

設計書をdocs配下へ集約する

採用

理由

GitHub上で管理しやすい。

Project Charter

Requirements

Basic Design

Detail Design

という流れが自然になる。

---

## 採用した構成

backend

frontend

docs

scripts

config

assets

tests

examples

---

## 期待する効果

・設計書とコードを同時管理できる

・AIがMarkdownを生成しやすい

・PDF化もしやすい