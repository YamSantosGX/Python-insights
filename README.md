# Python Insights - Análise de Cancelamento de Clientes

**Autor:** Yam Santos  
**Data:** Julho 2025

## 📊 Sobre o Projeto

Este projeto foi desenvolvido para analisar os dados de cancelamento de clientes de uma empresa com mais de 800 mil clientes. O objetivo principal é identificar os principais motivos dos cancelamentos e propor ações eficientes para reduzir essa taxa.

## 🎯 Problema de Negócio

A empresa identificou que a maioria de sua base de clientes são inativos (cancelaram o serviço). Este projeto visa:

- Entender os principais motivos dos cancelamentos
- Identificar padrões nos dados dos clientes que cancelaram
- Propor ações estratégicas para reduzir a taxa de cancelamento
- Melhorar a retenção de clientes e os resultados da empresa

## 📂 Estrutura do Projeto

```
Segundo Projeto Python/
├── README.md                    # Este arquivo
├── inicial.ipynb              # Notebook principal com as análises
├── cancelamentos.csv          # Base de dados completa
├── cancelamentos_sample.csv   # Amostra dos dados para testes
└── .venv/                     # Ambiente virtual Python
```

## 📋 Dataset

O dataset contém informações detalhadas sobre os clientes, incluindo:

| Coluna | Descrição |
|--------|-----------|
| `CustomerID` | ID único do cliente |
| `idade` | Idade do cliente |
| `sexo` | Gênero do cliente (Male/Female) |
| `tempo_como_cliente` | Tempo em meses como cliente |
| `frequencia_uso` | Frequência de uso do serviço |
| `ligacoes_callcenter` | Número de ligações para o call center |
| `dias_atraso` | Dias de atraso no pagamento |
| `assinatura` | Tipo de assinatura (Basic/Standard/Premium) |
| `duracao_contrato` | Duração do contrato (Monthly/Quarterly/Annual) |
| `total_gasto` | Total gasto pelo cliente |
| `meses_ultima_interacao` | Meses desde a última interação |
| `cancelou` | Variável target (0 = Não cancelou, 1 = Cancelou) |

**Total de registros:** ~50.000 clientes na amostra

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** - Manipulação e análise de dados
- **Jupyter Notebook** - Ambiente de desenvolvimento
- **Matplotlib/Seaborn** - Visualização de dados (planejado)
- **Plotly** - Gráficos interativos (planejado)

## 🚀 Como Executar

### Pré-requisitos

- Python 3.x instalado
- Jupyter Notebook ou VS Code com extensão Python

### Instalação

1. Clone ou faça download do projeto
2. Navegue até o diretório do projeto
3. Ative o ambiente virtual (se disponível):
   ```bash
   .venv\Scripts\activate  # Windows
   ```
4. Instale as dependências:
   ```bash
   pip install pandas jupyter matplotlib seaborn plotly
   ```

### Execução

1. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook inicial.ipynb
   ```
   
   Ou abra diretamente no VS Code.

2. Execute as células sequencialmente para reproduzir a análise.

## 📈 Análises Realizadas

### 1. Exploração Inicial dos Dados
- Carregamento e limpeza dos dados
- Remoção da coluna `CustomerID` (não relevante para análise)
- Visualização da estrutura do dataset

### 2. Análises Planejadas
- [ ] Análise descritiva das variáveis
- [ ] Identificação de valores faltantes
- [ ] Análise da distribuição da variável target (cancelou)
- [ ] Correlação entre variáveis
- [ ] Segmentação de clientes
- [ ] Identificação de padrões nos cancelamentos
- [ ] Visualizações interativas

## 🔍 Principais Insights (Em Desenvolvimento)

*Esta seção será atualizada conforme as análises forem concluídas.*

## 📊 Visualizações

*Gráficos e visualizações serão adicionados conforme o desenvolvimento do projeto.*

## ✅ Conclusões e Recomendações

*As conclusões e recomendações estratégicas serão documentadas após a conclusão das análises.*

## 🤝 Contribuições

Este é um projeto de análise pessoal desenvolvido por Yam Santos. Sugestões e feedback são bem-vindos!

## 📄 Licença

Este projeto é de uso educacional e para portfólio pessoal.

---

⭐ **Status do Projeto:** Em Desenvolvimento  
🔄 **Última Atualização:** Julho 2025
