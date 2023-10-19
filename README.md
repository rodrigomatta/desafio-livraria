# desafio-livraria
Sistema de Livraria com base em prompt para estudos de linguagem.

# Principais requisitos do sistema:
- Arquivo JSON como base dos dados.
- Classe Livro com seus atributos: id, titulo, popularidade, autor, preço e favoritos.
- Mostrar livros por ordem: alfabética, preço, autor, popularidade e favoritos.
- Adicionar e remover livros da sacola.
- Adicionar ou remover favoritos.
- Calcular preço final dos itens com: quantidade de itens, preço e os itens.
- Adicionar lista de favoritos na sacola.
- Perguntar de deseja finalizar o pedido antes de fechar a sacola.

# Arquivos de execução:
- livraria.json -> comtém os dados dos livros.
- classLivraria -> Comtém a classe livrária.
- classSacola -> comtém a classe sacola.
- listarLivros -> comtém uma função com um switch case para listar os livros em vários formatos.
- mainLivraria -> arquivo principal de execução que chama os demais. 

# Execução:
```bash
dart run mainLivraria.dart
```