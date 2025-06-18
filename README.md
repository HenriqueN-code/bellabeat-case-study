# 📊 Bellabeat Case Study — Análise de Dados com R

Este projeto tem como objetivo aplicar conceitos de análise de dados com **R** para investigar o comportamento de uso de dispositivos smart fitness (Fitbit) e gerar insights estratégicos para a empresa **Bellabeat**.

---

## 🧠 Objetivo do Projeto

Bellabeat deseja entender como usuários utilizam dispositivos como o Leaf para melhorar sua saúde e bem-estar. A partir da análise dos dados da Fitbit, buscamos responder:

- Como os usuários distribuem sua atividade física ao longo do tempo?
- Qual a relação entre sono, atividade e queima calórica?
- Que padrões podem embasar decisões de marketing da Bellabeat?

---

## 🧰 Ferramentas Utilizadas

- **Linguagem:** R
- **Bibliotecas:** `tidyverse`, `lubridate`, `janitor`, `ggplot2`, `dplyr`
- **Plataforma de execução:** Kaggle Notebooks (Kernel R)
- **Formato do código:** Jupyter Notebook (`.ipynb`) com kernel R

---

## 🔍 Principais Etapas

1. **Importação e limpeza dos dados**
   - Padronização de colunas com `janitor`
   - Conversão de datas com `lubridate`
   - Remoção de duplicatas

2. **Análise exploratória**
   - Visualização de padrões de atividade física ao longo da semana
   - Correlação entre minutos de atividade intensa com perca de calorias
   - Eficiência das atividades fisicas intensas na parca de calorias

3. **Correlação e interpretação**
   - Correlação entre passos, calorias e atividades intensas
   - Sugestões práticas com base nos dados

---

## 📌 Insights Gerados
- Há correlação positiva entre passos e queima calórica.
- Usuários realizam um maior numero de atividades leves no sábado, provavelmente atrelado a lazer ou afazeres que não podem ser realizados durante a semana.
- Atividades intensas são muito eficazes na perca de calorias em seus primeiros 30 minutos.
- Oportunidade para criar notificações que incentivem atividades intensas mesmo que de curta duração; criação de um sistema de recompensas/progressão para engajar os usuários.


---

## 🔗 Fonte dos Dados

O dataset utilizado é público, proveniente da [base de dados Fitbit no Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit).

---

## ▶️ Como Executar o Projeto

1. Faça o clone deste repositório:
```bash
git clone https://github.com/seu-usuario/bellabeat-case-study.git



