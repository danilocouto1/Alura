# Dashboard de Salários na Área de Dados

Este projeto é uma aplicação em Streamlit para explorar salários na área de dados com filtros e gráficos interativos.

## Requisitos

- Python **3.12**  
  Esta versão é recomendada para evitar travamentos durante `pip install -r requirements.txt`.

## Passo a passo para rodar

1. Crie e ative um ambiente virtual:

```bash
# Windows (PowerShell)
python -m venv .venv
.venv\Scripts\Activate
```

2. Atualize o pip (opcional, mas recomendado):

```bash
python -m pip install --upgrade pip
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Execute a aplicação:

```bash
streamlit run app.py
```

## O que este código faz e como funciona

O arquivo `app.py`:

- Lê um arquivo CSV com dados de salários (carregado de um repositório no GitHub).
- Cria filtros na barra lateral (ano, senioridade, contrato, tamanho da empresa e cargos).
- Filtra o conjunto de dados de acordo com as escolhas do usuário.
- Exibe KPIs (salário médio, máximo, total de registros e cargo mais frequente).
- Mostra gráficos interativos (barra, histograma, pizza e mapa).
- Exibe a tabela completa do DataFrame filtrado.

## Ferramentas utilizadas

- **Python 3.12**
- **Streamlit** para a interface e a aplicação web.
- **Pandas** para leitura e filtragem dos dados.
- **Plotly Express** para gerar os gráficos interativos.

## Fonte dos dados

Os dados são carregados de um arquivo CSV hospedado em um repositório no GitHub disponibilizado pela Alura.  
Essa fonte pode sofrer mudanças ao longo do tempo (novas versões ou alterações no dataset).  
Se algo parecer diferente nos resultados, verifique se o CSV foi atualizado.
