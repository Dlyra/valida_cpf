# Função valida CPF

O  **CPF (Cadastro de Pessoas Físicas)**, emitido pela Receita Federal, é caracterizado por uma função entre o conjunto das pessoas físicas cadastradas e o conjunto dos documentos emitidos.

Ou seja, o fato de um número de CPF ser autenticado pelos seus dígitos verificadores, não o torna um CPF válido, pois é necessário que ele esteja cadastrado no banco de dados da Receita Federal.

Assim, um número válido de CPF nem sempre será um documento já emitido. Porém,  **os dígitos verificadores servem para alertar que o número foi escrito de forma inadequada**, sem precisar acessar o banco de dados da Receita Federal.

## Informações Gerais

Utilizando o cálculo validador do dígito verificador, a função desenvolvida propõe como solução validar e identificar se o número de CPF informado se possui um formato válido ou não.  

Desenvolver e testar uma função que valide se um número de CPF é válido.  Você encontrará as regras práticas do cálculo validador descritas passo a passo no notebook.

Condições:
-   Deve conter 11 dígitos.
-   Deve ser uma entrada de dígitos exclusivamente, sem texto.
-   Os números não podem ser todos repetidos.
-   Os dígitos devem ser calculados corretamente, pelo cálculo oficial.

## Requisitos

Python 3.x
Jupyter Lab ou Notebook
