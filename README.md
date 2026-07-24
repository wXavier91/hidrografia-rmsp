# Hidrografia RMSP

Camada de hidrografia da Região Metropolitana de São Paulo para uso em aplicativos de navegação (testado no OsmAnd).

## Uso no OsmAnd

Adicionar como mapa de sobreposição (Overlay):

https://wxavier91.github.io/hidrografia-rmsp/tiles/{0}/{1}/{2}.png

## Fonte dos dados

Dados hidrográficos obtidos a partir da base do CEM/USP.
https://centrodametropole.fflch.usp.br/pt-br/download-de-dados
Tipos = cartografico
Temas = meio ambiente
Arquivo = Cursos d'água da Região Metropolitana de São Paulo 2025
Link completo: https://centrodametropole.fflch.usp.br/pt-br/download-de-dados?f%5B0%5D=facets_temas%3Ameio%20ambiente&f%5B1%5D=facets_tipos%3Acartografico

## Características

- Hierarquia dos cursos d'água:
  - Rio
  - Ribeirão
  - Córrego
  - Outros

- Rótulos adaptados por nível de zoom.
- Estilo otimizado para visualização em smartphones.

## Projeto QGIS

A pasta `qgis` contém:
- arquivo do projeto;
- estilos;
- dados utilizados na geração dos tiles.

## Última atualização

Julho de 2026