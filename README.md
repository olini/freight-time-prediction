# freight-time-prediction
> Este projeto foi desenvolvido na disciplina de Introdução à Ciência de Dados no Programa de Especialização em Software da Embraer em parceria com o CIn-UFPE, realizado em 2023

Repositório com análises de dados de e-commerce e predição do tempo de entrega de pedidos.

**Estrutura de Arquivos:**
- Pasta data/: possui os arquivos .csv utilizados nos projetos
- Pasta imgs/: possui imagens utilziadas nos notebooks
- .gitignore: lista de pastas e arquivos ignorados pelo controle de versionamento do repositório
- README.md: este arquivo de descrição do repositório
- Arquivo notebook_analise_descritiva_exploratoria.ipynb: notebook com análises descritivas e exploratórias dos dados, além de realizar alguns tratamentos nos dados
- Arquivo notebook_ml.ipynb: notebook com aplicação de modelos de ML para predição do tempo de frete
- pyproject.toml: arquivo com as dependências do projeto utilizado pelo gerenciador de dependências *poetry*
- poetry.lock: arquivo com as exatas versões utilizadas para cada uma das dependência do projeto utilizado pelo gerenciador de dependências *poetry*

**Dataset utilizado:** https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

**Ferramentas e pacotes utilizados:**
- Gerenciador de dependências: poetry
- Virtualização de ambiente: python venv
- Manipulação de dados: pandas, numpy
- Visualização de dados: plotly, seaborn
- Testes de hipóteses: scipy
- Preparação de dados para modelagem: sklearn (RobustScaler, MinMaxScaler, OrdinalEncoder)
- Workflow de modelagem: sklearn (train_test_split para separação dos dados, Pipeline e ColumnTransformer para evitar data leakage e facilitar reprodução do processo de treinamento, GridSearchCV e RandomizedSearchCV para realização de treino e validação utilizando Cross-Validation com busca de hiper-parâmetros)
- Modelagem: sklearn (LinearRegression, Ridge e RandomForestRegressor) e lightgbm
- Métrica de avaliação: sklearn (mean_squared_error)
