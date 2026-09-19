![MODSinicio](recursos/archivos/MODSinicio.png){ width="250" style="display: block; margin: 0 auto;" }

MODS CE (community edition) is a fork of CBA mods research project. mods is a modular cross platform tool for fablabs. It is based on independent but interrelated modules. mods could potentially be used for CAD, CAM, machine control, automation, building UI, read input devices, react to to physical models, and much more. The possibilies are endless.
The goal of the community edition is to provide documentation, support and help the community engage in the project and foster the development/exchange of new modules.

![MODSinsertar](recursos/archivos/MODSinsertar.png){ width="250" style="display: block; margin: 0 auto;" }

Para insertar un archivo se va a la sección para leer el SVG, después de seleccionar el archivo puedes comenzar la edición de diferentes parámetros, por ejemplo invertir la zona que será cortada, el diámetro de la herramienta, la velocidad de la cortadora, así como el sistema de medición. Es importante tomar en cuenta que todo lo que esté de color negro en el archivo será la zona en la que se hará el corte.

![MODSinvertir](recursos/archivos/MODSinvertir.png){ width="250" style="display: block; margin: 0 auto;" }

Se pueden cambiar las especificaciones de las herramientas directamente, si las preestablecidas no se adecuan a las dimensiones que serán utilizadas en el proceso de la fabricación de la pcb.

![MODSherramienta](recursos/archivos/MODSherramienta.png){ width="250" style="display: block; margin: 0 auto;" }

Se puede cambiar el origen de la cortadora directamente en el mods, es necesario cambiarlo manualmente a un origen (0,0,0) ya que el mods automáticamente lo pone en (10,10,10). En la mayoría de los casos vas a querer un origen (0,0,0), a menos que vayas a hacer muchos cortes a la vez, como lo puede ser más de una pcb.

![MODScalcular](recursos/archivos/MODScalcular.png){ width="250" style="display: block; margin: 0 auto;" }

La velocidad de trabajo de la cortadora es un parametro muy importante, asi no existe el riesgo de romper la punta por demasiada velocidad, especialmente en las perforaciones en la pcb.
Para contorno, pistas y etiquetas la velocidad recomendada es 4 mm/s.
Para perforaciones la velocidad recomendada es de 0.2 a 0.4 mm/s.

![MODSorigenes](recursos/archivos/MODSorigenes.png){ width="250" style="display: block; margin: 0 auto;" }

![MODSsvg](recursos/archivos/MODSsvg.png){ width="250" style="display: block; margin: 0 auto;" }
