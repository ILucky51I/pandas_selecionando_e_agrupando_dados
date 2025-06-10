# Análise de Emissões de Gases de Efeito Estufa no Brasil

## Descrição do Projeto

Este projeto utiliza a biblioteca **Pandas** para analisar dados de emissões de gases de efeito estufa no território brasileiro, extraídos do **SEEG** (Sistema de Estimativa de Emissões e Remoções de Gases de Efeito Estufa).

## Principais Técnicas e Aprendizados

### Manipulação de Dados

- Importação de Dados  
- Transformação de Dados

### Análise de Dados

- Seleção e Filtragem  
- Agregação de Dados

### Visualização

- Leitura de arquivos Excel usando `pd.read_excel()`  
- Seleção de abas específicas  
- Configuração de cabeçalhos e rodapés  
- Conversão de formato *wide* para *long* com `melt()`  
- Remoção de colunas com `drop()`  
- Criação de tabelas *pivot* com `pivot_table()`  
- Encontrar valores únicos com `unique()`  
- Filtrar dados com seleção booleana  
- Seleção de índices com `xs()`  
- Agrupamento com `groupby()`  
- Métodos de agregação: `sum()`, `mean()`, `max()`, `idxmax()`  
- Agrupamento por múltiplas colunas  
- Criação de gráficos de barras com `plot()`  
- Múltiplos *subplots* com `subplots=True`  
- Visualização de séries temporais  

## Principais Insights

- Análise da emissão de gases de efeito estufa por:
  - Tipo de gás  
  - Setor econômico  
  - Estado  
  - Evolução temporal  

## Tecnologias Utilizadas

- Python  
- Pandas  
- Matplotlib  

## Como Usar

1. Clone o repositório  
2. Instale as dependências:  
   ```bash
   pip install pandas matplotlib
3. Execute os scripts Jupyter Notebook
