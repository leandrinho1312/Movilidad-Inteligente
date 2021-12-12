# Movilidad-Inteligente
Proyecto para mejorar la movilidad vehicular.

## Descripcion
Este proyecto pretende ayudar al Quindío, y específicamente al municipio de Armenia a encaminarse a convertirse en una ciudad o territorio inteligente según lo estipulado en el Plan de Desarrollo Nacional 2018-2022 (Pacto por Colombia, Pacto por la Equidad), enfocándose en la subdimensión de movilidad inteligente, donde se pretende mejorar la movilidad vehicular en el centro de la ciudad, optimizando el uso de las zonas de parqueo públicas y de los principales parqueaderos, mediante un software o aplicación la cual al estar finalizado su desarrollo, enviará información en tiempo real de la disponibilidad de cupos tanto en zonas de parqueo públicas como en los parqueaderos del centro de la ciudad. Este proyecto se enfoca en el modelado de dicha aplicación para servir de base para su posterior realización. Para el proyecto se tuvo en cuenta la estrategia CDIO (concebir, diseñar, implementar y operar) el cual en este documento se profundizará en las etapas de implementar y operar, en el cual se verificará su correcto funcionamiento del software y del hardware implementándolo en la universidad del Quindio. Además se tuvo en cuenta el documento que se realizó en las etapas de concebir y diseñar en las que se realizaron diferentes etapas de investigación y análisis para determinar qué tan viable era el proyecto. Para el diseño de dicho modelo fue necesario realizar las diferentes etapas de diseño (analizar las alternativas de diseño, especificación de diseño técnico, diseño preliminar y diseño detallado).

## Problematica
Se identificó que en la ciudad de Armenia se presentan varios problemas de movilidad, ya que muchos vehículos estacionan en zonas prohibidas, ocupando una parte de los carriles generando atascos; esto ocurre debido a que los diferentes conductores y/o propietarios de los vehículos no tienen conocimiento de los diferentes espacios disponibles para el aparcamiento de sus vehículos en la zona donde se encuentran.

Una de las mayores ventajas con la implementación de este sistema es la mejora en la movilidad vehicular, teniendo que el parqueo de vehículos será más ordenado, de modo que los conductores tendrán mayor facilidad en la búsqueda de zonas de parqueo (zonas azules) y parqueaderos cercanos a su lugar de destino, siendo posible una descongestión vehicular ya sea en la búsqueda de un zona de parqueo o de vehículos que están mal parqueados; siendo uno de los primeros pasos para convertir a Armenia en una ciudad o territorio inteligente.

## Zonas azules
En las zonas azules se tiene el diseño del circuito que cuenta con un microcontrolador arduino nano, que va conectado a un shield del arduino nano, un modulo WiFi Esp8266-01s y los sensores infrarrojos E18-d80nk, los cuales permitiran conocer los cupos disponibles en determinadas zonas azules. Ademas, el circuito tiene como alimentacion el uso de dos paneles solares, dos pilas de litio y un cargador de baterias Tp4056, teniendo una autonomia de todo el dia con los paneles y por la noche con las pilas.

<img src="https://user-images.githubusercontent.com/47339991/145722558-3766c400-09a9-4b80-94ac-2775a50307a9.jpeg" height="400">

## Aplicacion para los administradores
Para los administradores de los parqueaderos se empleara una aplicacion que permitira indicar cuantos cupos disponibles hay en el parqueadero, la cual puede ser utilizada a traves de un celular. La programación de esta aplicacion se realizoa través de la herramienta Android Studio que tiene un lenguaje de programacion java.

<img src="https://user-images.githubusercontent.com/47339991/145721947-7144ccbd-cffb-42f2-b5e5-53f44005af9e.jpeg" width="200" height="400">

## Aplicacion para los usuarios
Para la presentación de la información de los parqueaderos y zonas de parqueo se tiene el diseño de una aplicación la cual puede ser usada por los usuarios a través de un celular, la programación de esta aplicacion se realizo a través de la herramienta android studio que tiene un lenguaje de programacion java. 

<img src="https://user-images.githubusercontent.com/47339991/145721895-da936898-36b2-4ce2-ae3e-f21e50ed26fb.jpeg" width="200" height="400">
