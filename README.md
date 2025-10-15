# 🧺 Minicurso: Criando meu dashboard em R

**Desenvolvido por [Sara S. Ferreira](#-desenvolvedora)**  

Um painel interativo criado em **R** com **Flexdashboard** e **Shiny**, que permite explorar os produtos que compõem a cesta básica brasileira, analisando sua evolução de preços e participação no valor total da cesta ao longo do tempo.  

---

## 📊 Visão Geral

Este dashboard tem como objetivo **facilitar a visualização e análise dos dados da cesta básica**, permitindo filtrar os produtos e os anos de interesse e observar como os preços médios e valores totais se comportam.

A interface é dinâmica e intuitiva, oferecendo **gráficos interativos**, **tabelas exportáveis** e **indicadores automáticos**.

---

## 🚀 Funcionalidades Principais

### 🔎 Filtros Interativos
- **Seleção de produtos:** escolha um ou mais produtos da cesta básica.  
- **Intervalo de anos:** ajuste o período de análise através de um controle deslizante.

### 🧾 Tabela de Dados
- Exibe os registros filtrados com opção de **exportar** em diferentes formatos (CSV, Excel, PDF, etc.).

### 📦 Indicadores (Value Boxes)
- **Registros filtrados:** quantidade de observações exibidas.  
- **Produto mais caro:** identifica o item com maior valor médio no período selecionado.

### 🥧 Gráfico 1 — Participação dos Produtos
- Exibe um **gráfico de pizza interativo** mostrando a **participação percentual de cada produto** no **valor total da cesta básica** (`Valor_Total`).  
- Ideal para entender o peso de cada item na composição da cesta.

### 📈 Gráfico 2 — Evolução do Valor Médio
- Mostra a **variação do valor médio (`Valor_Medio`) dos produtos ao longo dos anos** selecionados.  
- Cada linha representa um produto, facilitando comparações e identificação de tendências.

---

## 🧰 Tecnologias Utilizadas

| Tecnologia | Descrição |
|-------------|------------|
| **R** | Linguagem principal do projeto |
| **Shiny** | Framework para aplicações web interativas |
| **Flexdashboard** | Criação do layout do painel |
| **Plotly** | Gráficos interativos e responsivos |
| **DT** | Exibição de tabelas dinâmicas e exportáveis |
| **Tidyverse** | Manipulação e limpeza dos dados |
| **Scales** | Formatação de valores e escalas |


