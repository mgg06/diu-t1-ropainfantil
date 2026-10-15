# Documentación de la interfaz - Pequeño Davante

## 1. Justificación del diseño

### 1.1 Importancia del diseño centrado en el usuario

Al plantear la app de Pequeño Davante, me he centrado en cómo la usaría alguien que entra a comprar ropa infantil desde el móvil, Muchas veces será una madre, un padre o un familiar que tiene poco tiempo y mira la tienda mientras hace otra cosa, Por eso he intentado que las opciones principales se vean sin tener que ir abriendo menús

Una de las cosas que más dudas puede dar es la talla, Saber los años que tiene un niño no siempre sirve para acertar con la ropa, He dejado la guía en la propia ficha, al lado del selector de talla, para poder consultarla sin salir de la prenda, Las tallas sin stock tienen un estado distinto para no confundirlas con las disponibles

El botón de añadir al carrito está en la parte baja de la pantalla para tenerlo más a mano, En el carrito aparecen la cantidad y el importe, y en el formulario de entrega hay un ejemplo de email incorrecto con un mensaje de ayuda, Me interesa que se entienda qué hay que hacer en cada paso y cómo corregir un error

### 1.2 Objetivos y metas del proyecto

Para comprobar si el diseño se entiende, he marcado cuatro objetivos, Los tres primeros se medirán en las pruebas con al menos dos compañeros de otro grupo, El último se comprobará con los colores de la guía de estilo

- Completar la compra de la chaqueta en verde oliva, talla 4 y cantidad 2 en menos de dos minutos y sin ayuda, Contaré desde Inicio hasta Confirmación, La tarea consiste en encontrar la chaqueta, elegir la talla y revisar la cantidad antes de confirmar
- Encontrar y abrir la guía de tallas desde el detalle en menos de diez segundos, sin indicar dónde está, Apuntaré si la encuentran a la primera o si antes pulsan en otro sitio
- Corregir el error de email y continuar desde Entrega sin ayuda, Mediré el tiempo y los intentos fallidos para ver si el mensaje explica bien qué hay que cambiar
- Revisar que todas las parejas de color y texto de la guía tengan un contraste mínimo de 4,5 a 1, tanto en claro como en oscuro, Los valores quedarán en el apartado 3.3

Son objetivos para las pruebas, no resultados que ya haya conseguido, Como participarán pocos compañeros, recogeré lo que le ocurra a cada uno sin sacar porcentajes sobre todos los posibles clientes

### 1.3 Beneficios esperados

Para quien compra, la idea es poder consultar la talla, ver el precio y revisar la cantidad sin ir saltando entre pantallas, Si el formulario explica qué dato está mal, debería ser más fácil corregirlo y seguir con la compra

Para la tienda, una guía de tallas clara podría evitar algunas dudas y compras equivocadas, Un proceso fácil de seguir podría ayudar a que menos personas dejen el carrito a medias, De momento son beneficios que espero del diseño, Para saber si bajan las devoluciones o suben las ventas haría falta probar la app con clientes reales

## 2. Investigación y análisis de usuarios

### 2.1 Datos demográficos y segmentación

Pequeño Davante está pensada para personas adultas que compran ropa y calzado para niños de 0 a 14 años desde un móvil Android, Quien usa la app y decide la compra no tiene por qué ser quien va a llevar la prenda, Esto importa sobre todo al hacer un regalo, porque se puede conocer la edad del niño sin saber su talla

He dividido el público en tres grupos según la situación de compra, Las edades son orientativas y me sirven para plantear los perfiles, no salen de una encuesta

| Grupo | Situación de compra | Qué necesita resolver | Qué debo tener en cuenta en el diseño |
| --- | --- | --- | --- |
| Padres y madres, aproximadamente de 30 a 45 años | Reponen ropa que se ha quedado pequeña o buscan prendas para otra temporada, Pueden consultar el catálogo en ratos cortos | Localizar una prenda, comprobar la talla y revisar el importe antes de terminar | Categorías visibles, precio junto a la prenda y controles de cantidad en el carrito |
| Familiares y amigos, aproximadamente de 20 a 30 años | Compran un regalo de forma puntual y pueden tener poca información sobre las medidas del niño | Entender las tallas y completar la compra sin tener que crear una cuenta | Guía de tallas accesible desde el detalle y recorrido de compra sin un paso de registro |
| Abuelos y otros familiares, aproximadamente de 60 a 75 años | Buscan una prenda para un nieto y pueden preferir revisar cada paso antes de confirmar | Leer los datos con comodidad, reconocer las acciones y corregir una equivocación | Texto con contraste, botones con etiqueta, áreas táctiles amplias y opción de deshacer al eliminar |

