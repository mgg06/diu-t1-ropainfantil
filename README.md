# Pequeño Davante

**Marta González González - 2º DAM - Desarrollo de Interfaces**

Pequeño Davante parte de imaginar que Davante abre una tienda de ropa y calzado infantil, he llevado esa idea a una propuesta de app Android para comprar prendas de 0 a 14 años, manteniendo la relación del nombre, el logo y los colores con Davante, aunque la ropa sea para niños, la interfaz está dirigida a las personas adultas que la eligen, por eso he dado importancia a las tallas, al precio y a revisar la compra antes de confirmar

En este repo reúno la documentación, los wireframes y las capturas del prototipo de Figma, la propuesta representa una tienda ficticia y un recorrido de compra de demostración

[Abrir el archivo de Figma](https://www.figma.com/design/uM6HT2RdelpEDSTGd4Fnk2/T1-Pequeno-Davante?node-id=19-218) | [Abrir la presentación del prototipo](https://www.figma.com/proto/uM6HT2RdelpEDSTGd4Fnk2/T1-Pequeno-Davante?node-id=19-939&page-id=19-218&scaling=scale-down&content-scaling=fixed) | [Leer la documentación](DOCUMENTACION.md)

<p align="center">
  <img src="capturas/prototipo/01-inicio.png" alt="Inicio de Pequeño Davante con las categorías y la chaqueta de temporada" width="300">
</p>

## La idea de la tienda

He utilizado la palabra Pequeño para relacionar Davante con la ropa infantil, y he mantenido el azul como referencia de la marca, la variedad de colores la aportan las propias prendas, así la tienda conserva una imagen común sin que cada pantalla parezca de una app diferente, la chaqueta de temporada sirve como ejemplo principal para explicar la elección de color y talla, el paso al carrito y la revisión de unidades

La compra de un regalo ha sido una de las situaciones que más he tenido en cuenta, una persona puede saber los años que tiene un niño y no conocer sus medidas, por eso la guía está relacionada con la ficha del producto, también he separado las prendas que gustan de las que ya se han añadido al carrito, guardar una chaqueta para mirarla otro día no significa que se haya decidido comprarla

## Índice de la documentación

| Apartado | Qué se explica |
| --- | --- |
| [1 - Justificación del diseño](DOCUMENTACION.md#1-justificación-del-diseño) | La idea de Pequeño Davante, las necesidades de compra, los objetivos medibles y los beneficios esperados |
| [2 - Investigación y análisis de usuarios](DOCUMENTACION.md#2-investigación-y-análisis-de-usuarios) | Los grupos de usuarios, tres perfiles ficticios, la competencia y las decisiones que he sacado de la comparación |
| [3 - Diseño de la interfaz](DOCUMENTACION.md#3-diseño-de-la-interfaz) | La organización del recorrido, los wireframes, la guía de estilo y las pantallas finales |
| [4 - Validación y pruebas](DOCUMENTACION.md#4-validación-y-pruebas) | Las tareas y las medidas con las que se valora el uso del prototipo |
| [5 - Entrega y documentación final](DOCUMENTACION.md#5-entrega-y-documentación-final) | La justificación de la propuesta y las recomendaciones para llevarla a una app real |
| [6 - Referencias bibliográficas](DOCUMENTACION.md#6-referencias-bibliográficas) | Las fuentes consultadas para apoyar las explicaciones y las referencias del diseño |

Dentro del diseño se puede ir directamente al [mapa de navegación](DOCUMENTACION.md#31-mapa-de-navegación), los [wireframes](DOCUMENTACION.md#32-wireframes), la [guía de estilo](DOCUMENTACION.md#33-guía-de-estilo-material-design-3) o el [prototipo de alta fidelidad](DOCUMENTACION.md#34-prototipo-de-alta-fidelidad)

## Recorrido de compra

El recorrido planteado empieza en Inicio, continúa por Catálogo y Detalle del producto, y después pasa a Carrito, Datos de entrega y Pedido confirmado, he separado esos pasos porque primero se compara la ropa, después se concreta la talla y el color, y al final se revisa la selección antes de introducir la dirección, Inicio, Catálogo y Favoritos son los tres destinos de la barra inferior

La guía de tallas se abre sobre el detalle para consultar las medidas y volver a la misma prenda, el ejemplo de email incorrecto permite representar cómo se explica una corrección dentro del formulario, en las capturas del carrito y de la confirmación aparece una chaqueta verde oliva de talla 4, una unidad y 39 €, las tareas de evaluación incluyen revisar dos unidades, cuyo importe esperado es de 78 €

## Pantallas del prototipo

| Pantalla | Para qué sirve | Captura |
| --- | --- | --- |
| Inicio | Presentar la tienda y empezar por categorías, novedades o catálogo | [Ver Inicio](capturas/prototipo/01-inicio.png) |
| Catálogo | Comparar prendas y presentar las opciones de filtro y ordenación | [Ver Catálogo](capturas/prototipo/02-catalogo.png) |
| Detalle del producto | Consultar la chaqueta, el color, la talla y la ayuda de medidas | [Ver Detalle](capturas/prototipo/03-detalle.png) |
| Carrito | Revisar la prenda, las unidades y el importe antes de continuar | [Ver Carrito](capturas/prototipo/04-carrito.png) |
| Datos de entrega | Completar el contacto y la dirección, con un ejemplo de error en el email | [Ver Entrega](capturas/prototipo/05-entrega.png) |
| Pedido confirmado | Reconocer el resultado de demostración y volver a Inicio | [Ver Confirmación](capturas/prototipo/06-confirmacion.png) |
| Favoritos | Volver a las prendas que interesan sin confundirlas con una compra decidida | [Ver Favoritos](capturas/prototipo/07-favoritos.png) |

Además de las siete pantallas principales, están las versiones de [Inicio en oscuro](capturas/prototipo/08-inicio-oscuro.png) y [Detalle en oscuro](capturas/prototipo/09-detalle-oscuro.png), junto con la [guía de tallas](capturas/prototipo/10-guia-tallas.png), los [siete wireframes](capturas/wireframes/) permiten comparar la organización inicial con el acabado final

## Base del diseño

| Elemento | Referencia utilizada |
| --- | --- |
| Plataforma | Propuesta de interfaz para Android |
| Formato de las pantallas principales | 360 × 800 |
| Base de los elementos de interfaz | Material Design 3 |
| Tipografía | Roboto, con cinco estilos principales |
| Rejilla | Cuatro columnas y márgenes laterales de 16 |
| Espaciado | Base de 8 |
| Zona de pulsación de referencia | 48 × 48 |
| Contraste de referencia | Mínimo de 4,5 a 1 en las parejas documentadas |

En la guía de estilo he separado los colores azules de las pantallas de los valores del tema material-theme incluido en Figma, así cada tabla de contraste se puede relacionar con la paleta que le corresponde, la explicación de los componentes recoge las tarjetas de producto y los selectores de talla y color con sus distintos estados

## Cómo consultar el proyecto

- El archivo de Figma contiene las páginas Wireframes y Prototipo, la presentación enlazada apunta a Inicio
- DOCUMENTACION.md desarrolla las decisiones y relaciona cada pantalla con sus capturas
- La carpeta capturas reúne las imágenes de baja y alta fidelidad para poder consultarlas desde el repo
- [diseno/estilos.json](diseno/estilos.json) reúne los valores de color, tipografía y espaciado, con el tema de Figma separado de la paleta azul de las pantallas
- Los precios, las selecciones y el pedido 12-PD pertenecen a la demostración, no se realiza ningún cobro ni envío

Las referencias consultadas se reúnen al final de [DOCUMENTACION.md](DOCUMENTACION.md#6-referencias-bibliográficas)

Palabra del día - 29
