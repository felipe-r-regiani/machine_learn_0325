# machine_learn_0325

Este repositório apresenta a aplicação de modelos de **Regressão Linear Múltipla** para a predição de preços de imóveis utilizando o dataset de King County. O foco principal é a implementação e o entendimento da **Equação Normal** através de operações de álgebra linear.

## 📂 Conteúdo

* **kc_house_data.csv**: Base de dados contendo características de imóveis como preço, número de quartos, banheiros e área construída (sqft_living).
* **regressao_multipla.ipynb**: Notebook contendo a implementação passo a passo da Regressão Múltipla. O projeto demonstra como encontrar os coeficientes ótimos ($\\beta$) utilizando a fórmula matricial $\\beta = (X^T X)^{-1} X^T y$, realizando o teste de previsão para validar o modelo.

## 🛠️ Tecnologias e Bibliotecas

As ferramentas centrais utilizadas neste projeto são:

* **Python 3**: Linguagem de programação principal.
* **NumPy**: Biblioteca fundamental para a criação da matriz de características, transposição, inversão e multiplicação matricial (operador `@`).
* **Pandas**: Utilizado para o carregamento e exploração inicial do dataset.
* **Jupyter Notebook**: Ambiente interativo para documentação e execução do código.

## 🚀 Como começar

1.  Clone este repositório:
    ```bash
    git clone https://github.com/felipe-r-regiani/machine_learn_0325.git
    ```
2.  Instale as dependências:
    ```bash
    pip install numpy pandas
    ```
3.  Execute o notebook:
    - Abra o ficheiro `regressao_multipla.ipynb`.
    - Explore os coeficientes descobertos para cada característica do imóvel (quartos, banheiros, área) e veja a previsão final baseada na combinação desses fatores.
