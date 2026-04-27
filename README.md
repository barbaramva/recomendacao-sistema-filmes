# 🎬 Sistema de Recomendação de Filmes

Este projeto foi desenvolvido como parte dos meus estudos no curso de Matemática e Estatística Aplicada para Data Science, Machine Learning e IA da DSA.

Imagine que você precise construir um sistema de recomendação de filmes. Cada vez que um usuário assiste a um título, o sistema deve sugerir outros semelhantes, com o objetivo de manter o usuário engajado, assim como acontece em plataformas de streaming e redes sociais.

Neste projeto, desenvolvi um sistema de recomendação seguindo essa ideia. Utilizei dados reais disponíveis publicamente e analisei características como elenco, diretor e descrição para encontrar conteúdos parecidos. Para isso, usei uma medida matemática chamada cosine similarity, que ajuda a identificar o quão semelhantes os filmes são.

## O que o projeto faz
Dado um filme como entrada, o sistema retorna uma lista de filmes semelhantes.

## Como eu fiz
- Utilizei dados de filmes (dataset TMDB)
- Fiz o tratamento e limpeza dos dados
- Separei informações importantes como atores e diretor
- Juntei essas informações em uma única coluna
- Transformei os textos em números (vetores)
- Comparei os filmes usando similaridade (cosine similarity)

## Tecnologias utilizadas
- Python
- Pandas
- Scikit-learn

## Arquivo principal
- `Projeto.ipynb`

## O que aprendi com esse projeto
- Trabalhar com dados reais
- Fazer pré-processamento de dados
- Aplicar conceitos básicos de NLP
- Entender como funcionam sistemas de recomendação

## Este projeto faz parte da minha formação em Ciência de Dados.
