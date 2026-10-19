# Pequeño Davante

**Marta González González - 2º DAM - Desarrollo de Interfaces**

Pequeño Davante es la tienda de ropa infantil que he imaginado para Davante, de ahí vienen el nombre, el logo y el azul de las pantallas. Reúne ropa y calzado de 0 a 14 años, con la información pensada para las personas adultas que compran, desde elegir una talla hasta revisar el importe del pedido

La tienda es ficticia y el prototipo está hecho en Figma para representar su uso desde un móvil Android, en el repo están la explicación del diseño, los wireframes, las pantallas finales y los valores de estilo

[Ver el diseño en Figma](https://www.figma.com/design/uM6HT2RdelpEDSTGd4Fnk2/T1-%C2%B7-Peque%C3%B1o-Davante-%C2%B7-Marta-Gonz%C3%A1lez-Gonz%C3%A1lez?node-id=19-218&t=I4eUANyW0SXHQ82B-1) | [Probar el recorrido](https://www.figma.com/proto/uM6HT2RdelpEDSTGd4Fnk2/T1-Pequeno-Davante?node-id=46-723&page-id=19-218&scaling=scale-down&content-scaling=fixed) | [Leer DOCUMENTACION.md](DOCUMENTACION.md)

<p align="center">
  <img src="capturas/prototipo/01-inicio.png" alt="Inicio de Pequeño Davante con las categorías y la chaqueta de temporada" width="300">
</p>

## Una tienda de Davante para los pequeños

La marca aparece desde la entrada, acompañada de las fotografías de ropa infantil. El azul identifica los controles y la navegación, mientras que las prendas aportan sus propios colores. El nombre Pequeño Davante recoge esa adaptación de la marca a una tienda para niños

La compra de un regalo ha tenido bastante peso en el diseño, porque conocer la edad no siempre basta para elegir la talla. La guía de medidas queda junto a la selección de talla y Favoritos permite guardar una prenda antes de decidir si se compra

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

La presentación empieza en "Inicio de sesión", con las opciones de correo, Google y cuenta Davante, también se puede seguir sin cuenta, el login incluye los campos de acceso, la aceptación de términos, recuperar cuenta y crear cuenta, estos dos últimos accesos están representados en la pantalla y no abren otros formularios, los botones de Google y Davante llevan a "Inicio" dentro del recorrido

La compra preparada en el prototipo utiliza la chaqueta verde oliva de talla 4. Desde Inicio se llega al Catálogo y al Detalle, donde se elige la talla antes de añadirla al Carrito. Una unidad cuesta 39 € y dos suman 78 €, después se completan los Datos de entrega y se llega a Pedido confirmado. Las capturas muestran una unidad y el pedido de ejemplo 12-PD

La guía de medidas se abre sobre el Detalle y permite regresar a la misma chaqueta. El formulario incluye un email incompleto y el cambio al estado corregido para recorrer ese caso de error, sin validar cualquier dirección escrita. Las demás prendas completan el Catálogo y Favoritos, aunque la compra desarrollada corresponde a la chaqueta

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

La tarjeta de producto y el selector de talla están en Wireframes, fuera de las pantallas exportadas. Las tarjetas del Catálogo y Favoritos utilizan esos componentes locales con la foto y los datos de cada prenda. Sus variantes recogen los estados de favorito, agotado y selección de talla en los dos modos de color

La [comparación de antes y después](DOCUMENTACION.md#43-iteraciones-y-mejoras) muestra un cambio concreto en el "Detalle", he sustituido Guía de tallas por Consultar medidas y tallas para explicar mejor qué ayuda se abre, el botón conserva su tamaño y su lugar junto a las tallas, la [sección de resultados](DOCUMENTACION.md#42-resultados) recoge los recorridos que he planteado para revisar esa dificultad

## Medidas y estilos

| Elemento | Valor utilizado |
| --- | --- |
| Pantallas | 360 x 800 |
| Base de la interfaz | Material Design 3 |
| Texto | Roboto, cinco estilos principales |
| Rejilla | Cuatro columnas, margen lateral de 16 y separación de 8 |
| Espaciado | Base de 8 |
| Referencia de pulsación | 48 x 48 |
| Contraste de las parejas documentadas | Todas superan 4,5 a 1 |

Los valores están en [diseno/estilos.json](diseno/estilos.json), he recogido en un mismo esquema los roles claros y oscuros de Material 3 con la paleta azul de las pantallas, además están los tamaños de letra, el espacio entre líneas y las medidas de distribución para relacionarlos con la explicación del diseño

## Referencias

Las quince fuentes están al final de [DOCUMENTACION.md](DOCUMENTACION.md#6-referencias-bibliográficas), dentro de la sección de referencias bibliográficas en formato APA7
