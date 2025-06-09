# 📊 Análise Exploratória da Dívida Ativa Nacional

Este projeto realiza uma análise exploratória completa de um dataset público sobre devedores inscritos na dívida ativa. Utilizando Python, Pandas e Matplotlib, foram extraídos insights relevantes a partir de mais de 30 mil registros de dívidas, abrangendo perfis de devedores, credores, situação dos créditos e tendências temporais.

---

## 🚀 Objetivos do Projeto

- Compreender o perfil dos maiores devedores (pessoa física vs jurídica, tipo do devedor)
- Identificar quais órgãos públicos concentram os maiores valores devidos
- Analisar a situação dos créditos (parcelados, suspensos, etc.)
- Avaliar padrões temporais de inscrição de dívidas
- Gerar insights estatísticos que podem ajudar em políticas de cobrança ou auditorias

---

## 📂 Fontes de Dados

- **Dataset**: [Kaggle - Devedores da Dívida Ativa](https://www.kaggle.com/datasets/carlosqbarbosa/devedores-da-dvida-ativa)

---

## 🛠️ Ferramentas Utilizadas

- Python 3.11
- Pandas
- Matplotlib
- Jupyter Notebook (recomendado para execução)

---

## 🔍 Estrutura da Análise

1. **Visão Geral do Dataset**
   - Formato dos dados
   - Tipos de colunas
2. **Perfil dos Devedores**
   - Pessoa física vs jurídica
   - Top 10 devedores
   - Tipos de devedor (principal, solidário etc.)
3. **Análise dos Credores**
   - Credores com maiores dívidas acumuladas
   - Distribuição da dívida entre órgãos
4. **Situação do Crédito**
   - Quantidade e valor por tipo de situação
   - Valor médio de dívidas por situação
5. **Análise Temporal**
   - Evolução da dívida ao longo dos anos
   - Anos com picos de inscrição
6. **Estatísticas Interessantes**
   - Valores totais
   - Maiores devedores e credores
   - Percentuais e curiosidades
7. **Conclusões**
   - Principais padrões identificados
   - Possíveis usos práticos da análise

---

## 📊 Exemplos de Visualizações

- Gráficos de barra com os maiores devedores
- Gráficos de pizza para distribuição por tipo de pessoa e credor
- Linhas temporais mostrando a evolução das dívidas
- Subplots temáticos para apresentar múltiplas análises por categoria

---

## 📈 Resultados Destacados

- O maior devedor do dataset acumula mais de **R$ 1 milhão** em dívidas.
- Cerca de **70%** das dívidas pertencem a pessoas físicas.
- O **Banco Central** e **INSS** estão entre os maiores credores.
- A maioria das dívidas está na situação **"Parcelado"**, indicando acordos em andamento.
- O ano com maior inscrição de dívidas foi **2024** (provavelmente reflexo de políticas fiscais).

---

## 📎 Como Rodar Localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/divida-ativa-analise.git
cd divida-ativa-analise

# Instale as dependências
pip install pandas matplotlib

# Execute o notebook
jupyter notebook divida_ativa_analise.ipynb
