Monitoramento de Estoque com n8n e Google Sheets

Este workflow automatiza o controle de estoque utilizando o n8n integrado ao Google Sheets.
Sempre que a quantidade de um produto é atualizada na planilha principal, o fluxo verifica o valor e toma decisões automaticamente.

Como funciona

Quando um item fica abaixo do nível mínimo (ex.: menos de 5 unidades), ele é enviado para uma segunda planilha chamada Fornecedores, indicando necessidade de reposição.

Quando o estoque volta ao normal, o fluxo remove o produto da planilha de fornecedores.

Objetivo do projeto

Demonstrar lógica de automação, uso de gatilhos baseados em alterações de dados e integração entre serviços externos usando o n8n.

Tecnologias usadas

n8n

Google Sheets

Arquivo do fluxo

O arquivo JSON exportado do n8n está neste repositório e pode ser importado diretamente em qualquer instância do n8n.
