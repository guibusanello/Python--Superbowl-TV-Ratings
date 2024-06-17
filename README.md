# Python - Superbowl Television Ratings

O Superbowl é um dos eventos esportivos mais assistidos pela televisão, reunindo espectadores do mundo todo para acompanhar o jogo entre o vencedor da NFC contra o vencedor da AFC e conquistar o tão cobiçado Lombardi Trophy. Com o objetivo de analisar algumas informações sobre as transmissões do Superbowl pela televisão, utilizei o Python para fazer uma análise exploratória e obter alguns insights. Boa leitura!

## Dataset

O dataset possui dados de 1967 até 2021, ou seja, do Superbowl I até o Superbowl LV. As colunas da tabela são:

- super_bowl - identificação do Superbowl com algarismos romanos
- super_bowl_number - id do Superbowl
- date - data do evento
- network - emissora que transmitiu o jogo
- average_viewers - média de espectadores
- total_viewers - total de espectadores
- household_rating - porcentagem de residências equipadas com televisão que estavam sintonizadas na transmissão do Superbowl.
- household_share - porcentagem de residências que estavam assistindo a transmissão do Superbowl em relação ao número total de lares que estão com a TV ligada no momento da transmissão do Superbowl.
- cost_of_30_second_ad_usd - custo de 30 segundos de propaganda durante a transmissão do Superbowl

Link para o dataset: https://www.kaggle.com/datasets/mattop/super-bowl-television-ratings/data

## Conclusões

📺 A emissora que mais transmitiu o Superbowl foi a CBS, já a ABC foi a que menos transmitiu a partida.

🏈📈 O Superbowl LI teve a maior média de audiência até 2021.

🏈📉 O Superbowl I teve a menor média de audiência até 2021.

📈 A partir do Superbowl XXVI, todas as audiências foram acima da média.

💸💥 A partir do Superbowl XLI, o custo por 30 segundos de propaganda teve um aumento exponencial.

💸📈 A partir do Superbowl XXXIV, em todos os anos o custo por 30 segundos de propaganda foi acima da média.

💰💰 O maior preço por 30 segundos de anúncio foi no Superbowl LV.

📈 A maior taxa de Household rating foi no Superbowl XVI.

🏠📈 A maior taxa de Household share foi no Superbowl X.

📊💸 O total e a média de espectadores têm uma correlação muito alta com o custo por 30 segundos de propaganda.
