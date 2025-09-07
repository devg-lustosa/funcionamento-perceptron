# 🧠 Perceptron em Python

Este projeto demonstra o funcionamento de um **Perceptron simples**, implementado em Python, mostrando como entradas, pesos e bias influenciam no resultado final de uma classificação binária.

---

## 1️⃣ Conceito
O **Perceptron** é um modelo inspirado nos neurônios biológicos.  
Ele recebe valores de entrada (**inputs**), multiplica cada um por um **peso** associado, soma esses valores e adiciona um **bias**. Em seguida, aplica uma **função de ativação** para decidir se a saída será `0` ou `1`.

🔹 Historicamente, o Perceptron foi o primeiro modelo de rede neural artificial (década de 1950), marcando o início dos estudos em **Inteligência Artificial**. Apesar de simples e limitado, abriu caminho para modelos mais complexos, como as **redes neurais profundas**.

---

## 2️⃣ Funcionamento
O Perceptron é considerado um **classificador linear**.  
Isso significa que ele só consegue separar dados que podem ser divididos por uma **reta (2D)**, um **plano (3D)** ou um **hiperplano (n-dimensões)**.

### ✅ Vantagem
- Simples e rápido para problemas binários (exemplo: sim/não, positivo/negativo).  

### ⚠️ Limitações
- Não resolve problemas **não lineares**, como o famoso caso do **XOR**.  
- Modelos mais avançados são necessários para situações complexas.

---

## 3️⃣ Estrutura do Código
No código implementado, temos três partes principais:

1. **Função `perceptron_input`**  
   - Calcula a soma ponderada das entradas multiplicadas pelos pesos, adicionando o bias.  

2. **Função `perceptron_output`**  
   - Aplica a função de ativação: se o valor da soma ponderada for maior ou igual a `0`, retorna `1`; caso contrário, retorna `0`.  

3. **Função `main`**  
   - Executa um exemplo prático, mostrando o cálculo da entrada do perceptron com os valores `[1, 2, 3]`, pesos `[0.1, 0.2, 0.3]` e bias `0.4`.

📌 Diferente de implementações completas, aqui **não há treinamento com ajuste automático de pesos**. Os valores de pesos e bias são fixos para fins didáticos.

---

## 4️⃣ Aplicação Prática
Um exemplo real onde um Perceptron simples pode ser aplicado é na **detecção de e-mails spam**.  

📩 Imagine que queremos classificar um e-mail como **spam (1)** ou **não spam (0)**.  
Entradas poderiam ser:
- Presença de certas palavras-chave  
- Número de links no corpo do e-mail  
- Se o remetente está ou não na lista de contatos  

Cada entrada teria um peso e, somados ao bias, resultariam na decisão final.  

🔎 Esse modelo é limitado, mas para problemas simples e lineares pode oferecer uma solução rápida e de fácil entendimento.

---

## ▶️ Como Executar
1. Certifique-se de ter o **Python 3** instalado.  
2. Salve o código em um arquivo, por exemplo `perceptron.py`.  
3. No terminal, rode o comando:  
   ```bash
   python perceptron.py
