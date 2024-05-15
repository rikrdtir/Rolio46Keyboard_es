# Presentación
Esta es una versión en español del repositorio original, próximamente se irá traduciendo todos los archivos necesarios para que puedas armar tu propio teclado.

¡El Rolio46, es un teclado inalámbrico y ergonómico de 46 teclas,está en su versión 1.0! Este repositorio contiene todos los archivos de diseño para que puedas construir tu propio Rolio46.1.

![CNC 1.0 With travel Case](images/main.png?raw=true "CNC 1.0 With travel Case")

Este teclado próximamente tendrá una tienda especializada para quienes desean obtener este teclado pre soldado y/o armado, así como partes y componentes, para más detalles ver el repositorio original [aquí](https://github.com/MickiusMousius/Rolio46Keyboard), o la tienda que se abrirá próximamente [aquí](https://keydio.io).

Todos los archivos de diseño son y serán siempre de dominio público, el teclado Rolio46 depende en gran medida de productos de código abierto como [ZMK](https://zmk.dev), por lo cual pertenece a la comunidad para su mejora o mantenimiento.

# Características
Del teclado:
- Totalmente inalámbrico gracias a [firmware ZMK](https://zmk.dev)
- Excelente duración de batería, con una autonomía de más de dos semanas antes llegar al 60%.
- Bajo perfil, gracias a switches y keycaps de formato choc, con forma que es similar a la del muy popular Corne keyboar.
- Con mejoras como Botones adicionales en la fila inferior en comparación al antes mencionado corne.
- Encoders de rodillos horizontales en ambas mitades.
- Retroiluminación bastante eficiente para funcionar con baterías.
- Un chasis robusto y práctico.
  - Una versión FDM para la producción doméstica de bajo coste.
  - Un chasis SLS para un aspecto más refinado a un coste inferior que las opciones basadas en CNC.
  - Una opción CNC para un aspecto elegante y una sensación de alta calidad.
- Una maleta de viaje que puede fabricarse fácilmente con cualquier impresora FDM 

ZMK Keymap & teclas personalizadas:
- Hasta cinco perfiles bluetooth memorizados y un modo USB.
- Las teclas están totalmente personalizadas  gracias a [FKCaps](https://fkcaps.com/custom/FGE2DW)
- Modos MacOS y Windows para mantener las «mismas» macros en ambos SOs.
- Se puede acceder a todos los símbolos y comportamientos especiales utilizando como máximo dos teclas.
- Las teclas de configuración y los diferentes modos están documentados en las propias mayúsculas de las teclas (fácil de aprender).
- El keymap se puede personalizar fácilmente gracias a ZMK, las keycaps también se pueden personalizar para adaptarlas a tus necesidades.
   - Aquí tienes un punto de partida para hacer tus propias keycaps de teclas: [FKCaps](https://fkcaps.com/custom/FGE2DW)

[![Version 1.0 Key Caps](images/key_legend.png?raw=true "Version 1.0 Key Caps")](https://fkcaps.com/custom/FGE2DW)


# Construye tu propio rolio46.
Para construir un Rolio46.1 necesitas completar con estos 5 subconjuntos principales. Los enlaces proporcionan información detallada de los componentes y partes necesarias, pero descuida, te guiaremos paso a paso para que el proceso sea sencillo y puedas completar cada una de las subtareas, al terminar tendrás el teclado ergonómico perfecto:
 * [El controlador](doc/controller.md)
 * [La pantalla](doc/display.md)
 * [Baterias](doc/battery.md)
 * [Placa electrónica](pcb/README.md)
 * [El chasis / carcasa](chassis/README.md)

Las placas electrónicas y el chasis son componentes exclusivos de este proyecto, todos los demás subconjuntos son intercambiables, y probablemente ya conozcas o hayas visto en otros teclados.

# Firmware

Puede descargar el firmware más reciente desde aquí: [versiones](https://github.com/MickiusMousius/RolioKeyboard/releases)

Si quieres personalizar el firmware (o crear tu propio layout) haz un fork del siguiente repositorio: [RolioFirmware](https://github.com/MickiusMousius/RolioFirmware)

Cuando introduzcas un cambio en tú fork GitHub action creará una nueva compilación de firmware para ti.


# Otros componentes

<ins>Keycaps</ins>

Este teclado ha sido diseñado para utilizar MBK keycaps. No obstante, debería poder utilizar cualquier keycap compatible con Choc.

También puedes ordenar un juego de teclas personalizadas a varios proveedores.

El diseñador del teclado ha creado un juego de keycaps personalizado en FKCaps, el keymap del teclado ha sido integrado en las teclas. Estas keycaps las  puedes encontrar [AQUÍ](https://fkcaps.com/custom/FGE2DW).

<ins>Switches</ins>

El Rolio46 está diseñado para su uso con interruptores Choc V1, que pueden adquirirse de muchos proveedores diferentes. 

# Próximamente
 * Modelos de estuches de transporte
 * Publicar los modelos del kit de tienda de campaña
 * Mejoras en las placas base y los amortiguadores para mejorar el perfil de sonido.

# Galería

![](images/case.png)

![](images/all_three.png)
