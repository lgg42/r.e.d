![App Image](https://raw.githubusercontent.com/lgg42/r.e.d/master/img/ti89red.gif)

## Introducción

Redes Eléctricas de Distribución (R.E.D) tiene carácter docente y se recomienda su uso a estudiantes que quieran comprobar sus resultados de problemas realizados a mano; también es apto para comprobar como influyen diversos factores en una red de distribución urbana (RDU), como puede ser la instalacion de bancos de condensadores, cambio de calibre a los alimentadores, cambio del nivel de tensión, etc. El objetivo principal del programa es resolver flujos de cargas en RDU's por el metodo de Haque, obteneniendo los resultados de: tensiones en los nodos (o postes) y caídas de tensión, pérdidas, potencias en envio y recibo por tramos. Se puede correr el flujo a partir de los datos de las demandas por poste o teniendo las capacidades instaladas de los transformadores y estimando la demanda mediante el método de Ardvinson, o finalmente, usando la combinación de estos dos métodos. 
También, se puede crear el perfil de tensión de la RDU una ves corrido el flujo y compararlo con otros nuevos perfiles creados a partir de los resultados de nuevos flujos. Los datos necesarios para correr el flujo, y los resultados de este, son guardados en forma matricial, por lo tanto pueden ser leídos y/o editados mediante el editor de datos y matrices que incorpora por defecto el sistema operativo de las TI-89 y TI-89 Titanium. En adicíon, usando la aplicación FLASH Cellsheet TM y el software TI-Cellsheet TM Converter se pueden exportar (e importar) los datos y  resultados finales a una hoja de cálculo en formato compatible para programas de tal proposito como OpenOffice.org Calc o Microsoft Excel. Finalmente, se debe aclarar que este programa esta restringido al uso en redes con topologia radial, y que poseean un desbalance menor que el 12 %.

## Instalación

Para instalar R.E.D, utilice su programa preferido de conectividad para la calculadora (TI-Connect, Tilp, etc) y agregue el archivo de grupo red.89g. Se creará automaticamente una nueva carpeta llamada “RED” que contiene los diversos programas y funciones que utiliza R.E.D. Estos estarán archivados y es necesario que permanezcan de tal forma, pues una operación de “reset” a la RAM provocaría la pérdida del programa o función que no este archivado y por tanto la inoperabilidad del paquete R.E.D. De ocurrir esta situación, será necesario volver a copiar el archivo eliminado o re-instalar el paquete de programas.

## Edición

Clonar el repositorio, realizar la instalación en la calculadora y editar los archivos con las herramientas incorporadas.
