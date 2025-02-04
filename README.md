# Projeto de Análise e Previsão de Preços com Random Forest

Este projeto tem como objetivo analisar dados e prever preços de uma variável de interesse (como preços de imóveis, produtos, etc.) utilizando técnicas de aprendizado de máquina, especificamente o modelo `RandomForestRegressor`. O pré-processamento de dados inclui a aplicação de transformações logarítmicas e análise estatística.

## Requisitos

Para rodar este projeto, você precisa ter o Python 3 instalado em sua máquina. Além disso, é necessário instalar as bibliotecas requeridas para o funcionamento do código.

### Dependências

As bibliotecas necessárias para este projeto são:

- **geopy**: Para calcular distâncias geográficas.
- **scikit-learn**: Fornece algoritmos de aprendizado de máquina, como o `RandomForestRegressor`.
- **statsmodels**: Usada para análise estatística, como o teste de Kruskal-Wallis.
- **scipy**: Para cálculos científicos, incluindo métricas de erro e transformações.
- **nltk**: Para processamento de linguagem natural, como tokenização e análise de frequências.
- **pandas**: Para manipulação de dados e estruturas de dados (DataFrame).
- **numpy**: Biblioteca para cálculos numéricos e manipulação de arrays.
- **matplotlib**: Para visualizações de gráficos.
- **seaborn**: Complementa o `matplotlib` com gráficos estatísticos de alto nível.
- **pickle**: Para serializar e desserializar objetos Python (no caso, o modelo treinado).

### Como Instalar as Dependências

Para instalar as dependências do projeto, utilize o `pip` (gerenciador de pacotes do Python) para instalar as bibliotecas necessárias. Você pode instalar todas as dependências executando os seguintes comandos:

1. Instalar **geopy**:

    `pip install geopy`

2. Instalar **scikit-learn**:

    `pip install scikit-learn`

3. Instalar **statsmodels**:

    `pip install statsmodels`

4. Instalar **scipy**:

    `pip install scipy`

5. Instalar **nltk**:

    `pip install nltk`

6. Instalar **pandas**:

    `pip install pandas`

7. Instalar **numpy**:

    `pip install numpy`

8. Instalar **matplotlib**:

    `pip install matplotlib`

9. Instalar **seaborn**:

    `pip install seaborn`

10. Instalar **pickle**:

    O **pickle** já é uma biblioteca padrão do Python, então você não precisa instalá-la separadamente.

### Como Configurar o Ambiente

Recomendamos o uso de um ambiente virtual para evitar conflitos de versões. Se você não tem um ambiente virtual configurado, siga os passos abaixo:

1. Crie um ambiente virtual no seu diretório de trabalho:

   `python -m venv venv`

2. Ative o ambiente virtual:

   - No **Windows**: `venv\Scripts\activate`
   - No **Linux/Mac**: `source venv/bin/activate`

3. Após ativar o ambiente virtual, instale as dependências conforme mencionado acima.
