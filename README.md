# Análise Geográfica e Demográfica de Países com Python + Power BI

Este projeto tem como objetivo explorar dados públicos sobre países, com foco em características geográficas, demográficas e sociais.
Os dados foram extraídos da **API REST Countries** utilizando Python, tratados, estruturados em DataFrames e convertidos em arquivo csv, e posteriormente analisados e visualizados com o Power BI.

---

## Objetivo

Criar uma base consolidada com informações relevantes sobre países do mundo e transformá-la em insights acessíveis por meio de visualizações interativas no Power BI.

---

## Tecnologias Utilizadas

- **Python** — Para extração e pré-processamento dos dados
- **Pandas** — Manipulação dos dados em DataFrames
- **Requests** — Consumo da API REST Countries
- **Power BI** — Análise visual e geração dos dashboards

---

## Fontes de Dados

- [REST Countries API](https://restcountries.com/) — API pública com dados de países, como:
  - População
  - Área
  - Idiomas
  - Moedas
  - Regiões e sub-regiões
  - Densidade demográfica (calculada)

---

## Estrutura do Projeto

- Extração dos dados via API e conversão em JSON
- Criação de **3 DataFrames** com informações complementares:
  - Dados principais por país
  - Idiomas e moedas associados
  - Dados de localização e densidade
- Salvar os DataFrames em arquivos CSV
- Exportação para Power BI com relacionamento entre tabelas
- Criação de visuais interativos com filtros por continente, idioma, moeda etc.

---

## Exemplos de Análises

- Ranking dos países mais populosos e mais extensos
- Mapa interativo por continente
- Densidade populacional global
- Quantidade de países por idioma oficial ou moeda

---

## Como Usar

1. Execute o script Python para extrair os dados da API REST Countries
2. Salve os DataFrames como `.csv` ou integre direto com Power BI
3. Construa ou atualize os visuais no Power BI com base nos dados tratados

---

## 👨‍💻 Autor

Projeto desenvolvido por Eduardo Coelho.

---
