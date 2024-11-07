# IAMON
Um modelo SVM para classificação de Pokémon comuns, Lendário, Sub-lendários e Míticos.

## Descrição 
O Projeto visa demonstrar como o modelo de Inteligência Artificial SVM se comporta na classificação de 
indíviduos criados manualmente. Para isso, foi usado um dataset da Franquia Pokémon, contendo **898** Indivíduos. O Objetivo do Algorítmo é classificar quais dentre esses Pokémon são Comuns, Lendários, Sub-lendários e Míticos.

## Arquivos e Links

### 1. Trello
Foi feito uma página no trello documentando o processo do projeto.

### 2. Documentação
- [Resumo Extendido]()


## Metodologia
A metodologia descreve como o projeto está configurado em sua execução. Algumas informações adicionais estão no próprio código

### 1. Banco de Dados
O banco de dados é uma versão adaptada [deste](https://www.kaggle.com/datasets/cristobalmitchell/pokedex).
Algumas colunas são levadas em desconsideração, como colunas com varíaveis que não são numéricas ou irrelevantes para o projeto.
é criada uma nova coluna que é a junção das colunas `is_sublegendary` , `is_legendary` e `is_mythical`.

### 2. Treino dos Dados
Usando o SVM, o modelo é treinado com `80%` dos dados e com um Random State de `54`. Durante esse processo, O algoritmo busca encontrar padrões entre os Pokémon dos quais ele irá classificar.

### 3. Teste e Vizualização do Modelo
Após o treino, o modelo utiliza os 20% restantes como teste de classificação, e para isso é criado um Gráfico de Matriz de Confusão, cujo papel é permitir o usuário vizualizar os resultados. Além de que é criado um gráfico de permutação, que permite que sejam vizualizados quais foram os atributos mais relevantes para as decisões tomadas pelo modelo.

### 4. Aprimoração do Modelo
Então é feito um segundo treino, usando de ferramentas para otimizar o algoritmo, como GriSearch e Validação Cruzada, após isso os Gráficos de Matriz de Confusão e de permutação são criados novamente para refletir os novos resultados.

##  Como Executar e Customização

### 1. Download do Algoritmo
O primeiro passo é acessar o [repositório](https://github.com/Felipe-Gomes-Amorim/Pokedex/tree/main) para baixar o notebook que contém o código do modelo, após isso executá-lo no serviço de preferência(o serviço utilizado foi o Google Colab).

## 2. Execução
Para executar todas as células do Notebook basta apertar o conjunto de teclas `Ctrl+f9`. Também é possível executar as células individualmente.

## 3. Modificação
Os parâmetros que podem ser modificados para obter diferentes resultados são: `column_names`, `test_size`, `random_state` e `kernel`.

## Equipe de Desenvolvimento.

### 1. Código do Algoritmo
- [Felipe](https://github.com/Felipe-Gomes-Amorim)
- [Guilherme]()
- [Herny](https://github.com/HenryGeraldes)
- [Márcio]()
### 2. Documentação do Código.
- [Henry](https://github.com/HenryGeraldes)

### 3. Documentação Geral.
- [Camylla]()
- [Gustavo]()
- [Murilo]()
- [Henry](https://github.com/HenryGeraldes)
- [Felipe](https://github.com/Felipe-Gomes-Amorim)

### 4. GitHub
- [Felipe](https://github.com/Felipe-Gomes-Amorim)

### 5. Trello
- [Henry](https://github.com/HenryGeraldes)
