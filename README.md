# 📈 Churn Analysis — Telecom X

## 📌 Visão Geral
Este projeto investiga os *fatores que influenciam a saída de clientes (churn)* na Telecom X.  
Entender por que clientes cancelam é essencial, pois o impacto vai além da perda de receita — inclui também o custo de adquirir novos consumidores.

A análise se concentrou em três frentes:
- 🔍 *Identificar* padrões e perfis mais propensos ao cancelamento.  
- 💡 *Fornecer insights* para retenção e fidelização.  
- 🧠 *Criar base sólida* para futuros modelos de previsão.  

---

## 📂 Obtenção e Preparação dos Dados
- *Fonte:* Arquivo JSON hospedado no GitHub.  
- *Arquivo:* TelecomX_Data.json  
- *Ferramentas:* Python (Pandas, Requests)  

*Etapas principais:*
1. Conversão do JSON em DataFrame (pd.json_normalize).
2. Padronização dos nomes de colunas (snake_case).
3. Conversão de tipos numéricos e categóricos.
4. Criação de métricas derivadas (cobranca_diaria, tempo_cliente_meses).
5. Tratamento de valores ausentes e correção de inconsistências.

---

## 🔍 Análise Exploratória (EDA)

### Variáveis Categóricas
- Avaliação de *gênero, **tipo de contrato* e *método de pagamento*.
- Uso de *gráficos de barras* e *pizza* para comparação entre clientes ativos e cancelados.

*Principais insights:*
- 📅 *Contratos mensais* apresentaram maior evasão.  
- 💳 *Pagamento automático* esteve associado a maior retenção.  
- ⚖ *Gênero* não apresentou diferença relevante no churn.  

### Variáveis Numéricas
- Principais métricas: cobranca_total, tempo_cliente_meses, cobranca_mensal, cobranca_diaria.
- Uso de *boxplots* e *KDE* para análise de distribuições.

*Padrões encontrados:*
- ⏳ Clientes com pouco tempo de contrato cancelam mais.  
- 💰 Cobrança mensal alta tende a aumentar churn.  
- 📉 Cobrança total baixa geralmente indica saída precoce.  

---

## 📌 Principais Conclusões
- *Tempo de contrato* é um forte preditor de cancelamento.
- *Planos caros*, especialmente mensais, têm maior churn.
- *Pagamento automático* e *múltiplos serviços* ajudam na retenção.

---

## 💡 Recomendações
- Criar *ofertas promocionais* para novos clientes nos primeiros meses.  
- Incentivar *planos anuais/bianuais*.  
- Ajustar preços para clientes de cobrança mensal alta.  
- Estimular *adesão ao pagamento automático*.  

---

## 🚀 Próximos Passos
- Implementar *modelos de machine learning* para prever clientes em risco.  
- Executar *campanhas de retenção direcionadas*.  
- Integrar *dados de atendimento e suporte* para enriquecer as análises.  

---

## 📊 Tecnologias Utilizadas
- *Python*
- *Pandas*
- *Seaborn*
- *Matplotlib*
- *Google Colab*

---

✍ *Autor:* Ruthciris06