La edad no dice por sí sola cómo usa alguien el móvil, Una persona joven puede perderse con las tallas y una persona mayor puede comprar online sin problemas, Me he fijado en lo que necesita resolver cada perfil

He tenido en cuenta las compras en ratos cortos y el uso del móvil con una mano, porque en esas situaciones cuesta más acertar con botones pequeños o recordar datos de otras pantallas

### 2.2 Personas

He creado tres perfiles para tener en cuenta distintas formas de comprar, Son perfiles ficticios que me sirven para relacionar cada necesidad con una decisión de diseño

#### Persona 1 - Laura, 36 años

- Laura tiene dos hijos y suele encargarse de comprarles la ropa, Mira la tienda por la noche, cuando tiene un rato, y a veces deja una compra a medias
- Quiere encontrar una chaqueta, comprobar si queda su talla y ver cuánto cuestan dos unidades
- Le molesta entrar en una prenda y descubrir después que no hay stock, Si deja la compra para otro día, quiere poder volver a lo que le había gustado
- Para ella he tenido en cuenta el precio visible en el catálogo, los estados de talla y Favoritos, El carrito reúne los controles de cantidad y el importe, El guardado de favoritos entre sesiones quedaría para una app real

#### Persona 2 - David, 25 años

- David busca un regalo para su sobrino, Sabe los años que tiene, pero no conoce sus medidas ni suele comprar ropa infantil
- Quiere entender qué talla elegir y comprar sin tener que crear una cuenta
- Le cuesta decidir si la talla aparece solo como un número, Tampoco quiere perder la ficha de la prenda al abrir la ayuda
- Por eso la guía se abre sobre el detalle y permite volver a la misma prenda al cerrarla, El recorrido está planteado sin un paso de registro, El archivo definitivo no tiene login ni un sistema de cuentas

#### Persona 3 - Alberto, 68 años

- Alberto quiere comprarle una prenda a su nieta, Usa el móvil para mensajes y algunas compras, pero prefiere ir despacio cuando no conoce una pantalla, Para este perfil he supuesto que necesita la letra más grande
- Quiere leer bien el precio, elegir la talla y comprobar que no ha añadido algo de más
- Le frustra no entender un icono o borrar un producto sin saber cómo recuperarlo
- Para él he tenido en cuenta las etiquetas de los botones, el contraste y las áreas táctiles, La opción Deshacer responde a su miedo a borrar algo por error, mientras que el mensaje del email le indica qué dato tiene que corregir

### 2.3 Análisis de la competencia

He revisado las webs y la ayuda en español de cuatro tiendas, Me he fijado sobre todo en las tallas y en los pasos para comprar, porque son las dudas que aparecen en los perfiles, La tabla separa lo que he podido comprobar de lo que yo cambiaría para Pequeño Davante, No he hecho compras ni probado sus apps Android

| Tienda | Qué hace bien | Qué veo mejorable o qué límite encuentro | Registro y acceso comprobado | Qué me llevo para Pequeño Davante |
| --- | --- | --- | --- | --- |
| Mayoral | Reúne fotos, precio, opciones de color, selección de talla y acceso a la guía en la ficha | La descripción combina información de la prenda con una explicación sobre el algodón, Para una consulta rápida, prefiero separar la selección de compra de ese contenido adicional | La ficha se puede consultar públicamente, Esta revisión no confirma si el pago exige una cuenta | Mantener foto, precio, talla y guía en el mismo detalle, con la acción de compra fácil de localizar |
| Vertbaudet | Explica cómo medir el pie e incluye una calculadora que parte de su longitud en milímetros, Da una referencia más concreta que la edad | La guía reúne muchos consejos por etapas, Para consultar una medida mientras elijo una prenda, prefiero una ayuda más breve y centrada en esa duda | La guía es pública, La página ofrece acceso a una cuenta, pero eso no demuestra que el registro sea obligatorio para comprar | Usar medidas y una explicación visual en la guía, Abrirla como panel sobre el detalle para poder volver a la prenda al cerrarla |
| Kiabi | Explica la compra como invitado, la confirmación por email y el seguimiento sin cuenta | El invitado no tiene el seguimiento desde una cuenta ni las ventajas de fidelidad, Me parece un límite que conviene explicar al elegir cómo comprar | Confirma que se puede continuar sin cuenta, Por tanto, no corresponde describir su registro como obligatorio | Dejar el inicio de sesión como opción, Para una futura app, explicar qué se guarda con una cuenta antes de pedir que se cree |
| Zara | Separa los temas de tallas, favoritos, pedidos y devoluciones en grupos reconocibles | La ayuda cubre muchos servicios de la marca, Para resolver una duda concreta sobre una talla, prefiero ofrecer un acceso desde la propia prenda sin obligar a buscar entre todos los temas | El índice de ayuda es público y contiene un apartado de registro, El índice por sí solo no permite confirmar las condiciones de compra sin cuenta | Mantener la guía junto al selector de talla y los destinos principales visibles en la navegación inferior |

