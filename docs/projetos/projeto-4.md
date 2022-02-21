---
hide:
  - toc
---

#Projeto 4
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis et justo dui. Donec dui nibh, molestie non massa sit amet, viverra volutpat massa. In vulputate vestibulum massa, vel accumsan mauris faucibus a. Etiam suscipit tellus ac gravida aliquet. Etiam sed sem blandit, vestibulum dolor quis, laoreet magna. Nunc sit amet nisl aliquet, feugiat nibh sed, aliquet massa. Donec quis ex aliquet, pharetra nulla sed, placerat neque. Donec quis porttitor turpis, non tincidunt urna. Aliquam interdum nunc nunc, semper porttitor est scelerisque vel. Vivamus eu pulvinar nisi. Sed eget ligula semper, sodales dui sit amet, accumsan lacus.
Phasellus molestie dignissim malesuada. 

Mauris egestas eros metus, ac tempus tellus faucibus at. Nunc vel aliquam dolor, eu rhoncus urna. Duis sit amet efficitur ipsum. Aenean luctus nunc at est varius, id sollicitudin ipsum ullamcorper. Cras vel sem ligula. Pellentesque rhoncus dictum lectus, ut egestas sem feugiat a. Etiam non nisi quis massa tincidunt sollicitudin. Praesent ullamcorper ornare purus, eget auctor tellus vestibulum eget. Sed at viverra mauris. Integer quis lorem a eros laoreet blandit a quis nulla. Sed vel fringilla nibh. Donec tincidunt ultricies est eget feugiat. Donec sapien metus, venenatis non ipsum eu, malesuada faucibus nisi.
Ut eget mollis tellus.

```vegalite
{
  "description": "Teste de Gráficao de Barras",
  "data": {
    "values": [
      {"Métrica / Dimensão": "Pellentesque", "Quantidade": 1},
      {"Métrica / Dimensão": "purus", "Quantidade": 4},
      {"Métrica / Dimensão": "dolor", "Quantidade": 2}
    ]
  },
  "mark": {"type": "bar", "tooltip": true},
  "encoding": {
    "x": {"field": "Métrica / Dimensão", "type": "nominal", "axis": {"labelAngle": -30}},
    "y": {"field": "Quantidade", "type": "quantitative"}
  }
}
```
------------------
```vegalite 
{
  "description": "A simple bar chart with embedded data.",
  "data": {"url" : "../docs/charts/data/teste.csv"},
  "mark": {"type": "bar", "tooltip": true},
  "encoding": {
    "x": {"field": "a", "type": "nominal", "axis": {"labelAngle": 0}},
    "y": {"field": "b", "type": "quantitative"}
  }
}
```