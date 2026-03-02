# nuvem-semana1-julia-schadeck
Atividade feita em sala de aula no dia 23/02/2026, no período da manhã. 

# Semana 1 - Deploy estatico (GitHub Pages)
## Links
- Repositorio: https://github.com/JuliaGabrielaSchadeck/nuvem-semana1-julia-schadeck
- Site (GitHub Pages): https://juliagabrielaschadeck.github.io/nuvem-semana1-julia-schadeck/
## O que foi feito
- Criei index.html, style.css e script.js pelo navegador
- Ativei GitHub Pages (main / root)
## Dificuldades
- Entender o que estava sendo pedido, comitar o site.


# Semana 2 -  HTTP e Fetch (sem Node)
- Comitei os textos da semana 1
- Adicionei o novo código
- Testei a simulação
## Links
- Repositorio: https://github.com/JuliaGabrielaSchadeck/nuvem-semana1-julia-schadeck
- Site (GitHub Pages): https://juliagabrielaschadeck.github.io/nuvem-semana1-julia-schadeck/
## Dificuldades
- Entender o erro e localiza-lo.
## Resultados
- O erro, antes de arrumar, era de token invalido
- Quando cliquei no GET, o seguinte texto apareceu
  {
  "fonte": "open-meteo.com",
  "temperatura": 23,
  "vento": 14.5,
  "unidade_temp": "°C",
  "unidade_vento": "km/h",
  "bruto": {
    "latitude": -24.375,
    "longitude": -53.875,
    "generationtime_ms": 0.04470348358154297,
    "utc_offset_seconds": 0,
    "timezone": "GMT",
    "timezone_abbreviation": "GMT",
    "elevation": 329,
    "current_units": {
      "time": "iso8601",
      "interval": "seconds",
      "temperature_2m": "°C",
      "wind_speed_10m": "km/h"
    },
    "current": {
      "time": "2026-03-02T11:15",
      "interval": 900,
      "temperature_2m": 23,
      "wind_speed_10m": 14.5
    }
  }
}
- Já quando cliquei no POST, apareceu
{
  "fonte": "jsonplaceholder.typicode.com",
  "resposta": {
    "turma": "Serviços em Nuvem",
    "atividade": "Semana 2",
    "timestamp": "2026-03-02T11:24:32.309Z",
    "id": 101
  }
}
