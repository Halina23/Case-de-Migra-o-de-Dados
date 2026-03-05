# Validação e Análise de Dados de Vendas

Este projeto demonstra um **case de validação e análise de dados** utilizando Python, Excel e PostgreSQL.  
O objetivo é garantir **integridade e consistência** dos dados de pedidos e faturamento, além de identificar divergências e perdas de receita.

## Conteúdo do projeto

- `Relatório de Compras.excel.csv` – CSV de exemplo com dados de vendas  
- `analise_faturamento.py` – Script Python que realiza leitura, limpeza, transformação e agregação dos dados  
- Gráficos gerados:  
  - Faturamento por estado (barras horizontais)  
  - Proporção de pedidos pagos vs cancelados (pizza)  

## Funcionalidades

- Detecção automática de colunas principais (estado, valor, status)  
- Conversão de valores monetários para formato numérico  
- Mapeamento e padronização de status de pedidos  
- Cálculo de faturamento total e real  
- Geração de gráficos claros para análise visual  
