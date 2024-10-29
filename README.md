## Análise dos Dados do Airbnb em Barcelona
### Descrição do Projeto

![freepik__candid-image-photography-natural-textures-highly-r__36495_Easy-Resize com (1)](https://github.com/user-attachments/assets/e5153e6f-8bb1-44b2-b0bb-eff221373221)


Este repositório contém uma análise exploratória dos dados do Airbnb na cidade de Barcelona, utilizando informações disponíveis no portal Inside Airbnb. O Airbnb é atualmente uma das maiores empresas hoteleiras do mundo, conectando viajantes a anfitriões que oferecem hospedagens alternativas. O objetivo deste projeto é extrair insights significativos sobre as características e tendências das propriedades listadas em Barcelona.

### Dados Utilizados

Os dados utilizados nesta análise foram obtidos a partir do arquivo listings.csv, que contém informações sobre as propriedades disponíveis para aluguel em Barcelona. As variáveis analisadas incluem:

|Variável    |   Descrição|
|------------|-----------------|
|id | Identificador único da propriedade|
|name |Nome da propriedade|
|host_id | Identificador do anfitrião|
|neighbourhood |Bairro da propriedade|
|latitude e longitude |Coordenadas geográficas|
|room_type| Tipo de quarto oferecido (e.g., apartamento inteiro, quarto privado)|
|price| Preço do aluguel|
|minimum_nights| Número mínimo de noites para reserva|
|number_of_reviews| Total de avaliações recebidas|
|reviews_per_month| Avaliações recebidas por mês|
|availability_365| Dias de disponibilidade no ano|

### Principais Insights

1. Distribuição de Preços: A média de preços das propriedades é de aproximadamente R$90,42. A análise revelou variações significativas entre os bairros, com alguns locais apresentando valores médios superiores a R$190,00.

2. Tipos de Propriedades: O tipo de imóvel mais comum listado no Airbnb é o apartamento inteiro, representando cerca de 58,68% das ofertas. Os quartos privados representam 39,71%, enquanto os quartos compartilhados e os quartos de hotel têm uma presença menor.

3. Localização e Disponibilidade: A análise geoespacial mostrou a distribuição das propriedades em Barcelona, destacando áreas com maior concentração de aluguéis e os preços correspondentes.

4. Outliers e Dados Ausentes: Foi realizada a identificação de outliers nas variáveis numéricas, resultando em um aumento na porcentagem de valores ausentes, especialmente nas colunas de preço e número de avaliações.