De estas tiendas me quedo con la ayuda cerca de la talla y con no pedir una cuenta antes de mirar las prendas, En Pequeño Davante he intentado que la ficha y el carrito tengan la información necesaria para decidir sin llenarlos de opciones


### 2.4 Insights y hallazgos clave

De los perfiles y la comparativa he sacado estas seis ideas, cada una relacionada con una decisión de diseño y una forma de comprobar si se entiende

| Idea que orienta el diseño | De dónde sale | Decisión en Pequeño Davante | Cómo comprobarla |
| --- | --- | --- | --- |
| Conocer la edad del niño no resuelve por sí solo la elección de talla | David conoce la edad de su sobrino, pero no sus medidas | Poner la guía junto al selector de talla y abrirla como panel sobre el detalle | Pedir que consulten la guía y registrar si la encuentran sin ayuda y cuánto tardan |
| Una compra puede interrumpirse antes de tomar una decisión | Es una situación prevista en el perfil de Laura, no una frecuencia medida | Incluir Favoritos como destino de la navegación inferior para poder volver a las prendas mostradas allí | Comprobar si localizan Favoritos y vuelven al detalle, La persistencia después de cerrar la app queda fuera del prototipo |
| Eliminar una prenda por error no debería obligar a buscarla otra vez | El perfil de Alberto plantea dudas al tocar acciones que cambian la compra | Incluir la recuperación del producto eliminado entre las acciones que necesita el carrito | Pedir que recuperen una prenda eliminada y observar si identifican la acción sin ayuda |
| Pedir una cuenta puede añadir un paso que no necesita quien compra de forma puntual | Necesidad planteada para David y existencia de compra como invitado en Kiabi | Plantear el recorrido sin un paso de registro, El archivo definitivo no tiene pantalla de inicio de sesión | Comprobar si la persona entiende los pasos de compra sin buscar antes un botón de registro |
| Un error de formulario necesita explicar qué corregir | Objetivo de evitar bloqueos en Entrega y necesidad de Alberto de entender cómo seguir | Mostrar el email en estado de error con un mensaje de ayuda en el propio campo | Pedir que corrijan el error y medir tiempo, intentos y necesidad de ayuda |
| Antes de confirmar conviene poder relacionar la cantidad con el importe | Laura quiere comprar dos unidades y revisar el coste | Mantener los controles de cantidad y el resumen juntos en el carrito, Dos chaquetas de 39 € deben sumar 78 €, que es el importe esperado para esa tarea | Comprobar si identifican la cantidad y el total durante la tarea de compra |

Si en las pruebas alguien no encuentra la guía o no entiende una acción, usaré ese problema para decidir qué mejorar

## 3. Diseño de la interfaz
### 3.1 Mapa de navegación

He organizado la tienda para que se pueda empezar a mirar ropa desde Inicio, sin pasar antes por un registro, las tres opciones de la barra inferior son Inicio, Catálogo y Favoritos, cada una tiene una función distinta para no llenar una sola pantalla con todo

- Inicio presenta las categorías y la prenda de temporada, sirve como entrada a la tienda y permite decidir por dónde empezar
- Catálogo reúne las prendas con su nombre y precio, junto a los filtros de edad o talla, color y precio y la opción de ordenar
- Favoritos reúne las prendas guardadas para volver a ellas sin buscarlas otra vez en el catálogo

El siguiente mapa representa la estructura de navegación planteada para el diseño, las flechas explican las acciones que llevan de una pantalla a otra, no son un registro de pruebas de funcionamiento

