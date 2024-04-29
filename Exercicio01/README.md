# Projeto de Aprendizado de Máquina com Azure

Este repositório contém um projeto de aprendizado de máquina utilizando o Microsoft Azure.

## Conjunto de Dados

O conjunto de dados utilizado neste projeto é um conjunto de dados para prever o preço de venda de imóveis com base em suas características.

## Modelo de Aprendizado de Máquina

O modelo utilizado neste projeto é o algoritmo algoritmo de Regressão Linear e/ou Floresta Aleatória, que são adequados para previsão de preços.

- **ID**: Identificador único para cada imóvel.
- **Localização**: Bairro ou distrito onde o imóvel está localizado.
- **Área**: Tamanho do imóvel em metros quadrados.
- **Quartos**: Número de quartos.
- **Banheiros**: Número de banheiros.
- **Vagas**: Número de vagas de garagem.
- **Ano de Construção**: Ano em que o imóvel foi construído.
- **Preço**: Preço de venda do imóvel.

## Configuração do Azure

1. Criou-se um Workspace no Azure Machine Learning para organizar os experimentos e modelos.
2. Os dados foram carregados e preparados.
3. O modelo foi treinado com os dados preparados.
4. Foi configurado um endpoint para permitir previsões usando o modelo treinado.

## Como Testar o Endpoint

Você pode testar o endpoint com dados de teste. Basta enviar uma solicitação HTTP POST com os dados para o endpoint e receberá a previsão correspondente.

## Links Úteis

- [Documentação do Azure Machine Learning](https://docs.microsoft.com/azure/machine-learning/)

## JSON
[
  {
    "ID": 1,
    "Localização": "Centro",
    "Área": 70,
    "Quartos": 2,
    "Banheiros": 2,
    "Vagas": 1,
    "Ano de Construção": 1990,
    "Preço": 300000
  },
  {
    "ID": 2,
    "Localização": "Zona Sul",
    "Área": 120,
    "Quartos": 3,
    "Banheiros": 3,
    "Vagas": 2,
    "Ano de Construção": 2015,
    "Preço": 1400000
   {
    "ID": 3,
    "Localização": "Zona Oeste",
    "Área": 158,
    "Quartos": 4,
    "Banheiros": 3,
    "Vagas": 2,
    "Ano de Construção": 2012,
    "Preço": 1700000
 ]
