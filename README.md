# Análise de Dados de Turismo no Nordeste Brasileiro (2009-2024)

## 📌 Visão Geral do Projeto
Análise completa dos dados de chegadas de turistas internacionais nos estados do Nordeste, com:
- Consolidação de dados oficíais do Ministério do Turismo
- Processamento de 16 datasets (2009-2024)
- Modelagem preditiva com Machine Learning

## 📊 Principais Análises
### Séries Temporais
- Evolução anual das chegadas
- Sazonalidade mensal
- Comparativo por via de acesso (aérea/terrestre/marítima)

### Origem dos Visitantes
- Distribuição por continentes
- Top 10 países emissores
- Análise geográfica

## 🛠️ Stack Tecnológica
Principais bibliotecas:
- Pandas, NumPy (ETL)
- Matplotlib, Seaborn (visualização)
- Scikit-learn (modelagem)
- Requests (API de dados)
🔍 Insights Relevantes
📈 Crescimento médio de X% ao ano (pré-pandemia)

✈️ 85% das chegadas por via aérea

🏖 Bahia e Pernambuco concentram XX% do fluxo

⏳ Sazonalidade acentuada em julho e dezembro

🧠 Modelo Preditivo
python
Copy
Random Forest Regressor:
- R²: 0.72
- MSE: 20653.58
- Variáveis mais importantes:
  1. Mês
  2. País de origem
  3. Via de acesso
## 📂 Estrutura do Código
extract/ - Coleta de dados

transform/ - Limpeza e consolidação

analysis/ - Visualizações e estatísticas

model/ - Desenvolvimento do modelo ML

## 🚀 Como Executar
bash
Copy
# 1. Instalar dependências
pip install -r requirements.txt

# 2. Executar pipeline completo
python main.py

# 📝 Licença
Dados abertos disponibilizados pelo Ministério do Turismo sob licença CC-BY-SA 4.0

# 📧 Contato
[[E-mail](cavalcanteprofissional@outlook.com)] | [[LinkedIn](https://www.linkedin.com/in/cavalcante-lucas/)]
