# CinePlusShari3E
Aplicación básica de cobro para un cine creada en python con wxglade. Consta de 4 ventanas; inicio de sesión, taquilla, dulceria, y ventana de cobro

1. Ventana de Inicio de Sesión.

Esta es la primera pantalla que aparece cuando el usuario accede al sistema CinePlus. Su propósito es validar que la persona que ingresa tenga un usuario y contraseña correctos antes de permitirle avanzar.

En la parte superior se muestra el título “Bienvenido a CinePlus” con un diseño centrado y de gran tamaño para dar una bienvenida clara y atractiva. Justo debajo aparece una imagen relacionada con el cine, que incluye un carrete de película, palomitas y una claqueta; esta imagen funciona como elemento visual que introduce al usuario al ambiente cinematográfico del sistema.

Debajo del área gráfica se encuentran los campos de ingreso:
	•	Usuario: un cuadro de texto donde el cliente o empleado escribe su nombre de usuario.
	•	Contraseña: un cuadro de texto que oculta los caracteres para proteger la información del usuario.

Finalmente, en la parte inferior hay dos botones:
	•	Entrar, de color verde, para acceder al sistema si los datos son correctos.
	•	Salir, de color rojo, que permite cerrar por completo la aplicación.

Esta ventana funciona como punto de inicio y controla el acceso al resto de las funciones del sistema.


2. Ventana de Taquilla.

Esta ventana representa el módulo donde se realiza la compra de boletos para la película elegida. Su objetivo es permitir al usuario seleccionar la función, horario y cantidad de boletos.

En la parte superior aparece el título “TAQUILLA” acompañado de dos pequeñas imágenes de boletos que decoran el espacio y refuerzan el propósito de la ventana.

A continuación, se muestra un conjunto de controles:

Selección de película

Un menú desplegable que permite elegir la película disponible. A un lado puede aparecer el póster de la película seleccionada, para mejorar la experiencia visual del usuario.

Sala

Muestra el número o nombre de la sala en la que se proyectará la película.

Horarios

Se presentan opciones de horarios representadas por botones de opción (radio buttons), para elegir la hora de la función.

Boletos

En esta sección se capturan las cantidades de boletos:
	•	Adultos ($80)
	•	Menores ($70)

El sistema calculará un subtotal según los boletos ingresados.

En la parte inferior aparecen los botones:
	•	Limpiar: reinicia la información de la taquilla.
	•	Siguiente: avanza a la ventana de dulcería para continuar la compra.

Esta ventana realiza todo lo necesario sobre boletos y horarios.

3. Ventana de Dulcería.

Esta pantalla corresponde al módulo donde el usuario puede comprar productos de la dulcería del cine. Todo está organizado en secciones que facilitan la selección.

En la parte superior aparece el título “DULCERIA”, decorado con imágenes de dulces en ambos extremos para reforzar la temática.

La ventana está dividida en varios apartados principales:

Paquetes

Incluye distintos combos como:
	•	Básico $75: palomitas chicas y refresco chico.
	•	Cuates $130: palomitas medianas y dos refrescos medianos.
	•	Familiar: que incluye palomitas grandes, refrescos chicos y hot dogs.

Cada paquete tiene controles para aumentar o disminuir la cantidad y una imagen ilustrativa del combo.

Palomitas

El usuario puede seleccionar cantidades de palomitas:
	•	Chicas
	•	Medianas
	•	Grandes

Cada tamaño tiene su respectivo campo numérico.

Refrescos

Aquí se elige:
	•	Tamaño
	•	Sabor
	•	Cantidad

Incluye un botón Agregar para sumarlo a la selección.

Subtotal de Dulcería

En la parte inferior se muestra el total acumulado de los productos seleccionados. También aparece una lista de “Productos agregados” para llevar control de lo que el usuario ha elegido.

Al final están los botones:
	•	Limpiar: borra los productos seleccionados.
	•	Siguiente: avanza al ticket final.

Esta ventana permite toda la personalización de compra de alimentos y bebidas.

4. Ventana de Ticket.

Esta es la última ventana del proceso, donde se muestra el resumen de la compra antes de finalizarla. Su función es unir los subtotales de la taquilla y la dulcería para mostrar el monto total.

En la parte superior aparece el título “TICKET”, acompañado de imágenes de boletos cinematográficos en ambos lados, dando una apariencia más realista de recibo.

La ventana está dividida en dos secciones principales:

1. Subtotal de Taquilla

Muestra el total correspondiente a los boletos elegidos previamente.

2. Subtotal de Dulcería

Presenta la suma de los productos del módulo de dulcería.

En la parte derecha inferior se calcula automáticamente el Total final, que corresponde a la suma de ambos subtotales. El diseño utiliza texto en rojo para resaltar el total a pagar.

Finalmente, hay dos botones:
	•	Cancelar: para abortar la compra y regresar si es necesario.
	•	Finalizar: para concluir el proceso de compra y confirmar el ticket.

Es la ventana que cierra todo el flujo del sistema CinePlus.
