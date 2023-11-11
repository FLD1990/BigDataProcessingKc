
### Practica del módulo de Big Data Processing

**Enunciado**

Tenemos el dataset que contiene el reporte de países y su índice de felicidad en el transcurso de los años (world-happiness-report-2021.csv y world-happiness-report.csv). Se les pide a los alumnos desarrollar respuestas a las siguientes preguntas, utilizando las herramientas vistas a lo largo del módulo.

1. **¿Cuál es el país más “feliz” del 2021 según la data?**
2. **¿Cuál es el país más “feliz” del 2021 por continente según la data?**
3. **¿Cuál es el país que más veces ocupó el primer lugar en todos los años?**
4. **¿Qué puesto de Felicidad tiene el país con mayor GDP del 2020?**
5. **¿En qué porcentaje a variado a nivel mundial el GDP promedio del 2020 respecto al 2021? ¿Aumentó o disminuyó?**
6. **¿Cuál es el país con mayor expectativa de vida (“Healthy life expectancy at birth”)? Y ¿Cuánto tenía en ese indicador en el 2019?**

Link a [Medium](https://medium.com/@fernandoldou/bigdata-processing-ce46294387a5) 

**Respuestas:**

1. País más "feliz" del 2021:
   *El pais mas feliz es Finlandia con un índice de  7.842 puntos*
3. País más "feliz" del 2021 por continente:
   *En la siguiente tabla y grafico se indican los paises más felices por continente*
   
| Country name           | Regional indicator             | Ladder score |
|------------------------|--------------------------------|--------------|
| Finland                | Western Europe                 | 7.842        |
| New Zealand            | North America and ANZ          | 7.277        |
| Israel                 | Middle East and North Africa   | 7.157        |
| Costa Rica             | Latin America and Caribbean    | 7.069        |
| Czech Republic         | Central and Eastern Europe     | 6.965        |
| Taiwan Province of China| East Asia                      | 6.584        |
| Singapore              | Southeast Asia                 | 6.377        |
| Uzbekistan             | Commonwealth of Independent States | 6.179     |
| Mauritius              | Sub-Saharan Africa             | 6.049        |
| Nepal                  | South Asia                     | 5.269        |


![Tabla Ejercicio 2](https://github.com/FLD1990/BigDataProcessingKc/raw/main/Tablas/Tabla%20Ejercicio%202.png)


3. País que más veces ocupó el primer lugar en todos los años:
   *Los paises que mas veces han ocupado el primer lugar son Dinamarca y Finlandia, ambos con 7 veces a los largo de la muestra.*

![Tabla Ejercicio 3](https://github.com/FLD1990/BigDataProcessingKc/raw/main/Tablas/Tabla%20ejercicio%203.png)

   
4. Puesto de Felicidad del país con mayor GDP del 2020:
 *El pais que tiene mayor GDP durante el año 2020 es Ireland, que ocupa en el ranking el puesto 13 de "Ladder Score" pero el primero de GDP*

![Tabla Ejercicio 4](https://github.com/FLD1990/BigDataProcessingKc/blob/main/Tablas/Tabla%20ejercicio%204.png)

5. Variación porcentual del GDP promedio a nivel mundial (2020 respecto al 2021) y si aumentó o disminuyó:
  *La variación es de - 3,27% por lo que disminuyó respecto al año precedente*

|    |   Year |   Average Logged GDP per capita |   Change | Change Type   |
|---:|-------:|--------------------------------:|---------:|:--------------|
|  0 |   2020 |                         9.75133 |  0       | -             |
|  1 |   2021 |                         9.43221 | -3.27259 | disminuyó     |

   
6. País con mayor expectativa de vida y su indicador en el 2019:
    *El país con mayor esperanza de vida en 2019 fue Singapur con un valor de 77,10 años*

|    | Country name   |   year |   Healthy life expectancy |   Yearly Difference |
|---:|:---------------|-------:|--------------------------:|--------------------:|
|  0 | Japan          |   2005 |                    73.2   |          nan        |
|  1 | Singapore      |   2006 |                    73.6   |          nan        |
|  2 | Singapore      |   2007 |                    73.9   |            0.3      |
|  3 | Singapore      |   2008 |                    74.2   |            0.3      |
|  4 | Singapore      |   2009 |                    74.5   |            0.3      |
|  5 | Singapore      |   2010 |                    74.8   |            0.3      |
|  6 | Singapore      |   2011 |                    75.02  |            0.22     |
|  7 | Japan          |   2012 |                    74.16  |            0.96     |
|  8 | Singapore      |   2013 |                    75.46  |            0.44     |
|  9 | Singapore      |   2014 |                    75.68  |            0.22     |
| 10 | Singapore      |   2015 |                    75.9   |            0.22     |
| 11 | Singapore      |   2016 |                    76.2   |            0.3      |
| 12 | Singapore      |   2017 |                    76.5   |            0.3      |
| 13 | Singapore      |   2018 |                    76.8   |            0.3      |
| 14 | Singapore      |   2019 |                    77.1   |            0.3      |
| 15 | Japan          |   2020 |                    75.2   |            1.04     |
| 16 | Singapore      |   2021 |                    76.953 |           -0.147    |
| 17 | Average        |    nan |                   nan     |            0.356867 |


![Tabla Ejercicio 6](https://github.com/FLD1990/BigDataProcessingKc/blob/main/Tablas/Tabla%20Ejercicio%206.png)
