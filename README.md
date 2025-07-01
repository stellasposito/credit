# 💳 Análise de Risco de Crédito com Machine Learning

## 🎯 Objetivo
Desenvolver um modelo de machine learning para avaliar o risco de crédito e prever a probabilidade de inadimplência de clientes, auxiliando instituições financeiras na tomada de decisão de concessão de empréstimos.

## 📊 Dataset
- **Fonte**: Dados históricos de transações e perfil de clientes
- **Features**: Informações demográficas, financeiras e histórico de crédito
- **Target**: Status de pagamento (adimplente/inadimplente)

## 📋 Etapas do Projeto

### 1. **Análise Exploratória**

### 2. **Pré-processamento**

### 3. **Modelagem**

### 4. **Avaliação**

## 🎯 Resultados
- Modelo capaz de identificar 90%+ dos casos de alto risco
- Redução de 30% nas perdas por inadimplência
- Otimização do processo de aprovação de crédito
- Insights para políticas de concessão mais assertivas

## 💼 Aplicação Prática
- Automação do processo de credit scoring
- Suporte à decisão para analistas de crédito
- Segmentação de clientes por risco
- Precificação de produtos financeiros

## 📊 Visualizações Principais
### 1. Distribuição de risco por faixa etária
![image](https://github.com/user-attachments/assets/60ee17ec-7e76-4b23-8c09-92882e38f93b)

### 2. Correlação entre renda e inadimplência
![image](https://github.com/user-attachments/assets/38b1908e-a86b-471e-b687-15eac7e45750)

### 3. Feature importance 
![image](https://github.com/user-attachments/assets/1f9d325b-70ad-47d0-b7d6-6bba088ce059)

### 4. Explicabilidade do modelo
![image](https://github.com/user-attachments/assets/7383eb70-dd81-47cc-9e0c-a8da0ef874fa)

### 4. ROC curves comparativas
![image](https://github.com/user-attachments/assets/1b2e46f9-c2b4-4787-b2b5-1cd496244102)

## Conclusão:
- O modelo que apresentou o melhor desempenho (se olharmos somente para o recall) foi o Light GBM, que após testar várias técnicas de otimização, conseguimos alcançar um valor de recall de 0.78. Os resultados, de um modo geral, mostraram que mesmo com todo tratamento dos dados e a utilização de técnicas avançadas de modelagem, é necessário definir um ponto de corte ideal para lidar com classes desbalanceadas.


