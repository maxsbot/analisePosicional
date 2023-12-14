# Análise de Locomoção Diária com Mapas Interativos

Este projeto é uma ferramenta para análise de padrões de locomoção diária. Usando Python e bibliotecas de visualização de dados, este script transforma dados de coordenadas em um mapa interativo, destacando trajetos diários com cores distintas.

## Funcionalidades

- **Visualização de Trajetos**: Cada trajeto diário é representado por uma cor única no mapa, facilitando o acompanhamento e a comparação de rotas ao longo do tempo.
- **Agrupamento de Marcadores**: Pontos no mapa são agrupados para melhor visualização. Cada ponto representa uma localização com detalhes adicionais acessíveis via pop-up.
- **Legenda Dinâmica**: Uma legenda interativa é gerada no mapa, relacionando datas a cores correspondentes para fácil referência.

## Como Usar

1. **Pré-requisitos**: Certifique-se de ter as versões mais recentes das seguintes bibliotecas instaladas:
   - pandas
   - folium
   - matplotlib
2. **Dados de Entrada**: O script aceita dados em formato Excel (`.xlsx`), que devem incluir colunas para coordenadas, altitude e data/hora.
3. **Executando o Script**: Após configurar o caminho do arquivo de dados no script, execute-o para visualizar o mapa gerado.

## Exemplo de Mapa

![Exemplo de Mapa](URL_da_imagem_do_mapa)

*Nota: A imagem acima é apenas um exemplo. O mapa gerado será baseado nos dados fornecidos pelo usuário.*

## Contribuições

Contribuições, ideias para melhorias e relatórios de bugs são sempre bem-vindos. Sinta-se à vontade para abrir uma issue ou enviar um pull request.
