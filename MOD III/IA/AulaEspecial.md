# Relembrando conceitos de Machine Learning

Todo algoritmo de Machine Learning possui três fases principais:

1. **Entrada**: Recebimento dos dados de entrada, geralmente representados como pares (x, y), onde:
    - `x`: características (features) ou variáveis independentes, que descrevem os atributos dos exemplos.
    - `y`: rótulo (label) ou variável dependente, que representa o valor ou categoria a ser prevista (no caso de aprendizado supervisionado).
    - Os dados podem ser tabulares (linhas e colunas), imagens, textos, áudios, entre outros formatos.

2. **Processamento**: Aplicação de um modelo ou função sobre os dados de entrada para aprender padrões ou realizar previsões.
    - O modelo pode ser um algoritmo estatístico, uma árvore de decisão, uma rede neural, entre outros.
    - Durante o treinamento, o modelo ajusta seus parâmetros internos (por exemplo, pesos em uma rede neural) para minimizar o erro entre as previsões e os valores reais.
    - Exemplo: calcular `x + y`, ajustar pesos em uma rede neural, encontrar a melhor linha de separação entre classes, etc.

3. **Saída**: Resultado do processamento, como uma previsão, classificação, agrupamento ou recomendação.
    - Pode ser um valor numérico (regressão), uma categoria (classificação), um grupo (agrupamento), ou até mesmo uma recomendação personalizada.
    - Exemplo: a soma, uma classe prevista, um grupo identificado, ou uma sugestão de produto.

## Tipos de Aprendizado em Machine Learning

Existem diferentes paradigmas de aprendizado em Machine Learning, sendo os principais:

### Aprendizado Supervisionado

- O modelo é treinado com um conjunto de dados rotulado, ou seja, cada entrada `x` possui uma saída esperada `y`.
- O objetivo é aprender uma função que, dada uma nova entrada, consiga prever corretamente a saída.
- Exemplos: classificação de e-mails como spam ou não spam, previsão de preços de casas, diagnóstico médico.
- Principais tarefas:
    - **Classificação**: prever categorias (ex: spam/não spam).
    - **Regressão**: prever valores numéricos (ex: preço de uma casa).

### Aprendizado Não Supervisionado

- O modelo recebe apenas os dados de entrada `x`, sem rótulos.
- O objetivo é identificar padrões, estruturas ou agrupamentos nos dados.
- Exemplos: segmentação de clientes, agrupamento de imagens semelhantes, redução de dimensionalidade.
- Principais tarefas:
    - **Clusterização (Clustering)**: agrupar dados semelhantes (ex: separar clientes em grupos).
    - **Redução de dimensionalidade**: simplificar os dados mantendo as informações mais relevantes (ex: PCA).

#### Exemplo de Clusterização

No aprendizado não supervisionado, como na clusterização, cada coluna representa uma variável. Por exemplo, podemos criar uma tabela com quatro variáveis:

- Zona (Rural ou Urbana)
- União dos pais (Mora com eles ou não)
- Passado criminal (Sim ou não)
- Etnia (Preto e pardo ou branco)

O objetivo é identificar grupos de indivíduos com características semelhantes, sem saber previamente se eles têm possibilidade de ser presos ou não. O algoritmo encontra padrões e separa os dados em clusters (grupos) de acordo com as semelhanças entre as variáveis.

Dados tabulares possuem linhas (exemplos/indivíduos) e colunas (variáveis/características).

## Divisão dos Dados

Ao treinar um algoritmo, é comum dividir o conjunto de dados em duas partes principais:

- **Treinamento (geralmente 80%)**: usado para ajustar o modelo.
- **Teste (geralmente 20%)**: usado para avaliar o desempenho do modelo em dados que ele nunca viu.

Essa divisão garante que o modelo seja avaliado de forma justa e evita que ele apenas memorize os dados de treinamento.

Na classificação, você pode prever, por exemplo, se uma pessoa será presa ou não; no dataset iris, prever a espécie de uma flor, etc.

- **Instâncias** são as linhas da tabela (cada exemplo/indivíduo).
- **Features** (características) são as colunas (variáveis que descrevem cada instância).

Dois tipos de dados principais:

- **Dados de entrada (`X`)**: conjunto de variáveis independentes (features).
- **Dados de saída (`y`)**: variável dependente (rótulo ou valor a ser previsto).

