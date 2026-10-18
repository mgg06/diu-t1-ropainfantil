# Pequeño Davante

**Marta González González - 2º DAM - Desarrollo de Interfaces**

Pequeño Davante es la tienda de ropa infantil que he imaginado para Davante, de ahí vienen el nombre, el logo y el azul de las pantallas, la propuesta reúne ropa y calzado para niños de 0 a 14 años, pero quienes utilizan la app son las personas adultas que compran para ellos, he partido de esa diferencia para decidir qué información hacía falta, reconocer una prenda, saber qué talla queda y comprobar cuánto cuesta antes de seguir con la compra

La tienda es ficticia y el prototipo está hecho en Figma para representar su uso desde un móvil Android, en el repo están la explicación del diseño, los wireframes, las pantallas finales y los valores de estilo, no hay una app instalada ni se hacen pedidos reales

[Ver el diseño en Figma](https://www.figma.com/design/uM6HT2RdelpEDSTGd4Fnk2/T1-%C2%B7-Peque%C3%B1o-Davante-%C2%B7-Marta-Gonz%C3%A1lez-Gonz%C3%A1lez?node-id=19-218&t=I4eUANyW0SXHQ82B-1) | [Probar el recorrido](https://www.figma.com/proto/uM6HT2RdelpEDSTGd4Fnk2/T1-Pequeno-Davante?node-id=46-723&page-id=19-218&scaling=scale-down&content-scaling=fixed) | [Leer DOCUMENTACION.md](DOCUMENTACION.md)

<p align="center">
  <img src="capturas/prototipo/01-inicio.png" alt="Inicio de Pequeño Davante con las categorías y la chaqueta de temporada" width="300">
</p>

## Una tienda de Davante para los pequeños

Me interesaba que la relación con Davante se entendiera al abrir la app, por eso he conservado la marca y he utilizado Pequeño para explicar a qué tipo de ropa va dirigida, el azul se repite en las acciones y en la navegación, mientras que las fotografías dan variedad al catálogo, la ropa tiene sus propios colores y los controles mantienen una referencia común, así se puede pasar de mirar una chaqueta a revisar el pedido sin perder la relación entre las pantallas

He tenido bastante en cuenta a quien compra un regalo, puede conocer la edad del niño y no saber qué talla utiliza, por eso la consulta de medidas está junto a la elección de talla, guardar una prenda para mirarla otro día tiene su espacio en "Favoritos", y revisar lo que ya se ha decidido comprar corresponde al "Carrito", esta diferencia me ha servido para organizar las partes de la tienda según lo que se necesita en cada momento

## Qué hay en la documentación

| Apartado | Contenido |
| --- | --- |
| [1 - Justificación del diseño](DOCUMENTACION.md#1-justificación-del-diseño) | Idea de la tienda, necesidades de compra, cuatro objetivos medibles y beneficios esperados |
| [2 - Investigación y análisis de usuarios](DOCUMENTACION.md#2-investigación-y-análisis-de-usuarios) | Grupos de usuarios, tres personas ficticias, comparativa de tiendas y apps, seis hallazgos relacionados con el diseño |
| [3 - Diseño de la interfaz](DOCUMENTACION.md#3-diseño-de-la-interfaz) | Navegación, ocho wireframes, colores, tipografía, componentes y explicación de las pantallas finales |
| [4 - Validación y pruebas](DOCUMENTACION.md#4-validación-y-pruebas) | Tres tareas, medidas de evaluación, revisión de las conexiones y mejora con capturas de antes y después |
| [5 - Entrega y documentación final](DOCUMENTACION.md#5-entrega-y-documentación-final) | Motivos de las decisiones principales y cambios necesarios para llevar la propuesta a una app real |
| [6 - Referencias bibliográficas](DOCUMENTACION.md#6-referencias-bibliográficas) | Bibliografía en APA7 gestionada con Zotero |

Los accesos al [mapa de navegación](DOCUMENTACION.md#31-mapa-de-navegación), los [wireframes](DOCUMENTACION.md#32-wireframes), la [guía de estilo](DOCUMENTACION.md#33-guía-de-estilo-material-design-3) y el [prototipo final](DOCUMENTACION.md#34-prototipo-de-alta-fidelidad) llevan a cada parte del diseño dentro del documento

## Cómo se recorre la tienda

La presentación empieza en "Inicio de sesión", con las opciones de correo, Google y cuenta Davante, también se puede seguir sin cuenta, el login incluye los campos de acceso, la aceptación de términos, recuperar cuenta y crear cuenta, estos dos últimos accesos están representados en la pantalla y no abren otros formularios, los botones de Google y Davante llevan a "Inicio" como demostración, sin conectar con esos servicios

Desde "Inicio" se pasa al "Catálogo" para mirar las prendas y abrir el "Detalle del producto", he preparado el ejemplo de compra con la chaqueta verde oliva y la talla de 4 años, al elegirla se puede añadir al "Carrito" y revisar la cantidad, una unidad cuesta 39 € y dos suman 78 €, después aparecen los "Datos de entrega" y "Pedido confirmado", en las capturas se muestra el estado inicial de una unidad, el número 12-PD identifica ese pedido de demostración

La consulta de medidas se abre sobre el "Detalle" para volver después a la misma chaqueta, el formulario muestra un email incompleto y tiene preparado el cambio al estado corregido, esta interacción sirve para explicar el error y cómo continuar, no comprueba cualquier dirección que se escriba, el recorrido está centrado en esa compra concreta, las demás prendas completan la propuesta de catálogo y favoritos sin tener todas su compra desarrollada

## Las pantallas

| Pantalla | Qué se resuelve en ella | Captura |
| --- | --- | --- |
| "Inicio de sesión" | Acceder a la tienda o seguir sin cuenta | [Ver el login](capturas/prototipo/11-inicio-sesion.png) |
| "Inicio" | Reconocer la tienda y empezar a mirar ropa | [Ver "Inicio"](capturas/prototipo/01-inicio.png) |
| "Catálogo" | Comparar prendas, precios y disponibilidad | [Ver "Catálogo"](capturas/prototipo/02-catalogo.png) |
| "Detalle del producto" | Consultar la chaqueta y elegir su talla | [Ver "Detalle"](capturas/prototipo/03-detalle.png) |
| "Carrito" | Revisar las unidades y el importe | [Ver "Carrito"](capturas/prototipo/04-carrito.png) |
| "Datos de entrega" | Representar los datos de contacto y dirección, con el error del email | [Ver "Datos de entrega"](capturas/prototipo/05-entrega.png) |
| "Pedido confirmado" | Comprobar el resumen de la compra y volver a "Inicio" | [Ver "Pedido confirmado"](capturas/prototipo/06-confirmacion.png) |
| "Favoritos" | Volver a las prendas guardadas antes de decidir qué comprar | [Ver "Favoritos"](capturas/prototipo/07-favoritos.png) |

"Inicio", "Catálogo" y "Favoritos" forman la barra inferior, son los tres lugares a los que se puede volver mientras se elige la ropa, además de estas ocho pantallas están ["Inicio" en oscuro](capturas/prototipo/08-inicio-oscuro.png), ["Detalle" en oscuro](capturas/prototipo/09-detalle-oscuro.png) y la ["Guía de tallas"](capturas/prototipo/10-guia-tallas.png), he mantenido la distribución en las dos versiones oscuras para que cambiar de colores no cambie la posición de las opciones

## Del wireframe al acabado final

Los [ocho wireframes](capturas/wireframes/) recogen la distribución antes del acabado con fotos y colores, incluido el [wireframe del login](capturas/wireframes/08-inicio-sesion.png), se pueden comparar con las capturas finales de cada pantalla para ver qué lugar ocupa la navegación, dónde se elige una talla o en qué momento se revisa la compra, en el archivo de Figma están separados en las páginas Wireframes y Prototipo

He reunido la tarjeta de producto y el selector de talla en la página Componentes, once tarjetas y ocho selectores utilizan esos dos conjuntos locales, cada tarjeta conserva la foto y los datos de su prenda, y cada talla mantiene su edad y su disponibilidad, los estados permiten distinguir una prenda favorita de una agotada y una talla disponible de la que ya se ha elegido, las versiones claras y oscuras comparten esa misma idea

La [comparación de antes y después](DOCUMENTACION.md#43-iteraciones-y-mejoras) muestra un cambio concreto en el "Detalle", he sustituido Guía de tallas por Consultar medidas y tallas para explicar mejor qué ayuda se abre, el botón conserva su tamaño y su lugar junto a las tallas, esta mejora procede de revisar el diseño, la [sección de resultados](DOCUMENTACION.md#42-resultados) separa esa revisión de las mediciones de uso con participantes

## Medidas y estilos

| Elemento | Valor utilizado |
| --- | --- |
| Pantallas | 360 × 800 |
| Base de la interfaz | Material Design 3 |
| Texto | Roboto, cinco estilos principales |
| Rejilla | Cuatro columnas, margen lateral de 16 y separación de 8 |
| Espaciado | Base de 8 |
| Referencia de pulsación | 48 × 48 |
| Contraste de las parejas documentadas | Todas superan 4,5 a 1 |

Los valores están en [diseno/estilos.json](diseno/estilos.json), he recogido por separado los roles claros y oscuros de material-theme y la paleta azul que se ve en las pantallas, tienen colores distintos y cada tabla de contraste corresponde a sus propias parejas de fondo y texto, también están los tamaños de letra, el espacio entre líneas y las medidas de distribución para relacionarlos con la explicación del diseño

## Referencias

Las quince fuentes están al final de [DOCUMENTACION.md](DOCUMENTACION.md#6-referencias-bibliográficas), la carpeta [referencias](referencias/) conserva la bibliografía APA7 y los datos de las entradas utilizadas

Palabra del día - 29
