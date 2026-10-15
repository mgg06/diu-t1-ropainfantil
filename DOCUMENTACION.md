# Documentación de la interfaz · Pequeño Davante

## 1. Justificación del diseño

### 1.1 Importancia del diseño centrado en el usuario

Al pensar en la app de Pequeño Davante, he partido de una situación bastante normal. Una persona necesita comprar ropa infantil y mira el móvil en un rato libre. Puede estar haciendo otra cosa y tener solo una mano disponible. Por eso me interesa que encuentre las prendas sin tener que recorrer muchos menús.

La talla es una de las dudas que he tenido más en cuenta. Saber la edad del niño no siempre basta para elegir una prenda. En el detalle he dejado la guía de tallas junto a la selección de talla, para poder consultarla sin salir de la ficha. Las opciones sin stock tienen un estado distinto para que se vea que no están disponibles.

He colocado el botón de añadir al carrito en la parte baja del detalle. En el carrito se puede cambiar la cantidad y deshacer una eliminación. Así, si alguien toca donde no quería, tiene una forma de recuperar la prenda. El formulario de entrega muestra un error de email con un mensaje de ayuda. Son decisiones pensadas para que la persona sepa qué puede hacer y cómo corregirse.

### 1.2 Objetivos y metas del proyecto

He planteado estos objetivos para comprobar el diseño. Todavía son metas, no resultados de las pruebas.

1. Conseguir que cada participante complete el recorrido de compra de la chaqueta en verde oliva, talla 4 y cantidad 2, en menos de dos minutos y sin ayuda. Mediré el tiempo desde Inicio hasta Confirmación. Es una compra simulada dentro de Figma.

2. Conseguir que cada participante encuentre y abra la guía de tallas desde el detalle en menos de diez segundos y sin indicaciones. Anotaré si la encuentra al primer intento y si pulsa antes en otro sitio.

3. Conseguir que cada participante corrija el error de email y avance desde Entrega sin ayuda. Registraré cuánto tarda y los intentos fallidos, para comprobar si el mensaje explica bien el problema.

4. Comprobar que todas las parejas de color y su texto que documente en la guía de estilo tengan un contraste mínimo de 4,5 a 1 en los esquemas claro y oscuro. Guardaré los valores y sus ratios en la sección 3.3. Esta comprobación no sustituye las pruebas de lectura con personas.

Las pruebas se harán con al menos dos compañeros de otro grupo. Con una muestra tan pequeña, recogeré lo que le pase a cada persona sin presentar esos resultados como si representaran a todos los compradores.

### 1.3 Beneficios esperados

Para quien compra, espero que la guía de tallas ayude a decidir con más información. Tener el precio y la selección de talla en la misma ficha evita tener que recordar datos de otras pantallas. Poder revisar la cantidad y recuperar una prenda eliminada permite corregir la compra antes de confirmarla.

Para Pequeño Davante, una ficha clara podría reducir las consultas sobre tallas y evitar algunas compras equivocadas. Un formulario que explique los errores podría ayudar a que menos personas abandonen el proceso por no saber cómo seguir. Son beneficios esperados. El prototipo no permite demostrar una reducción de devoluciones ni un aumento de ventas.

## 2. Investigación y análisis de usuarios

### 2.1 Datos demográficos y segmentación

Pequeño Davante está pensada para personas adultas que compran ropa y calzado para niños de 0 a 14 años desde un móvil Android. Quien usa la app y decide la compra no tiene por qué ser quien va a llevar la prenda. Esto importa sobre todo al hacer un regalo, porque se puede conocer la edad del niño sin saber su talla.

He separado tres situaciones de compra. Las edades son orientativas y me sirven para construir los perfiles del proyecto. No proceden de una encuesta ni describen a todos los clientes de una tienda real.

| Grupo | Situación de compra | Qué necesita resolver | Qué debo tener en cuenta en el diseño |
| --- | --- | --- | --- |
| Padres y madres, aproximadamente de 30 a 45 años | Reponen ropa que se ha quedado pequeña o buscan prendas para otra temporada. Pueden consultar el catálogo en ratos cortos. | Localizar una prenda, comprobar la talla y revisar el importe antes de terminar. | Categorías visibles, precio junto a la prenda y un carrito donde se pueda cambiar la cantidad. |
| Familiares y amigos, aproximadamente de 20 a 30 años | Compran un regalo de forma puntual y pueden tener poca información sobre las medidas del niño. | Entender las tallas y completar la compra sin tener que crear una cuenta. | Guía de tallas accesible desde el detalle y acceso opcional a la cuenta. |
| Abuelos y otros familiares, aproximadamente de 60 a 75 años | Buscan una prenda para un nieto y pueden preferir revisar cada paso antes de confirmar. | Leer los datos con comodidad, reconocer las acciones y corregir una equivocación. | Texto con contraste, botones con etiqueta, áreas táctiles amplias y opción de deshacer al eliminar. |

