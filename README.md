# Previsão de Faixa Etária com Python
_Este é um projeto que foi resultado da disciplina "Computação Científica e Análise de Dados"._

## Visão geral
O projeto tem como objetivo informar ao usuário a faixa etária de uma pessoa com base em uma foto fornecida, que pode se encaixar em uma das quatro categorias: Criança, Adolescente, Adulto e Idoso.

## Funcionamento
Depois do carregamento das imagens no programa, é aplicado um filtro que realça as rugas da pessoa na foto (para melhorar a predição do modelo) e depois as imagens são transformadas em matrizes e linearizadas.
Após o pré-processamento, é utilizado o algoritmo de Regressão Logística Multinomial para classificar essas matrizes em uma das quatro categorias possíveis: Criança, Adolescente, Adulto e Idoso, e então
é utilizado o modelo treinado para prever em qual categoria uma nova imagem posteriormente fornecida se encaixa.

Para mais detalhes sobre o projeto, acesse o PDF explicativo no repositório ou o Jupyternotebook para visualização dos algoritmos e breve explicação sobre os mesmos.
