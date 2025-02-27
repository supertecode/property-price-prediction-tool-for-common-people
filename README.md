# property-price-prediction-tool-for-common-people
Ferramenta de Previsão de Preço de Imóvel para pessoas comuns. 

Contexto:
No Airbnb, qualquer pessoa que possua um quarto ou um imóvel de qualquer tipo (apartamento, casa, chalé, pousada, etc.) pode ofertar o seu imóvel para ser alugado por diária.

Você cria o seu perfil de host (pessoa que disponibiliza um imóvel para aluguel por diária) e cria o anúncio do seu imóvel.

Nesse anúncio, o host deve descrever as características do imóvel da forma mais completa possível, de forma a ajudar os locadores/viajantes a escolherem o melhor imóvel para eles (e de forma a tornar o seu anúncio mais atrativo)

Existem dezenas de personalizações possíveis no seu anúncio, desde quantidade mínima de diária, preço, quantidade de quartos, até regras de cancelamento, taxa extra para hóspedes extras, exigência de verificação de identidade do locador, etc.

Nosso objetivo:
  *Construir um modelo de previsão de preço que permita uma pessoa comum que possui um imóvel possa saber quanto deve cobrar pela diária do seu imóvel. Ou ainda, para o locador comum, dado o imóvel que ele está buscando, ajudar a saber se aquele imóvel está com preço atrativo (abaixo da média para imóveis com as mesmas características) ou não.

Base de dados:
  *Baixar as bases de dados do site kaggle: https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro
  *As bases de dados são os preços dos imóveis obtidos e suas respectivas características em cada mês.
  *Os preços são dados em reais (R$)
  *Temos bases de abril de 2018 a maio de 2020, com exceção de junho de 2018 que não possui base de dados

Expectativas Iniciais:
  *A sazonalidade pode ser um fator importante, visto que meses como dezembro costumam ser bem caros no RJ
  *A localização do imóvel deve fazer muita diferença no preço, já que no Rio de Janeiro a localização pode mudar completamente as características do lugar (segurança, beleza natural, pontos turísticos)
  *Adicionais/Comodidades podem ter um impacto significativo, visto que temos muitos prédios e casas antigos no Rio de Janeiro
  
Vamos descobrir o quanto esses fatores impactam e se temos outros fatores não tão intuitivos que são extremamente importantes.

Etapas previstas do Projeto (metodologia CRISP):
  *Definição do Problema
  *Entendimento e ajuste (limpeza) dos dados
  *Análise Exploratória, analisar os Outliers
  *Tratamento dos dados
  *Definição do algoritmo de aprendizagem de máquina
  *Validação do modelo
  *Apresentação dos dados
  *Modelo em produção