```mermaid
flowchart TD
    INI["Inicio"]
    CAT["Catálogo"]
    DET["Detalle del producto"]
    CAR["Carrito"]
    ENT["Datos de entrega"]
    CON["Pedido confirmado"]
    FAV["Favoritos"]
    GUI["Panel de tallas"]

    INI -->|"Ver catálogo"| CAT
    CAT -->|"Consultar una prenda"| DET
    DET -->|"Añadir al carrito"| CAR
    CAR -->|"Continuar con la compra"| ENT
    ENT -->|"Confirmar pedido"| CON
    CON -->|"Volver a Inicio"| INI

    DET -->|"Consultar medidas"| GUI
    GUI -->|"Cerrar guía"| DET

    INI -->|"Abrir Favoritos"| FAV
    FAV -->|"Ver catálogo"| CAT
    FAV -->|"Consultar una prenda"| DET
    CAT -->|"Abrir Favoritos"| FAV
    CAT -->|"Volver a Inicio"| INI
    FAV -->|"Volver a Inicio"| INI
```

#### Recorrido de compra

La compra empieza al encontrar una prenda que interesa, desde el catálogo se consulta el detalle para ver la foto, el precio y las tallas, he separado estas dos pantallas porque en el catálogo interesa comparar varias prendas y en el detalle hace falta centrarse en una sola

La elección de talla pertenece al detalle, no tiene una pantalla aparte, así se puede consultar la guía y volver a la selección sin perder de vista qué producto se está comprando, la talla agotada debe distinguirse de las disponibles antes de añadir la prenda

El carrito queda entre la selección y los datos de entrega para poder revisar la compra antes de rellenar el formulario, ahí se reúnen la prenda, la talla, la cantidad y el importe, este paso permite detectar una cantidad equivocada antes de confirmar

Después aparecen los datos de contacto y dirección, el mensaje de error del email ayuda a entender qué hay que corregir, la confirmación cierra el recorrido con un número de pedido y el resumen de la compra, y ofrece volver a Inicio

#### Consulta de tallas

La guía es un panel que se abre sobre la ficha de la prenda, lo he planteado así porque consultar una medida es una ayuda dentro de la elección, al cerrarlo se recupera el detalle sin tener que recorrer de nuevo el catálogo

El panel no cuenta como otra etapa de compra, su función es resolver la duda antes de añadir la prenda, por eso aparece conectado al detalle y vuelve al mismo sitio

#### Vuelta a las pantallas principales

La barra inferior permite reconocer dónde se está entre Inicio, Catálogo y Favoritos, en la ficha y en los pasos de compra la flecha de la cabecera sirve para volver a la pantalla anterior

Las versiones oscuras de Inicio y Detalle mantienen la misma información y distribución, no añaden destinos al mapa porque representan esas mismas pantallas con otros colores

### 3.2 Wireframes

Los siete wireframes tienen un tamaño de 360 × 800 y muestran cómo se reparte el contenido de cada pantalla, he usado esta versión para centrarme en el orden de la información, el espacio de las imágenes y la posición de los botones

Las fotos están representadas con bloques y los botones llevan su texto para entender qué hace cada uno, predominan los grises, aunque en la confirmación queda un texto con un ligero tono azul

#### Inicio

He colocado el buscador arriba y las categorías justo debajo, Después aparece la prenda de temporada con el botón Ver catálogo, Así se puede empezar por una categoría o ir directamente a ver la ropa

Las categorías se ven antes de entrar al catálogo para orientar a quien ya sabe qué tipo de ropa busca, el buscador ofrece otra entrada para quien llega con una idea más concreta, son dos formas de empezar que responden a situaciones distintas

La prenda destacada tiene un espacio más grande porque presenta la temporada, pero no ocupa toda la pantalla, he dejado la navegación inferior separada para que se reconozca aunque cambie el contenido de la tienda

![Wireframe de Inicio con buscador, categorías y prenda destacada](capturas/wireframes/01-inicio.png)

#### Catálogo

Los filtros están encima de los productos, He usado dos columnas y he dejado el nombre y el precio debajo de cada foto para comparar las prendas sin entrar en todas las fichas

He separado los filtros de las tarjetas para que no compitan con el nombre y el precio de cada prenda, la opción de ordenar aparece en su propia línea porque cambia cómo se presentan los resultados, mientras que los filtros sirven para acotar lo que se busca

Cada tarjeta mantiene el mismo orden de información para comparar de arriba abajo sin tener que localizar el precio en un sitio diferente cada vez, el texto de agotado avisa de la disponibilidad sin depender solo del aspecto de la imagen

![Wireframe de Catálogo con filtros y cuatro productos en dos columnas](capturas/wireframes/02-catalogo.png)

#### Detalle del producto

La foto va arriba, seguida del nombre y el precio, Debajo están las tallas y la guía para consultarla antes de añadir la prenda, La talla agotada lleva el texto sin stock y el botón de compra queda en la parte baja

