# Mapa Interativo: Fazenda Rio das Pedras

Este projeto é um mapa interativo desenvolvido para a Fazenda Rio das Pedras, permitindo a visualização de camadas ambientais como uso consolidado, vegetação, hidrografia, linhas de transmissão, nascentes e perímetro.

## Link para o Mapa
Acesse o mapa online aqui: [Mapa Interativo](https://csambiental.github.io/Riodaspedras/)

## Funcionalidades
- **Visualizar Camadas**: Ative ou desative as camadas (Uso Consolidado, Vegetação, etc.) usando a barra lateral.
- **Exportar Mapa**: Clique no botão "Exportar Mapa" para baixar uma imagem do mapa com legenda e logos.

## Arquivos Necessários
O mapa depende dos seguintes arquivos GeoJSON, que devem estar na raiz do repositório:
- `consolidado_wgs84.geojson`
- `vegetacao_wgs84.geojson`
- `perimetro_wgs84.geojson`
- `hidro_wgs84.geojson`
- `transmissao_wgs84.geojson`
- `nascentes_wgs84.geojson`

Além disso, os arquivos de logo (`logo.png` e `logo_cs.png`) também devem estar na raiz para a exportação funcionar corretamente.

## Autores
Desenvolvido por João Pedro [CS Consultoria Ambiental](https://csconsultoriaambiental.com.br/).
