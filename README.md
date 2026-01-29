# 📊 Dashboard de Análise de Salários na Área de Dados

## 🎯 Objetivo do Projeto

Este projeto tem como objetivo desenvolver um **dashboard interativo** para análise exploratória de dados salariais na área de dados.  
A aplicação permite filtrar informações por diferentes critérios e visualizar métricas e gráficos que auxiliam na compreensão do mercado de trabalho em tecnologia.

O projeto foi desenvolvido durante a **Imersão Dados da Alura**, aplicando conceitos de **visualização de dados**, **tratamento de datasets** e **desenvolvimento de aplicações interativas com Python**.

---

## 🧠 Funcionalidades

✔️ Filtros interativos na barra lateral por:
- Ano  
- Senioridade  
- Tipo de contrato  
- Tamanho da empresa  

✔️ Métricas principais (KPIs):
- Salário médio anual  
- Salário máximo anual  
- Total de registros filtrados  
- Cargo mais frequente  

✔️ Gráficos interativos:
- Top 10 cargos por salário médio (gráfico de barras)  
- Distribuição salarial (histograma)  
- Proporção dos tipos de trabalho (remoto/presencial/híbrido)  
- Salário médio de Data Scientists por país (mapa mundial)  

✔️ Tabela detalhada com os dados filtrados  

---

## 🗂️ Conjunto de Dados

O dataset contém informações sobre profissionais da área de dados, com os seguintes atributos principais:

| Coluna | Descrição |
|--------|-----------|
| ano | Ano de referência do registro |
| senioridade | Nível de senioridade do profissional |
| contrato | Tipo de contrato de trabalho |
| cargo | Cargo ocupado |
| salario | Salário na moeda local |
| moeda | Moeda original do pagamento |
| usd | Salário anual convertido em USD |
| residencia | País de residência |
| residencia_iso3 | Código ISO3 do país |
| remoto | Tipo de trabalho (remoto/presencial/híbrido) |
| empresa | País da empresa |
| tamanho_empresa | Porte da empresa |

---

## 💻 Tecnologias Utilizadas

- **Python**
- **Pandas** — Manipulação e filtragem de dados  
- **Streamlit** — Criação do dashboard interativo  
- **Plotly Express** — Visualizações gráficas interativas  
- **Google Colab / VS Code** — Ambiente de desenvolvimento  

---

## 📈 Estrutura do Dashboard

O código realiza:

1. Criação de filtros dinâmicos na sidebar  
2. Aplicação de filtros no DataFrame  
3. Cálculo de métricas gerais (KPIs)  
4. Geração de gráficos interativos  
5. Exibição de tabela detalhada  

Tudo em tempo real conforme a seleção do usuário.

---

## ▶️ Como Executar o Projeto

### 1️⃣ Instale as dependências
```bash
pip install streamlit pandas plotly

### 2️⃣ Execute a aplicação
python -m streamlit run src/main.py
