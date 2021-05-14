# See here my data projects!
[My Portfolio](https://dannyredel.github.io/)


## Ejercicio A.
1. Definimos como numéricas las siguientes variables: $age$, $duration$ y $amount$. Construimos la tabla descriptiva para las variables numéricas:
```{r Numericas, include=FALSE}

numericas <- credit_data %>% 
  select(duration, amount, age)
head(numericas)

```
