# MVP Análise de Dados e Boas Práticas - PUC-RIO

Este projeto é o MVP desenvolvido para a pós-graduação lato-sensu da PUC-RIO, focado na sprint de **Análise de Dados e Boas Práticas**.

## 📋 Descrição do Projeto

O projeto realiza uma **análise exploratória de dados (EDA)** sobre rotatividade de funcionários (employee turnover/attrition) utilizando dados de recursos humanos. O objetivo principal é identificar padrões e fatores que influenciam o desligamento de funcionários em uma organização.

### 🎯 Objetivos

- Analisar e prever a rotatividade de funcionários com base em variáveis demográficas, profissionais e comportamentais
- Identificar os principais fatores que contribuem para o desligamento de funcionários
- Aplicar boas práticas de análise de dados e visualização
- Desenvolver insights acionáveis para gestão de recursos humanos

## 📊 Dados Utilizados

O projeto utiliza dois datasets principais:

### 1. HR Analytics Dataset (`HR_Analytics.csv`)
- **1.482 registros** de funcionários
- **38 variáveis** incluindo:
  - **Demográficas**: Idade, Gênero, Estado Civil, Educação
  - **Profissionais**: Departamento, Cargo, Nível hierárquico, Salário
  - **Comportamentais**: Satisfação no trabalho, Satisfação com o ambiente, Work-life balance
  - **Organizacionais**: Tempo na empresa, Tempo no cargo atual, Promoções
  - **Variável alvo**: Attrition (Sim/Não)

## 🔍 Metodologia

### Tipo de Problema
**Classificação supervisionada** - Dado um conjunto de características, o objetivo é prever se o funcionário irá deixar a empresa.

### Etapas da Análise

1. **Setup e Importação**
   - Importação das bibliotecas (pandas, numpy, matplotlib, seaborn, scipy)
   - Carga dos dados
   - Definição de funções auxiliares para análise

2. **Pré-processamento**
   - Limpeza de dados (remoção de duplicatas e valores nulos)
   - Exclusão de variáveis irrelevantes ou de baixa variabilidade
   - Tratamento de outliers

3. **Análise Exploratória**
   - **Análise Univariada**: Distribuição de cada variável individualmente
   - **Análise Bivariada**: Relacionamentos entre variáveis
   - **Análise de Correlação**: Identificação de associações numéricas
   - **Análise de Associação**: Relacionamentos entre variáveis categóricas

4. **Análise Comparativa com Variável Alvo**
   - Comparação de todas as variáveis com o status de desligamento
   - Identificação de padrões significativos

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas**: Manipulação e análise de dados
- **NumPy**: Computação numérica
- **Matplotlib & Seaborn**: Visualização de dados
- **SciPy**: Análises estatísticas

## 📁 Estrutura do Projeto

```
pucrio-mvp-analise-dados/
├── data/
│   └── HR_Analytics.csv          
├── MVP_Análise_de_Dados_e_Boas_Práticas.ipynb  
└── README.md                 
```

## 🚀 Como Executar

1. Clone o repositório
2. Instale as dependências Python necessárias:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
3. Abra o notebook `MVP_Análise_de_Dados_e_Boas_Práticas.ipynb` em um ambiente Jupyter
4. Execute as células sequencialmente

## 📝 Conclusões

O projeto demonstra a aplicação de boas práticas em análise de dados, incluindo:
- Limpeza e preparação adequada dos dados
- Análise exploratória sistemática
- Visualizações informativas
- Identificação de padrões relevantes para tomada de decisão

Os insights gerados podem ser utilizados para:
- Desenvolver estratégias de retenção de talentos
- Identificar funcionários em risco de desligamento
- Melhorar políticas de recursos humanos
- Otimizar processos organizacionais

---

**Desenvolvido para a Pós-graduação Lato-Sensu da PUC-RIO**  
*Sprint: Análise de Dados e Boas Práticas*
