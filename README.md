# 📊 TelecomX - Análise de Evasão de Clientes (Churn)

## 📝 Descrição do Projeto
A retenção de clientes é um dos maiores desafios estratégicos no setor de telecomunicações. Este projeto tem como objetivo analisar a base de dados de clientes da **TelecomX** para entender o fenômeno da evasão (**Churn**). 

Através da limpeza de dados, engenharia de recursos (feature engineering) e Análise Exploratória de Dados (EDA), o projeto identifica os perfis de clientes com maior probabilidade de cancelar os serviços. Os insights gerados visam auxiliar a tomada de decisão e o direcionamento de campanhas de retenção.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Python 3**
* **Pandas:** Para manipulação, limpeza e transformação dos dados estruturados.
* **Matplotlib & Seaborn:** Para visualização de dados e criação de gráficos estatísticos.
* **Google Colab:** Ambiente de desenvolvimento em nuvem utilizado para a execução e documentação da análise.

## 📁 Estrutura do Projeto
O notebook principal (`TelecomX_BR.ipynb`) está dividido nas seguintes etapas lógicas:
1. **Extração:** Consumo dos dados brutos em formato JSON a partir de uma API externa e conversão para DataFrame.
2. **Transformação e Limpeza:**
   * Achatamento (flattening) de colunas aninhadas (dicionários).
   * Tratamento de valores nulos e inconsistentes.
   * Padronização de variáveis categóricas para formato binário (0 e 1).
   * Conversão de tipos de dados (financeiros para `float`).
   * Criação de novas variáveis (`Contas_Diarias` e `Total_Servicos`).
3. **Análise Exploratória (EDA):**
   * Distribuição geral da evasão.
   * Análise do impacto de variáveis categóricas (Gênero, Contrato, Método de Pagamento).
   * Matriz de Correlação (Heatmap) para identificar relações matemáticas entre o Churn e variáveis numéricas.
4. **Relatório Final:** Síntese dos achados e recomendações de negócio.

## 🚀 Como Executar o Projeto Localmente

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)

2. **Acesse a pasta do projeto:**

   ```bash
  cd nome-do-repositorio

3. **Instale as dependências necessárias:**
   ```bash
   pip install pandas matplotlib seaborn 

4. **Abra o projeto no seu editor:**
   ```bash
   Abra o arquivo .ipynb e execute as células sequencialmente.

5. **Abra o projeto no seu editor:**
   ```bash
   Abra o arquivo .ipynb e execute as células sequencialmente.

## Desenvolvido por Tanuris Pina