# Dashboard de Salários na Área de Dados

![GitHub last commit](https://img.shields.io/github/last-commit/Douglas-Perez/Imersao-de-Dados-Alura)
![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.2.3-150458?logo=pandas)
![Plotly](https://img.shields.io/badge/Plotly-5.24.1-3F4F75?logo=plotly)
![Streamlit](https://img.shields.io/badge/Streamlit-1.44.1-FF4B4B?logo=streamlit)

Aplicação interativa desenvolvida em **Python** durante a **Imersão de Dados** da [Alura](https://www.alura.com.br/), com o objetivo de explorar informações sobre salários na área de dados.  
O projeto permite filtrar e visualizar dados de forma dinâmica e interativa, utilizando gráficos e KPIs.

Acesse a versão online: [**Dashboard de Salários**](https://imersao-de-dados-alura-hpxecvdnu5gm3zbvoeishc.streamlit.app/)

---

## Funcionalidades

* **Filtros interativos**:
  * Ano
  * Senioridade
  * Tipo de contrato
  * Tamanho da empresa
* **Indicadores principais (KPIs)**:
  * Salário médio
  * Salário máximo
  * Total de registros
  * Cargo mais frequente
* **Visualizações interativas**:
  * Top 10 cargos por salário médio
  * Distribuição de salários
  * Proporção de tipos de trabalho (remoto, presencial, híbrido)
  * Mapa de salários médios para Cientistas de Dados por país
* **Tabela detalhada** dos dados filtrados

---

## Como Usar

1. **Selecionar filtros**:
   * Ajuste os filtros na barra lateral para definir Ano, Senioridade, Tipo de contrato e Tamanho da empresa.
2. **Visualizar métricas**:
   * Veja os KPIs atualizados automaticamente com base nos filtros aplicados.
3. **Explorar gráficos**:
   * Analise a distribuição de salários, cargos mais bem pagos e tendências geográficas.
4. **Consultar tabela**:
   * Visualize os dados detalhados na parte inferior do dashboard.

---

## Tecnologias Utilizadas

* **Python 3.10+** – Linguagem principal.
* **Pandas 2.2.3** – Manipulação e análise de dados.
* **Plotly 5.24.1** – Criação de gráficos interativos.
* **Streamlit 1.44.1** – Criação da interface web.

---

## Estrutura do Projeto

* **app.py** – Código principal do dashboard.
* **dados-imersao-final.csv** – Dataset utilizado no projeto.
* **requirements.txt** – Lista de dependências.
* **README.md** – Documentação do projeto.

---

## Como Executar o Projeto

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/Douglas-Perez/Imersao-de-Dados-Alura.git
   cd Imersao-de-Dados-Alura
   ```

2. **Crie e ative um ambiente virtual**:

   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Linux/Mac
   .venv\Scripts\activate      # Windows
   ```

3. **Instale as dependências**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Execute o dashboard**:

   ```bash
   streamlit run app.py
   ```

---

## Dependências

```txt
pandas==2.2.3
streamlit==1.44.1
plotly==5.24.1
```

---

## Licença

Este projeto foi desenvolvido para fins educacionais durante a **Imersão de Dados** da Alura.  
O código está disponível para uso e adaptação com os devidos créditos.
