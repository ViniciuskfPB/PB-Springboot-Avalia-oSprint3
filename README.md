# ViniciuskfPB-PB-Springboot-Avalia-oSprint3

1 – Desenvolva uma API REST com os seguintes endpoints:
• POST - /api/states
• GET - /api/states
• GET - /api/states/{id}
• PUT - /api/states/{id}
• DELETE - /api/states/{id}
A estrutura do objeto é a seguinte:
{
"id": "1",
"nome": "Rio Grande do Norte",
"regiao": "Nordeste",
"populacao": 3409000,
"capital": "Natal",
"area": 52.797
}
O id é a chave primaria e deve ser gerado automaticamente.
O campo região só deve aceitar 5 valores: Norte, Nordeste, Sul, Sudeste e Centro-Oeste. Se for
colocado um valor diferente desses 5, não deve permitir o cadastro.
O endpoint GET - /api/states, deve possuir os seguintes filtros:
• Filtrar os estados por região
• Ordenar os estados com maior população
• Ordenar os estados com a maior área
2 – Faça o swagger da API desenvolvida na questão 1.
Obs.: Na primeira questão usar o banco de dados H2 e na segunda questão não deve ser utilizado
o springfox e sim deve ser criado o arquivo yaml do zero, seguindo as especificações da
OpenAPI.
Link da Documentação da OpenApi: https://swagger.io/specification/
