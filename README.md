# Análise de Condições Ocupacionais e Fatores Associados ao Trabalho Remoto

## **Objetivos**
- Identificar os fatores mais relevantes associados ao trabalho remoto.
- Construir modelos preditivos para estimar a probabilidade de trabalho remoto com base em condições ocupacionais.
- Fornecer insights que possam orientar políticas públicas e estratégias empresariais.

---

## **Estrutura do Projeto**
- **`dicionario_PNADC_microdados_trimestre1_2023.pdf`**: Dicionário de variáveis fornecido pela PNAD para consulta e compreensão dos dados.
- **`projeto3.ipynb`**: Notebook contendo a análise exploratória e os modelos preditivos aplicados aos dados.
- **`.ipynb_checkpoints/`**: Arquivos gerados automaticamente pelo Jupyter Notebook.

---

### **Modelagem**
- **Modelos Utilizados**:
  - **Regressão Logística**: Para capturar relações lineares entre variáveis explicativas e a variável alvo.
  - **Random Forest**: Para identificar relações não lineares e determinar a importância das variáveis.

---

## **Resultados**

### **1. Regressão Logística**
- **Acurácia**: 98%.
- **Fatores Relevantes**:
  - Nível de instrução aumenta significativamente a probabilidade de trabalho remoto.
  - Ocupações administrativas possuem maior elegibilidade.

### **2. Random Forest**
- **Acurácia**: 98%.
- **Área sob a Curva (AUC)**: 1.00.

---

## **Como Reproduzir**

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto3-trabalho-remoto.git

2. Instale as dependências necessárias:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn

## **Conclusões**
Este projeto identificou que o nível de instrução, o grupamento ocupacional e o rendimento mensal são os fatores mais determinantes para a elegibilidade ao trabalho remoto. Os modelos desenvolvidos oferecem suporte à formulação de políticas públicas e decisões empresariais, promovendo um mercado de trabalho mais inclusivo e adaptado às transformações digitais.
