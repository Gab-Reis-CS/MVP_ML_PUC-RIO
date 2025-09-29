# MVP_ML_PUC-RIO 
**Modelagem Preditiva de Acidentes Rodoviários - Dados da PRF**

## Descrição
Este projeto implementa um **MVP (Minimum Viable Product)** de Machine Learning aplicado à análise e predição de acidentes rodoviários no Brasil, utilizando dados públicos disponibilizados pela **Polícia Rodoviária Federal (PRF)**.  
O objetivo é desenvolver, avaliar e comparar modelos de classificação capazes de prever categorias de acidentes a partir de atributos registrados nas ocorrências.

---

## Funcionalidades
- **Carregamento e pré-processamento de dados**: limpeza, tratamento de valores ausentes e codificação de variáveis categóricas.  
- **Análise exploratória**: estatísticas descritivas e inspeção de balanceamento entre classes.  
- **Modelos de classificação**:  
  - Baseline (modelo simples para comparação inicial).  
  - RandomForestClassifier (modelo principal avaliado).  
- **Métricas de avaliação**:  
  - Acurácia  
  - F1-score (macro)  
  - Relatório de classificação por classe  
  - Matriz de confusão  
- **Discussão de erros e limitações**: identificação de classes mais difíceis de prever, impacto do desbalanceamento de classes e propostas de melhorias futuras.

---

## Estrutura do projeto
- `Machine_Learning_MVP_FINAL2.ipynb` → Notebook principal com todo o pipeline.  
- `datatran2025.csv` → Base de dados de acidentes da PRF.  

---

## Requisitos
- Python 3.8+  
- Jupyter Notebook  
- Bibliotecas:  
  - pandas  
  - numpy  
  - matplotlib  
  - scikit-learn  

---

## Fonte dos Dados
- Dados públicos da PRF:  
  [Portal de Dados Abertos da PRF](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf)  

---

## Licença
Este projeto está licenciado sob a **MIT License**.  

## 🛠 Instalação
Clone este repositório:
```bash
git clone https://github.com/Gab-Reis-CS/MVP-PUC-Rio.git
cd MVP-PUC-Rio

[datatran2025.csv](https://github.com/user-attachments/files/22586645/datatran2025.csv)
