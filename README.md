# 📊 Imersão Dados com Python – Alura
Este projeto foi desenvolvido durante a **Imersão Dados com Python**, oferecida pela **Alura** em janeiro de 2026.  
O objetivo é analisar dados salariais da área de dados, explorando informações por meio de planilhas, gráficos e dashboards interativos, utilizando Python.

## 🚀 Dashboard Online
O dashboard final está disponível Streamlit: 🔗 https://dashboard-dados-py-alura.streamlit.app/

Nele, é possível filtrar os dados por:
- Ano
- Senioridade
- Tipo de contrato
- Tamanho da empresa  
Além de visualizar métricas e gráficos interativos sobre salários na área de dados.

## 🛠️ Tecnologias Utilizadas
- Python
- Pandas
- Streamlit
- Plotly

## ▶️ Como executar o projeto localmente
### Pré-requisitos
- Python instalado na máquina

### Passo a passo
1. Clone este repositório: git clone https://github.com/marys75/imersao-dados-python-alura.git
2. Crie um ambiente virtual de Pyhton: python3 -m venv .venv
3. Ative o ambiente virtual:
     em Windows: .venv\Scripts\Activate          em MAC/LINUX: source .venv/bin/activate
4. Instale as bibliotecas necessárias: pip install -r requirements.txt
5. Execute a aplicação: streamlit run app.py
6. O arquivo principal é app.py, requirements.txt é um arquivo com as bibliotecas usadas e dados-imersao-final.csv é um arquivo com o dataframe
