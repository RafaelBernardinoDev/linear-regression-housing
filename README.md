# Introdução

Este projeto tem como objetivo prever os preços de casas com base em suas características estruturais e qualitativas. Os dados utilizados foram inspirados no conjunto *House Prices - Advanced Regression Techniques* do Kaggle.

A metodologia principal empregada para essa previsão será a **Regressão Linear**, um dos métodos mais utilizados para análise preditiva em problemas de regressão.

## Sobre os dados

Os principais atributos utilizados no modelo são:

- **`area_primeiro_andar`**: Representa a área do primeiro andar da propriedade (m²).  
- **`existe_segundo_andar`**: Variável binária indicando se há um segundo andar (1 = Sim, 0 = Não).  
- **`area_segundo_andar`**: Se a propriedade possuir um segundo andar, essa variável indica sua área total (m²).  
- **`quantidade_banheiros`**: Número total de banheiros na propriedade.  
- **`capacidade_carros_garagem`**: Capacidade máxima de veículos na garagem.  
- **`qualidade_da_cozinha_Excelente`**: Indica se a qualidade da cozinha é "Excelente" (1 = Sim, 0 = Não).  
- **`preco_de_venda`**: Preço final da propriedade (variável alvo a ser prevista).
