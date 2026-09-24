![MonoFabOG](recursos/archivos/MonoFabOG.png){ width="800" style="display: block; margin: 0 auto;" }

![Sacrificio](recursos/archivos/Sacrificio.jpg){ width="800" style="display: block; margin: 0 auto;" }

El VPanel es el software de control virtual para la máquina monoFab y funciona como el panel de mando en la computadora para operarla manualmente. Desde este programa se realizan los ajustes principales antes de enviar a cortar, tales como mover la herramienta sobre los ejes para establecer el punto de origen (0, 0, 0) y cargar los archivos de mecanizado.

Sin embargo, antes de mover la máquina, se debe preparar la placa de sacrificio: fija la PCB firmemente a su superficie utilizando cinta doble cara para garantizar que no se suelte durante el corte. La placa cuenta con perforaciones en sus cuatro esquinas para poder atornillarla de forma segura a la cama de la MonoFab. Finalmente, utilizando una llave Allen, coloca o cambia las fresas necesarias para que el equipo quede listo para la operación.

![MonoFabX](recursos/archivos/MonoFabX.png){ width="800" style="display: block; margin: 0 auto;" }

Para comenzar, se configura primero el origen en X e Y. Utiliza el panel de navegación de ejes hasta comprobar visualmente que la herramienta se encuentra cerca de la esquina inferior izquierda de la placa. Una vez en la posición deseada, haz clic en el botón de la derecha que indica "X/Y". Aparecerá una ventana de aviso para confirmar la asignación del nuevo origen en ese punto, el cual deberás aceptar.

![MonoFabZ](recursos/archivos/MonoFabY.png){ width="800" style="display: block; margin: 0 auto;" }

A continuación, se procede a configurar el origen en Z. Este paso requiere precaución: primero, enciende el motor de la fresa haciendo clic en el botón "ON" ubicado en la esquina inferior izquierda. Con la fresa girando, bájala con cuidado hasta rozar la placa PCB. El objetivo es rayar ligeramente la superficie sin atravesarla (lo cual se comprueba visualmente cuando comienza a soltar polvo).

Para evitar accidentes y no romper la herramienta, ajusta la velocidad de desplazamiento utilizando los selectores "Continuo, x100, x10, x1"; de este modo, los movimientos serán cada vez más lentos conforme te acerques a la base, reduciendo el riesgo de dañar la placa o la fresa. Tan pronto como la fresa empiece a marcar la PCB, apaga el spindle con el botón "OFF" y fija el origen en Z presionando el botón "Z" situado en el panel derecho.

![MonoFabCut](recursos/archivos/MonoFabCut.png){ width="800" style="display: block; margin: 0 auto;" }
![MonoFabExportar1](recursos/archivos/MonoFabExportar1.png){ width="800" style="display: block; margin: 0 auto;" }

Una vez que los orígenes estén configurados correctamente, haz clic en "CUT" en la esquina inferior derecha. En la nueva ventana, selecciona y carga el archivo que deseas cortar y presiona "Output" para que la máquina comience a trabajar.

El orden de corte recomendado es el siguiente:

Perforaciones: utilizando la fresa de 0.8 mm.

Pistas y etiquetas: utilizando la fresa de 0.4 mm.

Contorno de la PCB: utilizando la fresa de 2.0 mm.

Finalmente, es importante recordar que al finalizar cada etapa de corte se debe cambiar la fresa según corresponda para la siguiente tarea, por lo que el eje Z deberá configurarse nuevamente cada vez que se realice un cambio de herramienta.
