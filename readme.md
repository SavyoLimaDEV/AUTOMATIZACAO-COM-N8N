
# Automação de Convergência de Dados via Excel e API

## Descrição

Este projeto realiza a **automação da captura e integração de dados** a partir de uma planilha Excel utilizando **n8n**. Ele lê informações da tabela primária, envia requisições a uma **API externa** e consolida os resultados em uma **tabela de saída detalhada**, permitindo análises precisas e rápidas.

O fluxo geral da automação é:

1. Ler os dados da tabela primária no Excel.  
2. Para cada linha, realizar requisições HTTP à API com os parâmetros específicos.  
3. Receber e tratar os dados retornados pela API.  
4. Consolidar os resultados em uma **tabela secundária**, incluindo detalhes adicionais e informações de status.  


Essa automação foi desenvolvida no **n8n**, permitindo integração visual, criação de workflows e manipulação de dados de forma eficiente, usando **JavaScript** para transformações personalizadas quando necessário.

Esta automação no n8n permite atualizar e processar os dados simplesmente substituindo ou editando as tabelas de entrada, integrando automaticamente com a API e gerando a tabela de saída consolidada.

Além disso, o projeto contém:

- **Prints do workflow do n8n** mostrando a lógica da automação.  
- **Documentação detalhada** explicando cada parte do projeto e fluxo de dados.


## Tecnologias Utilizadas

| Tecnologia       | Finalidade                                                                 |
|------------------|----------------------------------------------------------------------------|
| n8n              | Plataforma de automação e integração de workflows                          |
| JavaScript       | Transformações e manipulação de dados dentro do n8n                        |
| Excel / XLSX     | Tabela primária de entrada e tabela de saída                               |
| HTTP Request     | Realiza chamadas à API externa e captura de dados                          |
| Git              | Controle de versão do projeto                                              |
