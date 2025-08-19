# ✈️ Análise de Preços de Passagens Aéreas

Este repositório contém uma análise exploratória de dados (EDA) sobre preços de passagens aéreas, utilizando **Python** e bibliotecas como **Pandas, Matplotlib e Seaborn**.  

O objetivo principal é **treinar habilidades em análise de dados** e entender melhor como variáveis como classe, horário, duração do voo e antecedência da compra impactam no valor da passagem.

---

## 📊 Objetivos da Análise

- Explorar a **distribuição dos preços** de passagens aéreas.  
- Verificar a diferença de preço entre **classe econômica e executiva**.  
- Analisar se a **duração do voo** influencia no preço.  
- Investigar a variação de preço por **horário de partida**.  
- Descobrir as **rotas mais caras e mais baratas**.  
- Avaliar o impacto da **antecedência da compra** no valor da passagem.  

---

## 📈 Principais Conclusões

- Os preços apresentam **forte assimetria à direita**, com alguns outliers acima de 100.000 USD.  
- A **classe executiva** é significativamente mais cara e apresenta maior variação de valores.  
- A **duração do voo** influencia no preço, mas não é o fator mais determinante.  
- O **horário da madrugada** tende a ter preços médios mais elevados, possivelmente pela baixa oferta de voos.  
- A **antecedência da compra** é o fator que mais impacta no preço: quanto mais perto da data do voo, maior o valor.  

---

## 🛠️ Tecnologias Utilizadas

- [Python 3.10+](https://www.python.org/)  
- [Pandas](https://pandas.pydata.org/) para manipulação de dados  
- [Matplotlib](https://matplotlib.org/) e [Seaborn](https://seaborn.pydata.org/) para visualização
- Jupyter Notebook para desenvolvimento

---

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/marcossilva11/analise_voos.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd analise_voos
   ```
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
4. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Execute o arquivo `analise_voos.ipynb`.

---

## 📂 Estrutura do projeto
```bash
├── analise_voos.ipynb   # Notebook principal com a análise
├── requirements.txt     # Bibliotecas necessárias
└── README.md            # Documentação do projeto
```

---

## ✍️ Autor

Projeto desenvolvido como prática em **Análise de Dados com Python** por **Marcos**.
