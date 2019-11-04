
# Workshop Para mineria de texto

## pre requisitos.

1.  Instalar R y Rstudio. (recomendamos este tutorial de
    [Rladies](https://github.com/lauracion/R_Curso_de_Nivelacion/blob/master/Instalacion_R_RStudio.md))
2.  Instalar los siguientes paquetes:

<!-- end list -->

``` r
install.packages('tidyverse')
install.packages('tm')
install.packages('rtweet')
install.packages('wordcloud2')
install.packages('topicmodels')
install.packages('LDAvis')
install.packages('tsne')
install.packages('devtools')
install.packages('jsonlite')
devtools::install_github("VerbalExpressions/RVerbalExpressions")
```

3.  Tener cuenta de twitter, y de twitter developer (se aplica desde
    [acá](https://developer.twitter.com/en/apply-for-access.html)).
    Como aplicar a una cuenta de developer de twitter no es trivial, y
    no siempre se conceden los permisos, se puede venir sin este
    requisito, aunque es necesario para replicar los procesamientos en
    otros proyectos.

4.  Es aconsejable tener una base de R y R studio para poder seguir
    mejor el desarrollo del curso. En caso de no tener experiencia
    previa en R se recomienda [estas
    notas](https://github.com/lauracion/R_Curso_de_Nivelacion/blob/master/Taller_Primeros_Pasos_en_R.md)
    introductorias de Laura Ación y Riva Quiroga

5.  Descargar los materiales del curso:

<!-- end list -->

``` r
usethis::use_course('https://github.com/DiegoKoz/workshop_text_mining/archive/master.zip')
```

## Materiales:

  - [Explicacion](1_explicacion.nb.html)
  - [Práctica Guiada](2_practica_guiada.nb.html)
  - [Práctica Independiente](3_practica_independiente.nb.html)

## Temario:

  - Introducción
  - Análisis de texto en Ciencias Sociales
  - Bag of Words
  - Normalización
      - Caracteres especiales.
  - Distancia de palabras
  - Distancia de caracteres
  - Distancia Conceptual
  - Distancia de Documentos
      - Similitud Coseno
  - Topic Modelling
  - Implementaciones en R:
      - rtweet
      - tm
      - RVerbalExpressions
      - wordcloud2
      - LDAvis
      - tsne
