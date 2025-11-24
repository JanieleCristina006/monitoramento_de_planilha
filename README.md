Monitoramento de Estoque com n8n e Google Sheets

Este projeto utiliza o n8n integrado ao Google Sheets para automatizar o controle de estoque.
O fluxo acompanha alterações na planilha principal e toma decisões automaticamente com base na quantidade disponível de cada produto.

Como funciona

Quando a quantidade de um item fica abaixo do limite mínimo (ex.: menos de 5 unidades), o fluxo adiciona esse produto à planilha Fornecedores, indicando necessidade de reposição.

Quando o estoque volta ao normal, o item é removido automaticamente da planilha de fornecedores.

Todo o processo ocorre em tempo real após qualquer atualização manual ou automatizada na planilha principal.

Objetivo do projeto

Demonstrar:

Lógica de automação usando o n8n

Uso de gatilhos baseados em alterações de dados

Integração entre serviços externos

Manipulação dinâmica de planilhas no Google Sheets

Tecnologias usadas

n8n

Google Sheets

Arquivo do fluxo

O arquivo JSON exportado do n8n está neste repositório e pode ser importado diretamente em qualquer instância do n8n para replicação do workflow.
