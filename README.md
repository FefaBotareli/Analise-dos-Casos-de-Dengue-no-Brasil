# Análise Exploratória de Dados: Monitoramento Histórico da Dengue no Brasil

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Manipulation-lightgrey.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualização-orange.svg)
![Status](https://img.shields.io/badge/Status-Concluído-green.svg)

## 📌 Sobre o Projeto
Este projeto foi desenvolvido originalmente como parte do escopo prático de pós-graduação e aprimorado para simular um cenário real de mercado. O objetivo principal é transformar dados brutos de notificações de Dengue no Brasil em **direcionamentos analíticos e estratégicos**, respondendo a três perguntas essenciais de gestão: **Quando** os casos aceleram, **qual** o ritmo de crescimento e **onde** os recursos devem ser priorizados de forma preventiva.

O foco central desta análise está na **Maturidade de Negócio**: extrair insights claros e acionáveis utilizando manipulação eficiente de dados com Python (Pandas/Numpy) e visualizações limpas (Matplotlib/Seaborn), competências fundamentais para um Analista de Dados Júnior.

---

## 🎯 Perguntas de Negócio Respondidas
1. **Sazonalidade:** Em quais meses do ano ocorre a aceleração exponencial da doença e o ápice dos surtos?
2. **Evolução Temporal:** Qual o comportamento de crescimento ou queda da doença ao longo dos anos avaliados?
3. **Criticidade Regional:** Quais estados concentram o maior volume acumulado de notificações?

---

## 📊 Principais Insights e Visualizações

### 1. Análise de Sazonalidade (O "Quando")
Os dados históricos revelam um comportamento cíclico e altamente previsível. A aceleração das notificações começa a ganhar força no final do verão e atinge seu ápice absoluto no outono (entre abril e maio), período que sucede os meses de maior índice de chuvas acumuladas e altas temperaturas.

**💡 Decisão de Negócio:** Campanhas de conscientização e mutirões de eliminação de focos do *Aedes aegypti* não devem ser feitos de forma reativa no pico da doença. Os recursos e comunicações de rádio/TV precisam ser alocados de forma preventiva no início do ciclo de alta (fim do ano/janeiro).

![Análise de Sazonalidade](./gráfico%201.jpg)

---

### 2. Evolução Temporal dos Casos (O "Ritmo")
A análise da série anual demonstra instabilidade no volume total de notificações, apresentando anos de calmaria seguidos por explosões abruptas de contágio. Esse comportamento reforça a importância de um monitoramento contínuo e histórico de dados para detecção rápida de desvios.

**💡 Decisão de Negócio:** O crescimento percentual agressivo em determinados anos serve como um gatilho de alerta para que a cadeia de suprimentos farmacêuticos (testes rápidos, insumos hospitalares e medicamentos) ajuste seus estoques preventivamente com base no ritmo de aceleração inicial detectado.

![Evolução Temporal](./gráfico%202.png)

---

### 3. Ranking de Criticidade Regional (O "Onde")
Ao mapearmos o volume acumulado de casos por Unidade Federativa, a distribuição geográfica do problema fica nítida. O ranking aponta diretamente os estados federativos que demandam atenção imediata e contínua devido à densidade populacional e fatores climáticos favoráveis ao mosquito.

**💡 Decisão de Negócio:** Sabendo exatamente quais estados ocupam o topo do ranking, os gestores e os **exércitos de agentes de saúde** podem focar sua atuação de forma cirúrgica. Recursos públicos limitados geram maior impacto quando direcionados aos locais de maior criticidade, reduzindo custos operacionais e maximizando vidas salvas.

![Top Estados mais Afetados](./gráfico%203.png)

---

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Linguagem:** Python 3.9+
* **Manipulação de Dados:** `Pandas` e `Numpy` para limpeza, tratamento de valores ausentes e agregações temporais.
* **Visualização de Dados:** `Matplotlib` e `Seaborn` para geração de gráficos limpos, focados na interpretação executiva.
* **Ambiente de Desenvolvimento:** Google Colab.

---

## 📈 Conclusão Geral
Esta análise prova que a aplicação de técnicas de **EDA (Análise Exploratória de Dados)**, quando aliada a uma mentalidade voltada para a resolução de problemas reais, é suficiente para embasar decisões complexas na gestão pública ou privada. O projeto destaca competências essenciais de manipulação de dados, organização de código e, acima de tudo, **Storytelling**.

---

## 🚀 Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
