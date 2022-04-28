# Projeto - Automação Web
Projeto de Web Scraping - realizado pelo curso Python Impressionador

O projeto consiste em fazer pesquisas no google shopping e no site buscapé buscando produtos cadastrados em uma planilha do excel, que contém o nome do produto, um preço mínimo e máximo e palavras banidas (separadas por espaços). O script então acha esses resultados fazendo os devidos filtros e realiza duas operações:

- Cria uma nova planilha do excel com todos os produtos encontrados, contendo o nome dos produtos, preço e link para compra.
- Envia um email com todas essas informações

Foi adicionado também a funcionalidade de realizar todas essas operações em segundo plano através do selenium, o que significa que o projeto pode ser usado em um computador enquanto o usuário o utiliza normalmente.

