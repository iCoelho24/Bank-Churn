# **Bank Churn**
Este é um projeto de análise de dados que visa prever a probabilidade de um cliente cancelar sua conta bancária. Para isso, utilizamos um conjunto de dados contendo informações sobre clientes do banco, incluindo sua pontuação de crédito, país, sexo, idade, tempo de permanência como cliente, saldo na conta e outros atributos relevantes.

Dicionário de Variáveis
Para entender melhor os dados que estamos analisando, aqui está um dicionário de variáveis:

- RowNumber: índice da linha no dataset.
- CustomerId: ID único do cliente.
- Surname: sobrenome do cliente.
- CreditScore: pontuação de crédito do cliente.
- Geography: país do cliente.
- Gender: gênero do cliente.
- Age: idade do cliente.
- Tenure: tempo de permanência como cliente do banco (em anos).
- Balance: saldo disponível na conta do cliente.
- NumOfProducts: número de produtos bancários que o cliente possui.
- HasCrCard: indica se o cliente possui um cartão de crédito ou não.
- IsActiveMember: indica se o cliente é um membro ativo ou não.
- EstimatedSalary: salário estimado do cliente.
- Exited: variável target, informa se o cliente cancelou sua conta ou não.

Pré-requisitos
Para executar este projeto, você precisa ter instalado em sua máquina o Python 3 e as seguintes bibliotecas:

NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Como Executar o Projeto
Para executar o projeto, basta baixar ou clonar o repositório em sua máquina e executar o arquivo churn.ipynb. Este script irá carregar os dados, realizar a análise exploratória, pré-processamento dos dados, treinar um modelo de machine learning e avaliar sua performance.

Resultados
Os resultados da análise serão apresentados no notebook. As métricas usadas para avaliar o modelo são Recall, Matriz de confusão.

Conclusão
Este projeto tem como objetivo ajudar o banco a identificar quais clientes têm maior probabilidade de cancelar suas contas e, assim, tomar medidas preventivas para evitar a perda de clientes. Com a aplicação do modelo de machine learning, podemos obter uma boa acurácia na previsão de churns, permitindo que o banco tome as medidas necessárias para manter seus clientes satisfeitos e fiéis.