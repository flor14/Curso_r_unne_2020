# Introducción al lenguaje R

17 de septiembre de 2019 - Universidad Nacional de Salta  

[Tutorial de las 48 JAIIO](http://48jaiio.sadio.org.ar/Simposios/Tutoriales)

----------

_Mg. Yanina Bellini Saibene - [INTA Anguil.](https://inta.gob.ar/personas/bellini.yanina)_ 
<a href="https://twitter.com/yabellini" class="twitter-follow-button" data-show-count="false">Twitter</a>

_Dra. Maria Florencia D'Andrea - [Instituto de Recursos Biológicos.](https://inta.gob.ar/personas/dandrea.florencia)_
<a href="https://twitter.com/cantoflor_87" class="twitter-follow-button" data-show-count="false">Twitter</a>

----------
<img src="https://github.com/flor14/r_cai_2019/blob/master/flyer.jpg?raw=TRUE">  


----------
## Cronograma

9 hs

- Introducción y tidyverse. 
- Trabajar con Proyectos.

10.30 - 11 hs. (Intervalo)

- Gráficos. Ggplot2 y RMarkdown.
- Sacar un DOI a un dataset.

13 hs

----------
## Material del curso
#### ¿Cómo instalar R y RStudio? 
 Para una mejor experiencia sugerimos acercarse con una computadora personal con R y RStudio instalados (pero esto no es excluyente). Información en este [Link](https://github.com/pachamaltese/tutoriales/blob/master/2019-04-24-instalar-r.md) para distintos sistemas operativos.
 
#### Filminas

[Filminas parte 1](https://github.com/flor14/r_cai_2019/blob/curso/Curso_parte1_CAI_2019.pdf?raw=TRUE) 

[Filminas parte 2](https://github.com/flor14/r_cai_2019/blob/curso/Curso_parte2_CAI_2019_yani.pdf?raw=TRUE) 

[Live coding 1 - RStudio y Proyectos](https://github.com/flor14/r_cai_2019/blob/curso/r_rstudio_proyectos_CAI.R)

[Live coding 2 - Pipes y Tidyverse](https://github.com/flor14/r_cai_2019/blob/curso/df_pipes_tidyverse_CAI.R)

[Live coding 3 - Gráficos 1](https://github.com/flor14/r_cai_2019/blob/curso/Graficos_Parte1_CAI.R)

[Live coding 4 - Gráficos 2](https://github.com/flor14/r_cai_2019/blob/curso/Graficos_Parte2_CAI.R)

[Live coding 5 - Gráficos 3](https://github.com/flor14/r_cai_2019/blob/curso/Graficos_Parte3.R)

[Live coding 6 - Mapas y plotly](https://github.com/flor14/r_cai_2019/blob/curso/muestra_mapas_plotly_CAI.R)

[Base de datos](https://github.com/flor14/r_cai_2019/blob/curso/gapminder.csv)

Parte práctica [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/flor14/r_cai_2019/curso?urlpath=rstudio)

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/deed.es_ES"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /> Las filminas y código asociado se encuentran bajo licencia <a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/deed.es_ES">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

#### Referencias principales

* [Gandrud, C. (2016). Investigación reproducible con R y R studio. Chapman y Hall / CRC](https://github.com/christophergandrud/Rep-Res-Book)
* [Ismay C, Kim A. (2019) Moderndive. Statistical Inference via Data Science. A moderndive into R and the tidyverse.](https://moderndive.com/)
* [Marwick B.,  Boettiger C. & Mullen L. (2018) Packaging Data  Analytical Work Reproducibly Using R (and Friends), The American Statistician, 72:1, 80-88](https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1375986)
* [Thieme, N. (2018). R generation. Significance, 15(4), 14–19. 
](https://rss.onlinelibrary.wiley.com/doi/10.1111/j.1740-9713.2018.01169.x)
* [Xie, Y., Allaire, J. J., & Grolemund, G. (2018). R markdown: The definitive guide. Chapman and Hall/CRC.](https://bookdown.org/yihui/rmarkdown/)
* [Wickham, H. (2015). R packages: organize, test, document, and share your code. " O'Reilly Media, Inc.".](http://r-pkgs.had.co.nz)
* [Wickham, H., & Grolemund, G. (2016). R for data science: import, tidy, transform, visualize, and model data. " O'Reilly Media, Inc.". (EN ESPAÑOL)](https://es.r4ds.hadley.nz/)

#### Sitios de consulta

* [Machetes de RStudio](https://www.rstudio.com/resources/cheatsheets/)
* [Data to Viz. Consejos para generar gráficos con código R](https://www.data-to-viz.com/) 
* [R Cook Book BBC. Gráficos al estilo de la BBC](https://bbc.github.io/rcookbook) 
* [R Graph Gallery. Ejemplos para generar gráficos con código R](https://www.r-graph-gallery.com/) 
* [Guía para chequear estilos de gráficos](https://datavizchecklist.stephanieevergreen.com/assets/DataVizChecklist_Feb2018.pdf)
* [Paquete DataSaurus](https://cran.r-project.org/web/packages/datasauRus/vignettes/Datasaurus.html) 
* [Guía de estilo de código](https://style.tidyverse.org/)
* [Happy Git and GitHub for the useR - Jenny Bryan, the STAT 545 TAs, Jim Hester](https://happygitwithr.com/)
* [What they forgot to teach you about R - Jenny Bryan](https://whattheyforgot.org/)
* [Git for Humans](https://speakerdeck.com/alicebartlett/git-for-humans)

#### Material en español
* [Ciencia de datos para curiosos - Martín Montané](https://bookdown.org/martinmontaneb/CienciaDeDatos/)
* [Fundamentos de la Programación Estadística y Data Science en R - Versión tidyverse - German Rosati](https://github.com/gefero/tidy_fund_prog_r)
* [Ciencia de datos para gente sociable - Vazquez Brust](https://bitsandbricks.github.io/ciencia_de_datos_gente_sociable/)
* [El arte de programar en R - Julio Sergio Santana & Efraín Mateos Farfán [español]](http://bit.ly/2N2Y1Y8)
* [Introducción a tidyr: Datos ordenados en R (Rpubs) [español]](http://bit.ly/2AaWV9T)
* [Visualización estática e interactiva con ggplot2 y plotly [español]]( http://bit.ly/2xI2dqH)
* [Curso de R para procesamiento de datos de la Encuesta Permanente de Hogares - Diego y Natsu](https://diegokoz.github.io/Curso_R_EPH_clases/)

## Comunidades
 
 * [R-Ladies Global](https://rladies.org/) 
 * [R-Ladies Buenos Aires (twitter)](https://twitter.com/rladiesba?lang=es) 
 * [R-Ladies Santa Rosa (twitter)](https://twitter.com/RLadiesSR) 
 * [R-Spatial en español (grupo de Telegram)](https://web.telegram.org/#/im?p=@rspatial_es)
 * [R en Buenos Aires](https://renbaires.github.io/)
 * [ROpenSci](https://ropensci.org/)
 * [R4DS en Español (twitter)](https://twitter.com/r4ds_es?lang=es)
 * [The Carpentries](https://carpentries.org/)
 
## Congresos regionales
 
 * [LatinR](http://latin-r.com)
 * [Congreso Argentino de Agroinformática](http://48jaiio.sadio.org.ar/simposios/CAI)
 
## Encuesta final

Te pedimos si pudieses contestar esta breve encuesta como devolución del curso. ¡Gracias por asistir!
[Encuesta final]()