No doy por hecho que una persona joven maneje bien cualquier app ni que alguien mayor necesite ayuda. Lo que cambia entre estos grupos es la situación que he elegido estudiar. Las dificultades de lectura, los toques imprecisos o las dudas con las tallas pueden aparecer a cualquier edad.

La falta de tiempo y el uso con una mano vienen del contexto del enunciado. El resto son supuestos de diseño que habrá que revisar con las pruebas. Las sesiones con compañeros servirán para detectar problemas del recorrido, pero no equivalen a investigar una muestra de padres, madres y abuelos.

### 2.2 Personas

Para saber cómo tengo que diseñar las pantallas de la app, he pensado en tres tipos de personas que van a usar la tienda. Para cada una me he inventado una situación y unos problemas diferentes:

Por un lado está Laura, que tiene 36 años y dos hijos. Es la que compra casi siempre porque a los niños se les queda pequeña la ropa volando. Como suele mirar el catálogo de noche con el móvil y va con el tiempo justa, lo que más le importa es encontrar las cosas rápidamente. Necesita poder filtrar por talla al momento y ver si hay stock directamente en las fotos, porque entrar producto por producto le quita un montón de tiempo

Luego está el caso de David, con 25 años, que entra a la app solo cuando le toca hacer un regalo de cumpleaños a algún sobrino. Controla el móvil perfectamente, pero de ropa infantil no tiene ni idea y se pierde con las tallas. Lo que peor lleva es que le pida rellenar mil datos solo para hacer una compra rápida, así que la app tiene que dejarle pagar con los mínimos pasos posibles si no quiere que se vaya de la tienda

Y por último está Alberto, que tiene 68 años y busca un detalle para su nieta. Usa el móvil con la letra más grande porque ya le cuesta fijarse de cerca. Para él lo importante es que los precios y los textos se lean bien a la primera, que los botones sean cómodos de pulsar para no equivocarse y que el proceso de pago le dé total seguridad, sin pantallas raras que le hagan dudar

### 2.3 Análisis de la competencia

Para no ir a ciegas, he estado analizando a fondo cómo funcionan cuatro aplicaciones y tiendas online de ropa infantil que dominan el mercado actual. En la siguiente tabla detallo qué hace bien cada una, en qué fallan, cómo manejan el acceso y qué conclusiones me llevo para aplicarlas directamente en el diseño de Pequeño Davante:

| Tienda | Qué hacen bien | Qué hacen mal | Sistema de registro y acceso | Qué me llevo para Pequeño Davante |
| :--- | :--- | :--- | :--- | :--- |
| **Mayoral** | Tienen una guía de tallas súper trabajada y detallada con medidas exactas para que el usuario no se equivoque nunca al elegir online | La interfaz general se ve bastante pesada, genérica y poco optimizada cuando entras a navegar desde el móvil | Te pide cuenta clásica de usuario para guardar datos, aunque deja ver algo del catálogo antes | Coger la idea de explicar las tallas al detalle, pero dándole un lavado de cara para que la pantalla de la app sea moderna, limpia y fluida |
| **Vertbaudet** | Organizan muy bien la ropa por categorías y las fotos del catálogo se ven grandes, llamativas y claras a primera vista | Al entrar en los detalles de una prenda o en las opiniones, saturan la pantalla con demasiado texto pequeño que agobia bastante | Permite inicio de sesión rápido, pero a veces satura con ventanas emergentes para crear un perfil nuevo | Mantener esa misma limpieza visual en el catálogo, asegurándome de no recargar las fichas con información innecesaria que moleste |
| **Kiabi** | Los filtros de búsqueda rápida por precio, talla y color funcionan de maravilla y ahorran muchísimo tiempo al usuario | El proceso de pago es un embudo, te exigen un registro obligatorio antes de dejarte avanzar, lo que corta totalmente el ritmo que tengas de la compra | Bloquea el pago si no te registras previamente con email y contraseña obligatorios | Aprovechar su agilidad en los filtros y menús, pero garantizando un proceso de compra directo y sin bloqueos de registro forzados para que nadie se pire |
| **Zara Kids** | Destacan por un diseño visual muy chulo, minimalista y tienen fotografías de estudio enormes que te entran por los ojos enseguida | Los menús principales están demasiado escondidos en iconos minimalistas y cuesta encontrar las categorías básicas sin dar mil vueltas | Cuenta unificada con la app general de la marca, permitiendo acceso rápido si ya la usas | Aplicar esa estética visual tan cuidada y directa en las fotos, pero asegurando que la navegación y los botones sean evidentes y fáciles de encontrar |

### 2.4 Insights y hallazgos clave           

## 3. Diseño de la interfaz
### 3.1 Mapa de navegación                   
### 3.2 Wireframes
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
Palabra del día: 29