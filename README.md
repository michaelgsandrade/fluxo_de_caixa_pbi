# Inteligência Financeira: Dashboard de Fluxo de Caixa

![Interface do Dashboard](https://github.com/michaelgsandrade/fluxo_de_caixa_pbi/blob/main/Print%20-%20Fluxo%20de%20caixa.png?raw=true)
[Faça o download do arquivo aqui](https://github.com/michaelgsandrade/fluxo_de_caixa_pbi/raw/refs/heads/main/Fluxo%20de%20Caixa.pbix)

## Visão Geral do Projeto
Este projeto consiste no desenvolvimento de uma solução de Business Intelligence para o controle e monitoramento do fluxo de caixa empresarial. O objetivo central foi consolidar dados de movimentações financeiras em uma visão executiva que permita o acompanhamento da liquidez e a saúde operacional da empresa em tempo real.

## Desenvolvimento Técnico

### 1. Extração e Tratamento de Dados (ETL)
A base de dados original foi estruturada em arquivos Excel, contendo o histórico de transações e categorias de despesas. O processamento foi realizado via Power Query, envolvendo:
* **Limpeza e Tipagem:** Padronização de campos monetários e temporais para garantir a integridade dos cálculos.
* **Normalização:** Organização das categorias de despesas e centros de custo para permitir análises dinâmicas.

### 2. Modelagem e Inteligência (DAX)
A arquitetura do modelo foi desenhada para suportar análises granulares e cruzamento de dimensões:
* **Dimensionalidade:** O modelo permite filtrar a performance financeira por Centro de Custo (Marketing, Operacional, Administrativo, entre outros) e Localidade (unidades como São Paulo e Porto Alegre).
* **Medidas Avançadas:** Implementação de cálculos em DAX para monitorar indicadores críticos, como Saldo Acumulado, Variação Mensal e Margem de Lucro.

## Indicadores de Performance (KPIs)
O dashboard apresenta os números consolidados do período, facilitando a tomada de decisão estratégica:
* **Liquidez e Operação:** Monitoramento de R$ 3.915.064 em entradas totais e R$ 2.059.117 em despesas.
* **Saldo Final:** O caixa encerrou o período analisado com um saldo de R$ 1.855.947.
* **Rentabilidade:** Identificação de uma margem de lucro operacional de 47,41%, métrica essencial para validar a eficiência do
