
# Diversidad ecológica

Libremente, intenta replicar los análisis que verás
[aquí](https://cran.r-project.org/web/packages/vegan/vignettes/diversity-vegan.pdf)
(excluyendo el punto 3) usando las matrices de comunidad `mc.csv` y
ambiental `env.csv` localizadas en la carpeta `data`, e interpretemos
oralmente los resultados en el aula. Se trata de muestras de plantas de
porte arboreo y arbustivo del bosque semideciduos de la cuenca del río
Ocoa. Una descripción de las muestras la puedes encontrar en la sección
*Materials and Methods* de [este
artículo](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0208780).
Esta práctica no se evaluará. “Libremente” significa que los análisis no
tienes que replicarlos exactamente igual.

## Paquetes. Necesitamos a la colección `tidyverse` y `vegan`

``` r
library(tidyverse)
library(vegan)
```

## Datos

``` r
cm <- read.csv('data/d.mc.csv', row.names = 1, check.names = F)
env <- read.csv('data/d.env.csv', row.names = 1, check.names = F)
```

## Índices de diversidad

## Gráficos de los índices de diversidad

## Rarificación

## Modelos de abundancia de especie

## Modelos de acumulación de especies y diversidad *beta*

### Modelos de acumulación de especies

### Diversidad *beta*

## Gráficos de la diversidad *beta*

## Conjunto de especies (esperadas, no vistas)
