## Trabajo práctico final de la asignatura DCI ##
Este repositorio contiene el trabajo práctico final para la asignatura de Diseño de Circuitos Impresos de la carrera de posgrado de FIUBA.

* Autor: Ismael Farid Marquez Quila
* Título corto del trabajo:  Shield_Datalogger
* Descripción: Placa tipo Shield de 2 capas compatible con placas STM32 Nucleo-64 (conectores Morpho) que consolida un sensor inercial IMU de 6 ejes (LSM6DS3 mediante bus I2C) y un zócalo lector de tarjetas MicroSD (mediante bus SPI) en un único circuito impreso compacto. Su objetivo es la adquisición y almacenamiento local de datos inerciales (datalogger) operando a 3,3 V, diseñado bajo criterios de integridad de señal (plano de tierra continuo GND en la cara inferior, capacitores de desacoplamiento locales, pistas de 0,15 mm para señales y 0,51 mm para alimentación) y encapsulados SMD 0805 aptos para soldadura manual.
* Cursada: OCT-NOV-DIC 2026


## Licencia de este trabajo ##
Este diseño de hardware abierto se publica bajo la licencia **CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P-2.0)**, siguiendo las recomendaciones de la Open Source Hardware Association (OSHWA).

## Estructura del TP FINAL ##

Se propone y se pide utilizar la siguiente estructura.

* doc: Toda la información sobre el circuito, principalmente de autoría o procesamiento propio. Por ejemplo:
  * Notas de ingeniería propias.
  * Notas de aplicación propias.
  * Estudios previos, estado del arte, resumen de las investigaciones.
  * Notas con cálculos.
  * Dibujos adicionales.
  * Fotos de los prototipos.
  * Presupuestos, cotizaciones.
* info: Toda la iformación recolectada, principalmente de terceros, como por ejemplo:
  * Hojas de datos.
  * Notas de aplicación.
  * Info de productos comerciales.
  * Info en internet.
* pcb: Archivos de diseño esquemático y pcb.

Dependiendo la magnitud del proyecto, tendremos más o menos información en estos directorios. 
Revisar los README.md en cada directorio para conocer las pautas de cada uno para este TP.

NOTA: El alumno puede y debe borrar de este archivo todo lo que considere necesario, por ejemplo las aclaraciones del docente y esta misma nota.

## Obligatorios para el TP Final ##
* doc/propuesta/README.md (con textos y links, formato markdown, a imágenes que deben estar en el mismo repo. Las imágenes son las que se piden en las pautas de TP).
* info/*.pdf (Se piden solo las hojas de datos de los componentes relevantes como circuitos integrados, conectores particulares, módulos, etc. No es necesario poner hojas de pasivos, discretos comunes, conectores estándar.)
* pcb/* (Acá va el proyecto KiCad, modelos 3D, bibliotecas particulares y archivos generados como BOM, gerbers, etc.). EVITE subir al git archivos temporales de KiCad. Se recomienda usar un .gitignore adecuado.
* El alumnos es libre de agregar otras cosas, pero siempre tenga en cuenta que el repositorio es público. Evitar colocar información personal o documentación confidencial. 
