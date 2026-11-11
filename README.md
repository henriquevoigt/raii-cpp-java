# Estudo Comparativo: RAII em C++ vs. Gerenciamento Determinístico em Java

Repositório referente ao trabalho prático da disciplina de **Conceitos de Linguagens de Programação (CLP)**.

## Objetivo

Estudar o princípio *Resource Acquisition Is Initialization* (RAII) em C++ e compará-lo aos mecanismos de gerenciamento determinístico de recursos em Java (`AutoCloseable` e `try-with-resources`), por meio da implementação de um processador sequencial de arquivos textuais em ambas as linguagens.

## Estrutura do Repositório

- `cpp/` — Implementação em C++ explorando RAII, escopo léxico, destrutores e fluxos da biblioteca-padrão (`<fstream>`).
- `java/` — Implementação em Java explorando `AutoCloseable`, `try-with-resources` e classes de entrada/saída da biblioteca-padrão.
- `tests/` — Casos de teste padronizados (`T1` a `T6`) e script de verificação para reprodução dos experimentos nas duas linguagens.
- `relatorio.pdf` — Relatório técnico contendo o estudo conceitual, descrição das implementações, resultados dos testes e análise comparativa (incluído na versão final de entrega).

## Requisitos

- **C++:** Compilador compatível com C++17 ou superior (`g++` ou `clang++`) e `make`.
- **Java:** JDK 17 ou superior (`javac` e `java`).

## Como Compilar e Executar

As instruções detalhadas de compilação, execução manual e execução automatizada da bateria de testes (`T1` a `T6`) serão disponibilizadas junto às implementações nas pastas `cpp/`, `java/` e `tests/`.
