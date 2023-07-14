# pes_embraer_intro_cd
Repositório com códigos desenvolvidos na disciplina de Introdução à Ciência de Dados no Programa de Especialização em Software da Embraer, para os projetos 1 e 2 da disciplina.

**Estrutura de Arquivos:**
- Pasta data/: possui os arquivos .csv utilizados nos projetos
- Pasta imgs/: possui imagens utilziadas nos notebooks
- .gitignore: lista de pastas e arquivos ignorados pelo controle de versionamento do repositório
- README.md: este arquivo de descrição do repositório
- Arquivo projeto_1.ipynb: notebook com os códigos de desenvolvimento do Projeto 1
- Arquivo projeto_2.ipynb: notebook com os códigos de desenvolvimento do Projeto 2
- pyproject.toml: arquivo com as dependências do projeto utilizado pelo gerenciador de dependências *poetry*

**Dataset utilizado:** https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

**Vídeo de apresentação dos projetos**: https://drive.google.com/file/d/1jCx2eOMCIavpQRy0jECg9Gfhoeyniv1b/view?usp=sharing

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
