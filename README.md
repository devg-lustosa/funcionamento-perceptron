# 🧠 Perceptron em Python

Este projeto mostra um exemplo simples de funcionamento de um **Perceptron** implementado em Python.

---

### 1. Conceito  
**O que é um Perceptron e qual a sua importância histórica?**  
O Perceptron é um modelo matemático inspirado em um neurônio biológico. Ele soma entradas ponderadas por pesos, adiciona um bias e aplica uma função de ativação para decidir a saída (0 ou 1).  
Historicamente, foi o primeiro modelo de rede neural (década de 1950) e marcou o início dos estudos em Inteligência Artificial.

---

### 2. Funcionamento  
**O Perceptron é um classificador linear. O que isso significa? Quais limitações ele tem?**  
Ser classificador linear significa que ele só consegue separar dados que podem ser divididos por uma linha (ou plano/hiperplano em mais dimensões).  
A principal limitação é que ele **não resolve problemas não lineares**, como o famoso caso do **XOR**.

---

### 3. Código  
**Quais foram as etapas principais do código implementado?**  
- Função `perceptron_input`: calcula a soma ponderada das entradas + bias.  
- Função `perceptron_output`: aplica a função de ativação (retorna 1 se ≥ 0, senão 0).  
- Função `main`: executa um exemplo prático com valores fixos de entrada, pesos e bias.  

---

### 4. Aplicação prática  
**Dê um exemplo real em que o uso de um Perceptron seria útil.**  
Um exemplo é a **classificação de e-mails em spam ou não spam**. O perceptron pode usar características como palavras-chave, quantidade de links ou remetente para decidir se um e-mail é spam (1) ou não (0).  
Esse tipo de modelo funciona bem para problemas simples e binários.

---

### ▶️ Como executar
1. Tenha o **Python 3** instalado.  
2. Salve o código como `main.py`.  
3. Execute no terminal:  
   ```bash
   python main.py
