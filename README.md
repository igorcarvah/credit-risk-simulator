# 📈 Dashboard de Inteligência Financeira & Risco
> **Uma abordagem estatística sobre o mercado brasileiro**

Este projeto é um laboratório digital que se conecta à B3 para transformar dados brutos em decisões fundamentadas (**Data-Driven Decision Making**), ideal para investidores e estudantes de finanças.

---

## 🎯 1. O Que Este Painel Faz?

O sistema realiza três tarefas complexas em tempo real:

1.  **Diagnóstico:** Performance setorial comparada (Base 100).
2.  **Raio-X de Risco:** Análise de oscilação e relação risco-retorno.
3.  **Clarividência (Simulação):** Utiliza o método de **Monte Carlo** para projetar milhares de futuros possíveis, definindo intervalos de confiança.



---

## 🧭 2. Manual de Bordo (Como Interpretar)

Traduzimos conceitos estatísticos para linguagem de negócios para facilitar sua análise:

| Conceito Técnico | Visualização | Tradução para a Vida Real |
| :--- | :--- | :--- |
| **Volatilidade** | Eixo X | **A Montanha-Russa:** Quanto maior, mais o preço "chacoalha". É o índice de emoção do ativo. |
| **Drawdown** | Gráfico de Área | **O Buraco:** A distância entre o preço atual e a máxima histórica. "Quanto eu estaria perdendo se tivesse comprado no pico?" |
| **Correlação** | Heatmap | **A Dança:** +1 significa que dançam juntos; -1 significa proteção (quando um sobe, o outro desce). |
| **Monte Carlo** | Cone Azul | **O Multiverso:** 1.000 cenários futuros. A área azul mostra onde há 95% de chance do preço estar. |

---

## 🧪 3. Laboratório: Experiências para Testar

Siga estas "receitas" para extrair insights imediatos:

### 🧪 Experiência A: "A Guerra dos Bancos"
* **Objetivo:** Comparar Bancos Digitais vs. Tradicionais.
* **Ação:** Selecione Nubank/Inter e Itaú/Bradesco.
* **Insight:** Observe se o retorno extra dos digitais compensa a volatilidade (posição à direita no gráfico).

### 🧪 Experiência B: "O Efeito Juros no Varejo"
* **Objetivo:** Entender a sensibilidade do setor varejista.
* **Ação:** Compare Magalu (MGLU3) com o Ibovespa (IBOV).
* **Insight:** Note o **Drawdown** agressivo do varejo em crises, ilustrando o conceito de "Beta Alto".

---

## 📊 4. Glossário de Métricas (KPIs)

| Métrica | O que nos diz? |
| :--- | :--- |
| **Sharpe Ratio** | A "nota" da ação. Acima de 1.0 é excelente; negativo significa que o risco não compensou. |
| **VaR (95%)** | O limite de perda diária provável. Ex: -4% significa que há uma chance real de cair 4% em um dia. |

---

## 🛠 Tecnologias
* **Dash & Plotly:** Interface e gráficos dinâmicos.
* **Yfinance:** Extração de dados da B3/Nasdaq.
* **Pandas & NumPy:** Cálculos vetoriais e manipulação de dados.
* **SciPy:** Modelagem estatística e Distribuição Normal.

---

## ⚠️ Disclaimer (Aviso Legal)

**Este projeto tem fins estritamente educacionais e didáticos.** As análises, simulações e dados apresentados neste dashboard:
* **Não constituem recomendação de investimento** (compra, venda ou manutenção de ativos).
* São baseados em dados históricos, e **performance passada não é garantia de resultados futuros**.
* Utilizam modelos estatísticos (como Monte Carlo) que trabalham com probabilidades, não com certezas.

O autor não se responsabiliza por quaisquer decisões financeiras tomadas com base nas informações visualizadas nesta ferramenta. Consulte sempre um profissional de investimentos certificado.

---

**Autor:** Igor Carvalho  
*Análise desenvolvida para o curso de Estatística (Anhembi Morumbi).*


---
**Autor:** Igor Carvalho  
*Análise desenvolvida para o curso de Estatística (Anhembi Morumbi).*
