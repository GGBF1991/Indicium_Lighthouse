# README - Indicium_Lighthouse
 Desafio Cientista de Dados - Indicium

## Resumo
Este projeto é parte de um desafio proposto pela Indicium, no qual o objetivo é testar os conhecimentos dos candidatos sobre a resolução de problemas de negócios, análise de dados e aplicação de modelos preditivos. O desafio envolve uma plataforma de aluguéis temporários na cidade de Nova York, para a qual é necessário realizar uma análise exploratória dos dados de um concorrente e validar um modelo preditivo de precificação.

## Instalação

1. Clone o repositório do projeto para o seu ambiente local:

git clone https://github.com/GGBF1991/Indicium_Lighthouse.git

2. Navegue até o diretório do projeto:

cd indiciun_project

3. Se necessário, instale as demais dependências do projeto listadas no arquivo `requisitos.txt`.

4. Após instalar as dependências, você estará pronto para executar o projeto.

## Execução

Este projeto é composto por um notebook Jupyter intitulado `INDICIUM.ipynb`. Você pode executar o notebook utilizando o Jupyter Notebook, JupyterLab ou o Google Colab. 

Execute o notebook seguindo as instruções a seguir:

1. Inicie o servidor Jupyter Notebook.

2. No navegador, acesse o link gerado pelo servidor para abrir o notebook `INDICIUM.ipynb`.

3. Siga as instruções do notebook para explorar os dados, implementar modelos de Machine Learning e realizar previsões de preços para novos anúncios.

## Utilização do Notebook

A primeira parte do notebook `INDICIUM.ipynb` trata da exploração de dados e da implementação dos modelos de Machine Learning.

A parte final do notebook, a partir de ">>>>>>> Testando o modelo em novos anúncios <<<<<<<<", deve ser utilizada para a predição de preços de novos anúncios. Para isso, siga as instruções abaixo:

1. Execute a primeira célula que carrega o modelo e os scalers.

2. Na célula seguinte, preencha as informações do novo anúncio nos campos entre colchetes, conforme o exemplo abaixo:

imovel = pd.DataFrame({
    'id': [2595],
    'nome': ['Skylit Midtown Castle'],
    'host_id': [2845],
    'host_name': ['Jennifer'],
    'bairro_group': ['Manhattan'],
    'bairro': ['Midtown'],
    'latitude': [40.75362],
    'longitude': [-73.98377],
    'room_type': ['Entire home/apt'],
    'price': [225],
    'minimo_noites': [1],
    'numero_de_reviews': [45],
    'ultima_review': ['2019-05-21'],
    'reviews_por_mes': [0.38],
    'calculado_host_listings_count': [2],
    'disponibilidade_365': [355]
})

3. Execute a célula com as informações do novo anúncio e a célula seguinte com a função para preparar esses dados.
4. Execute a última célula que chama a função predict_price e imprime o valor da predição para os dados informados.

Autor: Gabriel G. B. Ferri
