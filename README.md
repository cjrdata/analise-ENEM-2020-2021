# 🎓 Projeto: Análise de Dados do ENEM 2020-2021 + Machine Learning

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/2b/ENEM_logo.png" width="200"/>
</p>

---

# 📚 Sobre o Projeto

Este projeto tem como objetivo analisar o desempenho de estudantes brasileiros no ENEM dos anos 2020 e 2021, buscando entender a relação entre:

- Tipo de escola (Pública vs Privada)
- Faixa de renda familiar
- Desempenho acadêmico em diferentes áreas do conhecimento

Além disso, foi aplicado um modelo de Machine Learning para prever o tipo de escola com base nas notas e renda.

---

# 🧹 Etapas do Projeto

- **Coleta de Dados**: Utilização da plataforma [Base dos Dados](https://basedosdados.org/).
- **Tratamento e Limpeza**: Ajuste de nulos e tradução de variáveis.
- **Análise Exploratória**: Distribuição de tipo de escola, renda familiar e comparação de notas.
- **Machine Learning**: Modelo de Árvore de Decisão para previsão do tipo de escola.

---

# 📊 Principais Resultados

## 🎯 Comparação de Notas - Escola Pública vs Privada

| Tipo de Escola | Ciências Natureza | Ciências Humanas | Linguagens | Matemática |
|:---|:---|:---|:---|:---|
| Pública | 492.18 | 520.54 | 513.39 | 528.11 |
| Privada | 469.71 | 496.09 | 495.01 | 502.71 |

> **Nota:** Na amostra analisada, estudantes de escolas públicas apresentaram notas médias superiores às de privadas, indicando possíveis efeitos da pandemia, perfil de participantes e recortes amostrais.

---

## 📈 Análise de Notas vs Renda

- Identificada **correlação positiva**: quanto maior a faixa de renda, maior a média das notas em todas as áreas.
- As diferenças de desempenho tornam-se mais visíveis nas faixas de renda superiores.

---

## 🤖 Machine Learning

- **Modelo**: Decision Tree Classifier
- **Acurácia**: 57%
- **Observação**: Melhor desempenho na previsão de alunos de escolas privadas.

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fb/Decision_tree_model.png" width="300"/>
</p>

---

# 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

# 🚀 Próximos Passos

- Testar Random Forest e XGBoost para melhoria da acurácia
- Aplicar técnicas de balanceamento de classes (SMOTE)
- Desenvolver um dashboard interativo no Power BI

---

# 🧠 Conclusão

O projeto evidencia a forte relação entre fatores socioeconômicos e desempenho escolar no Brasil, mesmo em cenários atípicos como a pandemia.  
A aplicação de técnicas de ciência de dados permite visualizar essas disparidades de maneira crítica e fundamentada.

---

# 📢 Observação Final

> Este estudo é baseado em uma amostra dos microdados do ENEM e pode conter limitações relacionadas à seleção de variáveis e vieses amostrais.

---

# 👩‍💻 Autor(a)

> Projeto desenvolvido por **CAMILA DE JESUS RODRIGUES**  
> 📫 https://www.linkedin.com/in/camila-rodrigues-9ab744178/

---