En esta pantalla he dado prioridad a lo que hace falta para decidir la compra, la foto permite reconocer el producto, el precio indica el coste y las tallas muestran las opciones de elección, la ayuda queda justo en el punto donde puede aparecer la duda

He dejado un espacio separado para la información de la prenda, así se puede explicar el producto sin mezclar esa descripción con los controles, el botón de compra mantiene su sitio en la parte baja para encontrarlo después de revisar la talla

![Wireframe de Detalle con selector de talla, guía y botón de compra](capturas/wireframes/03-detalle.png)

#### Carrito

Junto a la prenda están la cantidad y la opción de eliminarla, Debajo aparecen el subtotal y el total antes de continuar, Esta captura muestra una chaqueta de talla 4, una unidad y un total de 39 €

La imagen y el nombre ayudan a reconocer que se ha añadido la prenda correcta, la talla aparece en el mismo bloque para revisar la selección sin volver al detalle, los controles de cantidad quedan cerca porque afectan a ese producto concreto

La eliminación tiene una etiqueta visible para distinguirla del cambio de cantidad, el resumen de importes está separado de la ficha del producto y colocado antes de continuar, así se puede revisar qué se compra y cuánto cuesta en el mismo paso

![Wireframe de Carrito con cantidad, eliminación y resumen de una unidad](capturas/wireframes/04-carrito.png)

#### Datos de entrega

He puesto los campos en una columna, primero los datos de contacto y después la dirección, El email tiene un ejemplo de ayuda, En el prototipo final se verá el campo con el estado de error

He separado nombre y email de los datos de dirección para seguir un orden fácil de entender, cada campo ocupa su propia fila para que no haya que repartir la atención entre dos entradas pequeñas, el mensaje del email indica el formato que se espera

El importe aparece antes del botón de confirmación para mantener la referencia del coste mientras se rellenan los datos, esta pantalla está centrada en contacto y entrega, no incluye una entrada de tarjeta ni una pasarela de pago real

![Wireframe de Datos de entrega con cinco campos y ayuda para el email](capturas/wireframes/05-entrega.png)

#### Pedido confirmado

La pantalla muestra Pedido realizado, el número 12-PD y el resumen de la chaqueta, He dejado el botón Volver a Inicio abajo para seguir mirando la tienda, El pedido es de demostración

Después del formulario hace falta una respuesta clara que permita reconocer que el recorrido ha terminado, por eso el mensaje de confirmación aparece junto al identificador y no queda solo una imagen sin explicación

El resumen incluye la prenda, la talla, las unidades y el total para poder contrastarlo con el carrito, la vuelta a Inicio es la acción principal de salida, no he añadido opciones de seguimiento que no forman parte de este diseño

![Wireframe de Pedido confirmado con identificador y vuelta a Inicio](capturas/wireframes/06-confirmacion.png)

#### Favoritos

He mantenido las dos columnas del catálogo para que las tarjetas se vean igual, Una prenda aparece como agotada y la barra inferior marca Favoritos como pantalla activa

Repetir la estructura de las tarjetas evita tener que aprender otra forma de consultar las prendas, aquí la diferencia es el motivo por el que aparecen, se reúnen como una selección que interesa revisar, en lugar de representar todo el catálogo

Mostrar el precio y el estado de disponibilidad permite valorar esa selección antes de abrir el detalle, la pantalla sirve como referencia para volver a una prenda, mientras que el carrito se reserva para revisar lo que se quiere comprar

![Wireframe de Favoritos con prendas guardadas y un producto agotado](capturas/wireframes/07-favoritos.png)


### 3.3 Guía de estilo Material Design 3
### 3.4 Prototipo de alta fidelidad

## 4. Validación y pruebas
### 4.1 Metodología                          
### 4.2 Resultados                           
### 4.3 Iteraciones y mejoras               
## 5. Entrega y documentación final
### 5.1 Justificación del diseño propuesto
### 5.2 Recomendaciones y pasos a seguir

## 6. Referencias bibliográficas

- Kiabi (sin fecha) - *Hacer un pedido en Kiabi.es* - https://www.kiabi.es/servicios/pedido.html
- Mayoral (sin fecha) - *Camiseta volante niña* - https://www.mayoral.com/es/es/camiseta-volante-nina-anis-2603008074-5
- Vertbaudet (sin fecha) - *Guía de calzado* - https://www.vertbaudet.es/page/asesoramiento/guias/calzado.htm
- Zara (sin fecha) - *Ayuda* - https://www.zara.com/es/es/help/compra-segura-h28.html

Palabra del día - 29
