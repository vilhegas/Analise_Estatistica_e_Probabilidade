# Análise Estatística e Distribuições de Probabilidade

## Visão geral

Este projeto apresenta uma exploração prática dos fundamentos de probabilidade e das principais distribuições estatísticas utilizadas em análise de dados. Por meio de cálculos, simulações e visualizações em Python, o notebook demonstra como quantificar incertezas e interpretar padrões em diferentes cenários.

O material utiliza **dados ilustrativos e simulados**, com exemplos relacionados a comportamento de clientes, conversão de campanhas, volume de atendimentos e tempo de espera. Seu objetivo é demonstrar conceitos estatísticos, não construir um modelo preditivo em produção.

## Objetivos

- Calcular probabilidades simples, conjuntas, complementares e condicionais.
- Explorar a diferença entre eventos independentes e dependentes.
- Simular variáveis aleatórias discretas e contínuas.
- Visualizar e interpretar distribuições de probabilidade.
- Relacionar modelos probabilísticos a cenários de análise de dados.

## Tecnologias

- **Python** — implementação dos cálculos e simulações.
- **Pandas** — organização e análise tabular dos exemplos.
- **NumPy** — geração de amostras e operações numéricas.
- **SciPy** — funções de probabilidade e densidade estatística.
- **Matplotlib e Seaborn** — construção de gráficos.
- **Jupyter Notebook** — documentação e execução interativa das análises.

## Conteúdo desenvolvido

### Fundamentos de probabilidade

O notebook explora propriedades básicas da probabilidade, eventos certos e impossíveis, probabilidade complementar, multiplicação de probabilidades e probabilidade condicional.

**Exemplo: conversão após abertura de e-mail.** Um conjunto ilustrativo de dez registros de clientes é utilizado para estimar a probabilidade de compra condicionada à abertura de um e-mail promocional. Nesse exemplo, **60% dos clientes que abriram o e-mail realizaram uma compra**. Trata-se de uma demonstração com dados fictícios, não de um resultado de campanha real.

Também são simulados eventos independentes de abertura de e-mail e compra, usando amostragem binomial para comparar probabilidades individuais e a regra de multiplicação.

### Distribuições discretas

| Distribuição | Aplicação explorada |
|---|---|
| Uniforme discreta | Simulação de lançamentos de um dado de seis faces. |
| Binomial | Probabilidade de obter diferentes quantidades de sucessos em dez lançamentos de moeda. |
| Poisson | Modelagem da quantidade de chamadas recebidas por hora, com taxa média de quatro chamadas. |

### Distribuições contínuas

| Distribuição | Aplicação explorada |
|---|---|
| Normal | Simulação de valores distribuídos em torno de uma média e visualização por histograma. |
| Exponencial | Simulação de tempos de espera até o próximo evento. |
| t de Student | Comparação de curvas com diferentes graus de liberdade e com a distribuição normal. |

## Metodologia

1. Apresentação dos conceitos e das propriedades estatísticas.
2. Construção de exemplos com dados fictícios ou amostras simuladas.
3. Cálculo de probabilidades com operações em Python e funções do SciPy.
4. Visualização das distribuições com gráficos de barras, histogramas e curvas de densidade.
5. Interpretação das probabilidades e dos formatos das distribuições em contextos ilustrativos.

## Principais aprendizados

- A probabilidade condicional permite avaliar como a ocorrência de um evento altera a chance de outro.
- A hipótese de independência é fundamental para aplicar corretamente a regra de multiplicação.
- A escolha de uma distribuição depende da natureza da variável e das hipóteses sobre o fenômeno observado.
- Representações gráficas ajudam a compreender concentração, dispersão, assimetria e incerteza.
- A distribuição t de Student permite representar maior incerteza em análises de médias quando a variabilidade populacional é desconhecida.

## Como executar

1. Tenha Python e Jupyter Notebook ou JupyterLab disponíveis.
2. Instale as bibliotecas utilizadas:

   ```bash
   pip install numpy pandas scipy matplotlib seaborn notebook
   ```

3. Abra o notebook original (`Probabilidade.ipynb`) no Jupyter ou em um ambiente compatível.
4. Execute as células em sequência para reproduzir os cálculos e os gráficos.

> Algumas simulações utilizam amostragem aleatória sem uma semente fixa em todas as etapas. Por isso, frequências e gráficos podem apresentar pequenas variações entre execuções.
