# decision-trees-base
Nesta base vamos tentar predizer a temperatura máxima do dia seguinte em Seattle-WA baseado em dados climáticos

1. Carregue a base temps.csv e prepare os dados
- Visualização, tratamento de colunas, divisão de dados, etc - o que for necessário

2. Crie e treine uma Árvore de Decisão
- Varie alguns parâmetros e avalie por meio de validação cruzada considerando que se trata de uma série temporal
Obs.: por se tratar de uma série de dados temporal, existem algumas implicações na validação cruzada.
Favor ler o link abaixo e tentar se adaptar a este fator:
https://scikit-learn.org/stable/modules/cross_validation.html#cross-validation-of-time-series-data

3. Treine o modelo final e avalie-o na base de testes
- Utilize os melhores parâmetros descobertos na etapa anterior, use o modelo para predizer a temperatura (actual) na base de testes e avalie o resultado

4. Exiba a árvore final em texto simples e como uma imagem

5. Exiba a predição e os dados reais (eixo y) vs a data (eixo x)

6. Treine um regressor baseado em Random Forest
- Encontre os melhores valores para os principais parâmetros utilizando validação cruzada

7. Use o modelo para predizer a temperatura e avalie o resultado

8. Eexiba a predição vs. dados reais
- Compare com o resultado anterior utilizando apenas uma árvore

9. Extra: calcule o bias e variância dos modelos trabalhados (0,5)
