# USAID_PNUD_Toma_decisiones_basada_en_evidencia-
Este repositorio contiene  los códigos y ejercicios que se realizan en el marco de la transferencia de conocimiento  organizada por USAID y PNUD. Este es administrado, actualizado y mantenido por el Área para la Reducción de Pobreza  e Inequidades de PNUD Colombia
 
 # 1. Instalación R y R Studio 
 
 Para poder instalar R y R studio en su computador, dirijase al archivo "Instructivo Instalación R y R Studio.pdf" ( el cual se encuentra colgado en el banner del repositorio).  
 
 <img width="698" alt="Captura de Pantalla 2022-12-26 a la(s) 5 48 16 p m" src="https://user-images.githubusercontent.com/73482880/209587182-60b1d575-c44f-4e4f-9ebd-d14cef120389.png">
 
 Al abrir este instructuvo, encontrará el paso a paso de como instalar  R y R Studio en un sistema operativo windows.
 
<img width="988" alt="Captura de Pantalla 2022-12-26 a la(s) 5 51 21 p m" src="https://user-images.githubusercontent.com/73482880/209587265-fc9c2361-14a6-4466-aa16-e95b5bfc94dd.png">

Una vez instalado R y R studio continue con el paso 2 "Primeros pasos en R"

 # 2. Primeros pasos en R
 
Una vez haya instalado y verificado que el programa  corre, deberá instalar los paquetes y librerias básicas  de R para poder explorar sus diferentes funcionalidades. Para familiarizarse con la interface del programa le recomendamos ver el siguiente video: https://www.youtube.com/watch?v=skPzCkvr8Cw



Es importante que sepa que existen diferentes metodos para instalar paquetes en R, en el presente instructivo se muestra la forma más sencilla e intuitiva de hacerla, no obstante la redacción de un código dependerá del nivel y sofisiticación que cada programador le de a este.

 Para instalar paquetes debe asegurarse de introducir el siguiente comando: 
```ruby
install.packages 
 ```
 Este le permitirá descargar e instalar archivos de repositorios en línea. Seguido a esto se deben instalar los siguientes paquetes con sus respectivas  liberias:
 
```ruby
install.packages("tidyverse") # tidyverse y dplyr son dos de los paquetes que mayor número de acciones permiten en R, se recomienda siempre instalarlos 
install.packages("dplyr")
library(tidyverse)
library(dplyr)
library(ggplot2) # Esta libreria le permitirá hacer gráficas
library("readxl") # Permite leer documentos Excel
library(tmap) # Permite hacer mapas estáticos e interactivos 
library(scales) # Permite introducir escala a mapas
library(gganimate) # Permite generar gráficas dinámicas
library(sf)# Permite integrar vectores espaciales 
library(raster)# Permite analizar y manipular datos espaciales
library(spData) # Integra datos espaciales de diferentes formatos 
library(spDataLarge) # Integra datos espaciales de diferentes formatos 
library(tmap)    # for static and interactive maps
library(leaflet) # for interactive maps
 ```
 
Los anteriores son paquetes básicos que se utilizarán adelante, no obstante R cuenta con un gran número de paquetes, de los cuales puede aprender en el siguiente link:  https://cran.r-project.org
 
 # Analítica de datos

En este repositorio encontrará difirentes scripts que le permitirán procesar los  microdatos de  las principales fuentes estadísticas de Colombia. 

## Bases disponibles 

Base | Temas | Función| Formato
------------ | -------------| ----------|--------|
GEIH| Unión de bases  |  Permite unir los diferentes módulos de la Gran Encuesta Integrada de hogares | R
GEIH|  Mercado Laboral | Permite obtener los principales indicadores del mercado laboral colombiano |  R
GEIH | Pobreza|  Permite  calcular ingresos  reales por quintíl para ciudades capitales | STATA


**Los  scripts permiten  utilizar los microdatos publicados por el DANE, en este repositorio no encontrará  los microdatos para acceder a estos debera ir al Archivo Nacional de Datos del DANE - ANDA, en el siguiente link**: https://sitios.dane.gov.co/anda-index/
