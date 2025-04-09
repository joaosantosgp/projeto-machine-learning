# Previsão de Preços de Pizza por Diâmetro

Este projeto utiliza técnicas de Machine Learning com Python para prever o preço de uma pizza com base no seu diâmetro. A aplicação web interativa é construída com Streamlit, a manipulação e análise de dados são feitas com Pandas, e o modelo de regressão é implementado com a biblioteca Scikit-learn (sklearn).

## Visão Geral

O objetivo principal deste projeto é criar um modelo preditivo simples que possa estimar o preço de uma pizza dado o seu diâmetro. Isso pode ser útil para consumidores que desejam ter uma ideia do preço justo de uma pizza ou para estabelecimentos que desejam precificar seus produtos de forma competitiva.

## Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **Streamlit:** Framework Python para criar aplicativos web interativos de forma rápida e fácil.
* **Pandas:** Biblioteca para manipulação e análise de dados, fornecendo estruturas de dados como DataFrames.
* **Scikit-learn (sklearn):** Biblioteca abrangente para machine learning em Python, contendo algoritmos para classificação, regressão, clustering, redução de dimensionalidade, seleção de modelos e pré-processamento.

## Funcionalidades

* **Interface Interativa:** Uma interface web simples e intuitiva construída com Streamlit permite aos usuários inserir o diâmetro da pizza.
* **Previsão em Tempo Real:** O modelo de machine learning realiza a previsão do preço da pizza com base no diâmetro fornecido.
* **Visualização (Opcional):** Poderá incluir visualizações simples dos dados de treinamento e da reta de regressão para melhor compreensão.

## Como Executar o Projeto

Para executar este projeto localmente, siga os passos abaixo:

1.  **Certifique-se de ter o Python instalado em seu sistema.** Você pode verificar sua instalação abrindo o terminal ou prompt de comando e digitando:
    ```bash
    python --version
    ```
    Se o Python não estiver instalado, você pode baixá-lo em [https://www.python.org/downloads/](https://www.python.org/downloads/).

2.  **Clone o repositório (se aplicável).** Se o código estiver em um repositório Git, clone-o para sua máquina local (Crie uma pasta, acesse ela pelo terminal, cole o codigo abaixo.):
    ```bash
    git clone https://github.com/joaosantosgp/projeto-machine-learning.git .
    ```

3.  **Instale as dependências.** Utilize o pip (gerenciador de pacotes do Python) para instalar as bibliotecas necessárias listadas no arquivo `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Execute a aplicação Streamlit.** Navegue até o diretório do projeto no seu terminal ou prompt de comando e execute o seguinte comando:
    ```bash
    streamlit run app.py
    ```

5.  **Acesse a aplicação no seu navegador.** O Streamlit irá automaticamente abrir uma nova aba no seu navegador com a aplicação rodando (geralmente em `http://localhost:8501`).

