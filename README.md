# Sistema de Recomendação de Filmes

Este é um mini projeto de um sistema de recomendação de filmes baseado em similaridade de texto usando Python e bibliotecas como pandas, numpy e scikit-learn.

## Descrição

O objetivo deste projeto é recomendar filmes semelhantes com base nos resumos dos filmes. Ele usa técnicas de Processamento de Linguagem Natural (NLP) para analisar os resumos dos filmes e calcula a similaridade entre eles usando a medida de similaridade de cosseno.

## Funcionalidades

- Leitura e pré-processamento de dados de filmes.
- Criação de uma matriz TF-IDF para representar os resumos dos filmes.
- Cálculo do núcleo sigmoidal entre os resumos dos filmes.
- Implementação de um sistema de recomendação que retorna os 10 filmes mais similares a um filme escolhido.

## Como Usar

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter instalado as bibliotecas necessárias listadas no arquivo `requirements.txt`.
3. Execute o script Python `recommender_system.py`.
4. Escolha um filme para receber recomendações e insira o título quando solicitado.
5. O sistema retornará os 10 filmes mais similares ao filme escolhido.

## Dados Utilizados

Os dados utilizados neste projeto foram obtidos do [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset) no Kaggle, que contém informações sobre milhares de filmes, incluindo títulos, resumos, gêneros e muito mais.

## Autores

- [Leda Mafia](https://github.com/ledamafia) - Desenvolvedor principal

## Licença

Este projeto é distribuído sob a licença [MIT](https://opensource.org/licenses/MIT). Consulte o arquivo `LICENSE` para obter mais informações.

