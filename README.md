# Modelo-de-Vasicek-para-Tasas-de-Interes
El modelo de Vasicek es un modelo de Ornstein Uhlenbeck en el campo de finanzas, usado para modelar curvas de tasas de interes de corto plazo. Se define a partir de una ecuacion diferencial estocastica y es un modelo base cuyas modificaciones dan lugar a modelos como el de CIR (Cox - Ingersoll - Ross) o el modelo de Hull and White

## Estructura
Este repositorio contiene un desarrollo completo del modelo de Vasicek mediante Simulacion Estocastica. En la carpeta **presentation** se encuentra una presentacion con diapositivas didacticas el tema, asi como un proyecto final en donde se explica todo el desarrollo escrito en modo reporte / informe. 

La carpeta **src** esta compuesta por los codigos en lenguaje **R** por etapas del desarrollo del proyecto, las cuales son:

-  1. Simulacion de Trayectorias :

-  2. Estimacion de Parametros :

-  3. Intervalos de confianza y otras estadisticas :

-  4. Montecarlo vs Montecarlo + Bootstrap : 
  
-  5. Valuacion de Instrumentos :
 
Estan escritos en R Markdown para poder obtener visualizaciones en forma de reportes de cada una de las etapas, estos se ubican en la carpeta **reports**. Por ultimo, en **data** se ubican los datos historicos de banxico usados para la parte final de valuacion de instrumentos
