# Análise de casos totais de COVID-19 nos EUA
🚧 Em construção 🚧

Este repositório contém um projeto de aprendizagem inicial focado na análise de dados dos casos totais de COVID-19 nos Estados Unidos. O objetivo é explorar e visualizar os dados para obter insights significativos e visualização de gráficos. Para tal, foi-se utilizado o Google Colab, ambiente de desenvolvimento e execução no navegador sem que seja necessário instalar nada previamente. Abaixo segue um pequeno tutorial caso deseje executar localmente em seu IDE:

## Ambiente virtual
Durante este, foi-se criado um ambiente virtual, o que garante o desenvolvimento estável e consistente sem interferir em outros projetos ou no ambiente global, neste caso, do Python. **É importante que esse passo seja feito antes mesmo da instalação de qualquer biblioteca! Para que o mesmo seja usado no próprio ambiente** Para criá-lo e ativá-lo, execute os seguintes comandos:

```
$ python -m venv venv

$ venv\Scripts\Activate
```

## Ferramentas 
A linguagem para a análise em questão é o **[Python](https://docs.python.org/pt-br/3/tutorial/)**:

### Dataset
•  O dataset utilizado foi retirado do [Kaggle](https://www.kaggle.com/), uma plataforma de banco de datasets públicos.

### Bibliotecas utilizadas
•  [**Pandas**](https://pandas.pydata.org/docs/getting_started/index.html#getting-started): Utilizada para manipulação e análise de dados.

•  [**Matplotlib**](https://matplotlib.org/stable/index.html): Utilizada para criação de gráficos estáticos.

•  [**Seaborn**](https://seaborn.pydata.org/tutorial.html): Utilizada para visualização de dados baseada em Matplotlib, com gráficos mais atraentes e informativos.

Para instalá-los, basta seguir os passos abaixo com o uso de um pacote de instalação chamado 'pip' no terminal do Windows:

```
$ pip install pandas matplotlib seaborn 
```
### Importação das bibliotecas
Para importá-las, basta adicionar o seguinte trecho de código em seu arquivo .py:

```
import numpy as np
import pandas as pd
import warnings
from matplotlib import pyplot as plt
import seaborn as sns
```

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.
