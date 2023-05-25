# Automação Web(Buscador de Preços)
 [![NPM](https://img.shields.io/npm/l/react)](https://github.com/KingShinjo/AutomacaoWeb/blob/main/LICENSE) 
# Sobre o Projeto
- Este projeto consiste em um script automatizado para comparação de fornecedores e atualização de preços de insumos/produtos em uma planilha. O objetivo é buscar os sites dos fornecedores em busca de produtos disponíveis e seus respectivos preços. Caso algum produto esteja abaixo de um limite de preço definido pelo usuário, o script irá atualizar a planilha com os produtos mais baratos e, em seguida, enviar um e-mail com a lista dos produtos abaixo do preço máximo de compra.
# Objetivo
- Automatizar a comparação de fornecedores, atualizando uma planilha com os produtos mais baratos abaixo do preço máximo definido e enviando um e-mail com a lista desses produtos.

# Passo a Passo Detalhado do Código
- Importação da base de dados;
- Abrindo o navegador com o selenium;
- Definição das funções;
- Criação da Planilha de ofertas;
- Envio do Email com as ofertas.
# Bibliotecas Usadas:
- Pandas
- Time
- Selenium
# Base de Dados
- buscas.xlsx (Planilha onde devem ser preenchidas os produtos a serem pesquisados)
# Estrutura
- Python
