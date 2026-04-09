# 📈 Análise de Negócio

> Projeto desenvolvido durante o **Sprint 8** do bootcamp [TripleTen](https://tripleten.com/), com foco em análise de métricas de negócio, comportamento de usuários e performance de marketing para embasar decisões estratégicas.

---

## 📌 Sobre o Projeto

Este projeto aplica técnicas de análise de negócio sobre dados reais de uma empresa, explorando métricas essenciais como aquisição de usuários, receita, retenção e eficiência de marketing. O objetivo é transformar dados brutos em insights acionáveis que suportem a tomada de decisão por gestores e times de produto.

---

## 🎯 Objetivos

- Calcular e interpretar **KPIs** de negócio (DAU, WAU, MAU, LTV, CAC, ROI)
- Realizar **análise de coorte** para entender retenção e comportamento ao longo do tempo
- Mapear o **funil de vendas** e identificar gargalos de conversão
- Calcular **economia unitária** (LTV vs CAC) por canal de aquisição
- Avaliar a **eficiência das campanhas de marketing** por fonte de tráfego
- Identificar os canais mais rentáveis e recomendar alocação de orçamento

---

## 🗂️ Estrutura do Repositório

```
📁 Analise-de-Negocio/
│
├── 📓 sprint 8 - tripleten.ipynb   # Notebook principal com toda a análise
└── 📄 README.md                    # Documentação do projeto
```

---

## 🔍 Etapas da Análise

### 1. Preparação dos Dados
- Carregamento e limpeza dos datasets (visitas, pedidos, custos)
- Tratamento de tipos de dados e valores ausentes
- Criação de variáveis auxiliares (coortes, sessões, períodos)

### 2. Métricas de Uso e Engajamento
- Cálculo de **DAU / WAU / MAU** (usuários ativos diários, semanais e mensais)
- Análise de **sessões por usuário** e **duração média das sessões**
- Identificação de sazonalidade e picos de acesso

### 3. Análise de Coorte
- Agrupamento de usuários por data de primeira visita
- Cálculo da **taxa de retenção** mês a mês por coorte
- Visualização do mapa de calor de retenção

### 4. Análise de Marketing
- Distribuição dos custos por **canal de aquisição** (source)
- Cálculo do **CAC** (Custo de Aquisição de Cliente) por fonte
- Avaliação do **ROI** de cada canal ao longo do tempo

### 5. Funil de Vendas e Receita
- Mapeamento das etapas: visita → pedido → receita
- Cálculo do **tempo até a primeira compra**
- Análise do **ticket médio** e frequência de compra

### 6. Economia Unitária
- Cálculo do **LTV** (Lifetime Value) por coorte e canal
- Comparação **LTV vs CAC** para avaliar rentabilidade
- Identificação do **payback period** por fonte de aquisição

### 7. Conclusões e Recomendações
- Ranking dos canais mais eficientes
- Sugestões de realocação de investimento em marketing
- Insights sobre o comportamento de usuários de alto valor

---

## 🛠️ Tecnologias Utilizadas

| Ferramenta | Finalidade |
|---|---|
| Python 3 | Linguagem principal |
| Pandas | Manipulação e análise de dados |
| NumPy | Cálculos numéricos e estatísticos |
| Matplotlib | Visualização de dados |
| Seaborn | Gráficos estatísticos e mapas de calor |
| Jupyter Notebook | Ambiente de desenvolvimento interativo |

---

## ▶️ Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/caguiar0/Analise-de-Negocio.git
```

2. Acesse a pasta do projeto:
```bash
cd Analise-de-Negocio
```

3. Instale as dependências:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Inicie o Jupyter Notebook:
```bash
jupyter notebook
```

5. Abra o arquivo `sprint 8 - tripleten.ipynb` e execute as células sequencialmente.

---

## 📊 Principais Métricas Analisadas

| Métrica | Descrição |
|---|---|
| **DAU / WAU / MAU** | Usuários ativos por período |
| **CAC** | Custo médio para adquirir um cliente |
| **LTV** | Receita total gerada por um cliente ao longo do tempo |
| **ROI** | Retorno sobre o investimento em marketing |
| **Retenção** | % de usuários que retornam após o primeiro uso |
| **Payback Period** | Tempo para recuperar o custo de aquisição |

---

## 💡 Principais Conclusões

> ⚠️ *Preencha esta seção com os insights reais obtidos no seu notebook, como:*
> - Qual canal de marketing apresentou melhor ROI
> - Qual coorte teve maior taxa de retenção
> - Qual o tempo médio de payback por fonte de aquisição
> - Recomendações de investimento baseadas na análise

---

## 👤 Autor

**caguiar0**  
Projeto desenvolvido como parte do currículo de Análise de Dados da [TripleTen](https://tripleten.com/).

---

## 📄 Licença

Este projeto é de uso educacional e está disponível para fins de estudo e portfólio.
