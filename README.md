# 📊 Dashboard de Análise de Risco e Mercado

> Projeto desenvolvido para democratizar a estatística financeira, traduzindo conceitos complexos de risco e retorno para uma linguagem de negócios clara e acionável.

---

## 🎯 1. O que este Dashboard faz?
Ele realiza duas tarefas complexas em tempo real:

* **Diagnosticar (Base 100):** Raio-X de Risco. Quem oscila mais? Quem compensa o risco?
* **Clarividência (Simulação):** Utiliza o método de **Monte Carlo** para projetar milhares de futuros possíveis e definir um intervalo de confiança para o preço de uma ação.

---

## 🧭 2. Manual de Bordo (Como Interpretar)
Para facilitar a leitura, traduzimos os conceitos estatísticos para uma linguagem de negócios:

| Conceito Técnico | O que aparece na tela | Tradução para a Vida Real |
| :--- | :--- | :--- |
| **Volatilidade** | Eixo X do gráfico "Risco vs Retorno" | **A Montanha-Russa.** Quanto maior a volatilidade, mais o preço chacoalha. É o "Índice de Emoção" (e perigo) do ativo. |
| **Drawdown** | Gráfico de Área (Vermelho/Cinza) | **O Buraco.** Mostra a distância entre o preço atual e o preço máximo histórico. Responde: *"Quanto eu estaria perdendo se tivesse comprado no pico?"* |
| **Correlação** | Heatmap e Scatter Plot | **A Dança.** Se for +1, os ativos dançam juntos (sobem juntos). Se for -1, um sobe e o outro desce (proteção). |
| **Monte Carlo** | O Cone Azul (Fan Chart) | **O Multiverso.** O computador simula 1.000 cenários futuros. A área azul é onde o preço tem 95% de chance de estar. |

---

## 🧪 3. Laboratório: 3 Experiências para Você Testar
Não sabe por onde começar? Siga estas "receitas" para extrair insights valiosos do dashboard agora mesmo:

### 🧪 Experiência A: "A Guerra dos Bancos"
* **Objetivo:** Descobrir se vale a pena correr o risco dos Bancos Digitais.
* **Configuração:** Grupo A: Selecione Bancos Digitais (Nubank, Inter) | Grupo B: Selecione Bancos Tradicionais (Itaú, Bradesco).
* **O que observar:** Olhe o gráfico Risco vs Retorno.
* **Hipótese:** O Nubank provavelmente estará mais alto (mais retorno), mas muito mais à direita (mais risco/volatilidade) que o Itaú. O usuário deve se perguntar: *"Esse retorno extra paga a minha insônia?"*

### 🧪 Experiência B: "O Efeito Juros no Varejo"
* **Objetivo:** Entender por que a Magalu sofre tanto.
* **Configuração:** Grupo A: Selecione Varejo (Risco) | Grupo B: Selecione Macro (Dólar/Ibov).
* **O que observar:** Olhe o gráfico de Drawdown.
* **Hipótese:** Você verá que enquanto o Ibovespa cai 10% ou 15% em crises, o Varejo chega a cair 80% ou 90%. Isso ilustra o conceito de "Beta Alto" (sensibilidade extrema à economia).

### 🧪 Experiência C: "Prevendo o Futuro do Nubank"
* **Objetivo:** Usar estatística para projetar preço.
* **Configuração:** Vá até o final da página (Laboratório Preditivo). Selecione Nubank (ROXO34) e defina o prazo para 180 dias.
* **O que observar:** O Cone Azul. Veja o valor do "Cenário Pessimista" (texto em vermelho).
* **Insight:** Se o cenário pessimista for aceitável para você, o investimento é considerado seguro segundo a sua tolerância a risco.

---

## 📊 4. Glossário de Métricas (Tabela KPI)
Na tabela no canto inferior direito, você verá números "crus". Veja como ler:

* **Sharpe Ratio:** É a nota da ação.
    * *Acima de 1.0:* Excelente. O risco valeu a pena.
    * *Entre 0 e 1.0:* Ok. Pagou as contas.
    * *Negativo:* Péssimo. Você correu risco para perder dinheiro.
* **VaR (95%):** O limite de perda diária. Se o VaR for -4%, significa: *"Prepare-se, pois existe uma chance real de cair 4% em um único dia."*

---

## 🛠 Tecnologias e Bibliotecas
Este projeto foi construído utilizando a stack de Data Science do Python:

* **Dash & Plotly:** Para a construção da interface web interativa e gráficos dinâmicos.
* **Yfinance:** API para extração de dados históricos da B3 e Nasdaq.
* **Pandas & NumPy:** Para manipulação de dados e cálculos vetoriais.
* **SciPy:** Para modelagem estatística e geração de números aleatórios (distribuição normal).

---

## ⚖️ Aviso Legal (Disclaimer)
Este projeto foi desenvolvido para fins **educacionais e acadêmicos**.
* As análises e simulações (Monte Carlo) apresentadas são baseadas em dados históricos e modelos estatísticos.
* **Não constitui recomendação de investimento.** Retornos passados não garantem retornos futuros.
* O autor não se responsabiliza por decisões financeiras tomadas com base nestas informações.

---

###### Autor: Igor Carvalho - Análise desenvolvida para o curso de Estatística (Anhembi Morumbi).