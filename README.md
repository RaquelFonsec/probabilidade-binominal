📌  Análise de Probabilidades com Distribuição Binomial


Este projeto tem como objetivo calcular e analisar as probabilidades de eventos usando a distribuição binomial. Cada situação representada envolve a probabilidade de ocorrência de diferentes números de eventos em amostras aleatórias, de acordo com a probabilidade de sucesso. Usamos a biblioteca scipy.stats no Google Colab para calcular essas probabilidades. Abaixo estão os problemas abordados, seguidos pelos resultados.




📋 Problemas Abordados:
Probabilidade de Motoristas Mulheres
Considerando que 5% dos motoristas de caminhões brasileiros são mulheres, foi calculada a probabilidade de:



a) Exatamente 2 motoristas serem mulheres em uma amostra de 10 motoristas.
b) Nenhum motorista ser mulher na amostra de 10 motoristas.
c) Pelo menos 1 motorista ser mulher na amostra.
Sistema de Detecção de Mísseis
Foi analisado o desempenho de sistemas de detecção de mísseis com uma taxa de sucesso de 90%. Foram calculadas as probabilidades de pelo menos 1 sistema funcionar com 2 e 3 sistemas instalados, respectivamente.



Amostra de Artigos Defeituosos
Para um lote de artigos, onde 10% são defeituosos, foram calculadas as probabilidades de:

Nenhum defeituoso
Um defeituoso
Um ou mais defeituosos
Um ou menos defeituosos
Dois defeituosos
No máximo dois defeituosos
No mínimo dois defeituosos
Não mais que três defeituosos
Produtividade de Funcionários
Em uma empresa, 80% dos funcionários melhoram a produtividade após um treinamento. Foram calculadas as probabilidades de:



Exatamente 7 funcionários aumentarem a produtividade.
Não mais que 8 funcionários aumentarem a produtividade.
Pelo menos 3 funcionários aumentarem a produtividade.
Controle de Qualidade em Componentes
Considerando uma amostra de 5 componentes com 1% de defeituosos, foram calculadas as probabilidades de:



Nenhum item defeituoso
Um item defeituoso
Um ou mais itens defeituosos


📝 Resumo dos Resultados:


1. Motoristas Mulheres
Probabilidade de 2 motoristas serem mulheres: 7.46%
Probabilidade de nenhum motorista ser mulher: 59.87%
Probabilidade de pelo menos 1 motorista ser mulher: 40.13%


3. Sistema de Detecção de Mísseis
Probabilidade de pelo menos 1 sistema funcionar (2 sistemas): 99.00%
Probabilidade de pelo menos 1 sistema funcionar (3 sistemas): 99.90%


5. Amostra de Artigos Defeituosos
Probabilidade de nenhum defeituoso: 65.61%
Probabilidade de 1 defeituoso: 29.16%
Probabilidade de um ou mais defeituosos: 34.39%
Probabilidade de um ou menos defeituoso: 94.77%
Probabilidade de 2 defeituosos: 4.86%
Probabilidade de no máximo 2 defeituosos: 99.63%
Probabilidade de no mínimo 2 defeituosos: 5.23%
Probabilidade de não mais que 3 defeituosos: 99.99%


7. Produtividade de Funcionários
Probabilidade de exatamente 7 funcionários aumentarem a produtividade: 20.13%
Probabilidade de não mais que 8 funcionários aumentarem a produtividade: 62.42%
Probabilidade de pelo menos 3 funcionários aumentarem a produtividade: 99.99%


9. Controle de Qualidade em Componentes
Probabilidade de nenhum item ser defeituoso: 95.10%
Probabilidade de um item ser defeituoso: 4.80%
Probabilidade de um ou mais itens serem defeituosos: 4.90%



💻 Execução no Google Colab



O código foi implementado utilizando a biblioteca scipy.stats para calcular as probabilidades baseadas na distribuição binomial. O código pode ser facilmente executado no Google Colab, permitindo a simulação de diferentes cenários com probabilidades variáveis.

📌 Conclusão
Distribuição Binomial: Utilizamos a distribuição binomial para modelar eventos em que há dois resultados possíveis: sucesso ou fracasso.
As probabilidades calculadas ajudam a entender cenários de risco e probabilidades de falha em diferentes contextos, como controle de qualidade, sistemas de detecção, e treinamento de funcionários.
Este projeto demonstra como o uso de distribuições probabilísticas pode informar decisões empresariais, como aceitação de lotes, avaliação de sistemas de segurança e otimização de produtividade.
