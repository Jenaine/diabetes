# Diabetes

# Motivação e objetivo

O Diabetes Mellitus é uma condição crônica que afeta milhões de pessoas em todo o mundo. O crescimento acentuado da prevalência nas últimas décadas se apresenta como um grave problema de saúde pública. Com o crescente volume de dados de saúde disponíveis, há uma oportunidade de usar modelos de inteligência artificial para melhorar a detecção precoce, o diagnóstico e o gerenciamento de diabetes. A aplicação de técnicas de aprendizado de máquina pode fornecer insights valiosos que auxiliam profissionais de saúde na tomada de decisões e no tratamento dos pacientes.

# Objetivo:
Desenvolver um modelo de aprendizado supervisionado que possa prever a presença de diabetes em indivíduos com base em um conjunto de indicadores de saúde. Usaremos o dataset CDC Diabetes Health Indicators para treinar e testar o modelo, visando obter um classificador eficaz que possa diferenciar entre indivíduos com e sem diabetes.

# Descrição do Dataset
O conjunto de dados CDC Diabetes Health Indicators contém informações de 253.680 indivíduos, com 21 características relacionadas à saúde e estilo de vida, como idade, IMC, pressão arterial, histórico de tabagismo, e outros. As variáveis de saída são categóricas, indicando se o indivíduo é saudável, pré-diabético ou diabético.

https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators


# Próximos Passos
Prosseguir com a construção e treinamento de modelos de IA utilizando o banco de dados sobre diabetes, aplicando técnicas de pré-processamento e validação de dados para melhorar a precisão dos resultados. 




## Metadata 
- `uci_id`: Unique dataset identifier for UCI repository 
- `name`
- `abstract`: Short description of dataset
- `area`: Subject area e.g. life science, business
- `task`: Associated machine learning tasks e.g. classification, regression
- `characteristics`: Dataset types e.g. multivariate, sequential
- `num_instances`: Number of rows or samples
- `num_features`: Number of feature columns
- `feature_types`: Data types of features
- `target_col`: Name of target column(s)
- `index_col`: Name of index column(s)
- `has_missing_values`: Whether the dataset contains missing values
- `missing_values_symbol`: Indicates what symbol represents the missing entries (if the dataset has missing values)
- `year_of_dataset_creation`
- `dataset_doi`: DOI registered for dataset that links to UCI repo dataset page
- `creators`: List of dataset creator names
- `intro_paper`: Information about dataset's published introductory paper
- `repository_url`: Link to dataset webpage on the UCI repository
- `data_url`: Link to raw data file
- `additional_info`: Descriptive free text about dataset
	- `summary`: General summary 
	- `purpose`: For what purpose was the dataset created?
	- `funding`: Who funded the creation of the dataset?
	- `instances_represent`: What do the instances in this dataset represent?
	- `recommended_data_splits`: Are there recommended data splits?
	- `sensitive_data`: Does the dataset contain data that might be considered sensitive in any way?
	- `preprocessing_description`: Was there any data preprocessing performed?
	- `variable_info`: Additional free text description for variables
	- `citation`: Citation Requests/Acknowledgements
 - `external_url`: URL to external dataset page. This field will only exist for linked datasets i.e. not hosted by UCI


## Links
- [UCI Machine Learning Repository home page](https://archive.ics.uci.edu/)
- [PyPi repository for this package](https://pypi.org/project/ucimlrepo)
- [Submit an issue](https://github.com/uci-ml-repo/ucimlrepo-feedback/issues)
