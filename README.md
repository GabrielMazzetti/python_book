# Python, Web Scraping e Livros Digitais: Uma Introdução

[![Quarto](https://img.shields.io/badge/Quarto-Renderizado-blue?logo=quarto)](https://quarto.org/)
[![Python](https://img.shields.io/badge/Python-3.x-FFD43B?logo=python&logoColor=blue)](#)

> **Autor:** Gabriel Sanábio Mazzetti Affonso  
> **Acesso Web (GitHub Pages):** [🔗 Clique aqui para ler o livro digital](https://gabrielmazzetti.github.io/python_book/) <br>
> **Versão em PDF:** [📥 Clique aqui para baixar o livro completo](./livro_python_scraping.pdf)  

Este repositório contém o código-fonte e o material desenvolvido durante o período de Iniciação Científica, vinculado ao projeto **Métodos de Aprendizado Estatístico para Discriminação e Classificação: Aplicações à Indústria 4.0 – Fase 3** da Universidade Federal de Juiz de Fora (UFJF).

O objetivo desta obra é fornecer uma ponte ágil e aplicada para que estudantes e profissionais de Estatística possam dar seus primeiros passos na linguagem *Python*. O material foca na transição do pensamento estatístico para o ecossistema da linguagem, abordando manipulação de dados, computação numérica de alta performance, coleta automatizada de informações na internet e a publicação reprodutível dos resultados.

## 📖 Estrutura do Material

O conteúdo foi estruturado de forma sequencial para garantir uma curva de aprendizado contínua, separando os arquivos-fonte em um diretório próprio (`capitulos/`):

* **Capítulo 1 - Introdução:** Contextualização da ferramenta no cenário da Ciência de Dados.
* **Capítulo 2 - Configuração:** Preparação do ambiente RStudio via `reticulate` e gerenciamento de pacotes com o `pip`.
* **Capítulo 3 - Fundamentos:** Sintaxe básica, funções nativas e manipulação de listas e estruturas de controle.
* **Capítulo 4 - Análise Exploratória e Manipulação de Dados:** O fluxo de *Data Wrangling* com `pandas` e visualizações estatisticamente acessíveis utilizando `seaborn` e `matplotlib` (aplicados aos *datasets* Titanic e Iris).
* **Capítulo 5 - Computação Numérica com NumPy:** A revolução da vetorização, indexação booleana, simulações estatísticas e demonstrações empíricas (como o Teorema Central do Limite).
* **Capítulo 6 - Web Scraping:** Automação e coleta de dados não estruturados na internet utilizando `requests` e `BeautifulSoup`.
* **Capítulo 7 - Livros Digitais:** Estruturação de relatórios dinâmicos, padronização visual com templates e compilação de projetos complexos utilizando o **Quarto**.

## Tecnologias Utilizadas

* **Linguagem Principal:** Python 3
* **Bibliotecas Focais:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `requests`, `BeautifulSoup`
* **Autoria e Compilação:** Quarto (para renderização em HTML e PDF)
* **IDE Recomendada:** RStudio / VS Code

## Como Compilar o Livro Localmente

Este material foi escrito utilizando o sistema de publicação científica e técnica [Quarto](https://quarto.org/). O projeto está configurado no arquivo mestre `_quarto.yml`.

Para compilar os arquivos `.qmd` e gerar o livro na sua própria máquina, certifique-se de ter o Quarto instalado. Em seguida, abra o terminal na pasta raiz deste repositório e execute:

```bash
quarto render
```
