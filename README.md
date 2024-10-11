# IMD-Backend-SEMANA4-1-2-
Atividade de criação de servidor usando node.js

Crie um servidor web com auxílio do Express a partir do que você aprendeu nas Aulas 04 e 05. O programa deve implementar uma API para cadastro e consulta de produtos, conforme detalhamento a seguir.

A partir do resultado da atividade anterior da Aula 04 (https://abre.ai/lcU3), incremente sua API adicionando os seguintes aspectos:

Adicione validação a partir da biblioteca Ajv (https://ajv.js.org/guide/gettingstarted.html)
a. Os produtos devem possuir os campos nome, descrição e preço.
b. Os campos “nome” e “descrição” devem ser textuais.
c. O campo preço deve ser numérico
d. O campos nome e preço são de cadastro obrigatório
As validações devem ser implementadas como um middleware do Express
Utilize o conceito de Router do Express para separar as rotas dos produtos em um arquivo dedicado.
