# COOL ANIMAL

Sitio de tienda estático, mobile-first, hecho con HTML, CSS y JavaScript sin frameworks.

## Sitio publicado

https://sspni.github.io/coolanimal/

## Publicar

Publica los archivos de esta tienda en la raíz del repositorio `coolanimal` y activa GitHub Pages desde la rama `main`. Abre `index.html` para previsualizar. No requiere compilación ni dependencias.

## Configuración antes de publicar

Edita `config.js` con los datos confirmados del negocio:

- `whatsappNumber`: número internacional solo con dígitos, por ejemplo el prefijo de país seguido del número.
- `instagramUsername`: usuario sin `@`.
- `deliveryFee`: domicilio en COP. Si se deja en `null`, el cliente puede escribir el valor confirmado en el carrito; sin ese dato el total queda “Por confirmar”.
- `paymentMethods`: opciones visibles en checkout. No incluir datos o cuentas de pago que no hayan sido confirmados.

El teléfono y el perfil de Instagram de `config.js` ya están configurados. La tarifa de domicilio sigue pendiente de confirmación, por eso el carrito muestra «Por confirmar» hasta que el cliente ingrese su valor. Cuando hay un número configurado, el pedido abre WhatsApp; si falta, permite copiar el mensaje. Revisa los métodos de pago antes de cambiarlos.

## Reemplazar visuales

El logotipo oficial provisto está en `assets/cool-animal-logo.png`; se usa sin recolorear. El catálogo muestra las fotografías disponibles para las paletas de fresa y banano y el pack. El hero conserva la imagen de referencia del proyecto. Reemplaza estas fotografías cuando tengas nuevas imágenes definitivas, actualizando `app.js` o `index.html` según corresponda.

Los precios y descripciones del catálogo se encuentran en `app.js`.
