# 🛒 Análise de Big Data Aplicada ao E-commerce  

Este projeto tem como objetivo aplicar técnicas de **Big Data e Aprendizado de Máquina** para otimizar a personalização da experiência do usuário, prever demanda de produtos e aprimorar a eficiência logística de uma empresa de e-commerce. Através da análise de grandes volumes de dados, são extraídos insights estratégicos para a tomada de decisão empresarial.  

---

## **📌 Objetivos do Projeto**  
- **Modelo de Recomendação Personalizado**: Implementação de um modelo de recomendação baseado em técnicas de similaridade vetorial utilizando FAISS.  
- **Modelagem Preditiva de Demanda**: Utilização de algoritmos de aprendizado de máquina para prever a demanda futura de produtos.  
- **Otimização da Cadeia Logística**: Análise preditiva para definir locais estratégicos para centros de distribuição.  

---

## **📌 Tecnologias Utilizadas**  
Para o desenvolvimento deste projeto, foram utilizadas as seguintes tecnologias:  

✅ **Google Colab** – Ambiente de desenvolvimento para análise de dados e modelagem preditiva.  
✅ **FAISS (Facebook AI Similarity Search)** – Implementação de um sistema de recomendação baseado em busca vetorial eficiente.  
✅ **Scikit-Learn** – Algoritmos de Machine Learning para previsão de demanda.  
✅ **Pandas e NumPy** – Manipulação e análise de grandes volumes de dados.  
✅ **Matplotlib e Seaborn** – Visualização e interpretação de padrões de consumo.  
✅ **GitHub** – Versionamento e controle do código-fonte.  

---

## **📂 Estrutura do Repositório**  
- 📄 `bigdata_ecommerce.ipynb` → Notebook contendo a implementação do projeto.  
- 📊 `clientes.csv` → Conjunto de dados fictícios representando clientes do e-commerce.  
- 🛍️ `compras.csv` → Histórico de transações de compra.  
- ❗ `reclamacoes.csv` → Base de dados contendo reclamações e feedbacks dos clientes.  

---

## **📊 Metodologia e Implementação**  

### **1️⃣ Coleta e Processamento de Dados**  
Os dados foram gerados artificialmente para simular interações reais em uma plataforma de e-commerce. O processamento e a estruturação das informações foram realizados utilizando **Pandas** e **NumPy**, garantindo a integridade e a eficiência da manipulação de dados.  

### **2️⃣ Sistema de Recomendação (FAISS)**  
O modelo de recomendação foi implementado utilizando **FAISS (Facebook AI Similarity Search)**, um método altamente eficiente para busca de similaridade em grandes bases de dados. Cada cliente teve seu histórico de compras transformado em um vetor numérico, e FAISS foi utilizado para encontrar clientes com padrões de consumo semelhantes.  

Essa abordagem permite **personalizar ofertas, otimizar estratégias de marketing e aumentar as taxas de conversão**, pois sugere produtos com base em interações reais dos usuários.  

### **3️⃣ Modelagem Preditiva de Demanda (Random Forest Regressor)**  
Para prever a demanda futura de produtos, utilizamos um modelo de **Random Forest Regressor**, um algoritmo de aprendizado de máquina baseado em múltiplas árvores de decisão.  

📌 **Motivação da Escolha:**  
O **Random Forest** foi escolhido por sua robustez e capacidade de capturar padrões não lineares em grandes volumes de dados. Alternativas como **Regressão Linear** e **Redes Neurais** foram consideradas, mas apresentaram menor desempenho para este tipo de problema específico devido à complexidade das interações entre variáveis.  

O modelo foi treinado com dados históricos de compras e utilizou variáveis como **mês, categoria do produto e volume de vendas** para prever demandas futuras.  

### **4️⃣ Visualização e Análise dos Resultados**  
A interpretação dos resultados foi facilitada por gráficos gerados com **Matplotlib e Seaborn**, que permitiram identificar tendências de consumo, sazonalidade e padrões de comportamento dos clientes.  

---

## **🚀 Como Executar o Projeto?**  

1️⃣ **Clone este repositório:**  
```bash
git clone https://github.com/Negosea/bigdata-ecommerce.git
