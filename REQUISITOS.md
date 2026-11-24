# Requisitos: App móvil "Asfalto & Cuero"

Accesorios de cuero para moteros: chaquetas, correas y billeteras.

- **Autor:** Arana jimenez julian
- **Fecha:** 23/11/2026
- **Dispositivo base:** iPhone 390×844
- **Diseño en Figma:** https://www.figma.com/design/6rnftwErFLqWXkIEC6WelL

---

## RF-01 · Inicio de sesión
- **Requisito:** Permitir al cliente ingresar a su cuenta.
- **Especificación:** Pantalla "01 Login" con foto de moto de fondo con degradado oscuro, marca en Oswald, campos de correo y contraseña, opciones "Recordarme" y "¿Olvidaste tu contraseña?", botón verde "Iniciar sesión" y enlace "Regístrate".
- **Criterio de aceptación:** Se ven los dos campos con su etiqueta, el botón principal destacado en verde y el enlace de registro, todo legible sobre la foto.
- **Historia de usuario:** Como cliente quiero ingresar con mi correo y contraseña para acceder a mi cuenta.

## RF-02 · Inicio con categorías
- **Requisito:** Llegar rápido a las tres categorías de productos.
- **Especificación:** Pantalla "02 Inicio" con saludo, banner de nueva colección, tres tarjetas de categoría (Chaquetas, Correas, Billeteras) con foto, lista "Más vendidos" y barra de pestañas inferior.
- **Criterio de aceptación:** Las tres categorías son visibles sin hacer scroll y la pestaña "Inicio" aparece marcada en la barra inferior.
- **Historia de usuario:** Como motero quiero ver chaquetas, correas y billeteras para llegar rápido a lo que busco.

## RF-03 · Catálogo con filtros
- **Requisito:** Explorar y filtrar los productos.
- **Especificación:** Pantalla "03 Catálogo" con chips de filtro (Todos, Chaquetas, Correas, Billeteras), cuadrícula de 2 columnas con foto, nombre y precio en pesos colombianos.
- **Criterio de aceptación:** El filtro activo se distingue (fondo cuero), los chips caben en 390 px sin cortarse y cada tarjeta muestra foto, nombre y precio.
- **Historia de usuario:** Como comprador quiero filtrar por tipo de producto para comparar opciones.

## RF-04 · Detalle de producto
- **Requisito:** Conocer un producto antes de comprarlo.
- **Especificación:** Pantalla "04 Detalle de producto" con foto grande, botón volver, nombre, precio, descripción, selector de talla (S, M, L, XL), selector de color y botón "Agregar al carrito".
- **Criterio de aceptación:** Talla y color seleccionados se distinguen visualmente y el botón de compra es visible sin scroll.
- **Historia de usuario:** Como comprador quiero ver talla, color y descripción para decidir mi compra.

## RF-05 · Carrito de compras
- **Requisito:** Revisar el pedido antes de pagar.
- **Especificación:** Pantalla "05 Carrito" con los productos agregados (foto, nombre, talla, cantidad con − y +, precio), resumen con subtotal, envío y total, y botón "Finalizar compra".
- **Criterio de aceptación:** El total corresponde a la suma del subtotal y el envío, y el botón "Finalizar compra" se ve en verde debajo del resumen.
- **Historia de usuario:** Como comprador quiero revisar y ajustar mi pedido para confirmar el total antes de pagar.

## RF-06 · Estilo visual coherente
- **Requisito:** Mantener una identidad visual única en todas las pantallas.
- **Especificación:** Paleta: negro asfalto `#121212`, superficie `#1D1B19`, cuero `#8B5A2B`, cobre `#C98B4B`, crema `#F1E6D4`, verde bosque `#1F4D36`. Tipografías: Oswald para títulos e Inter para texto. Barra de pestañas y botones iguales en todas las pantallas. Todas las pantallas se organizan con auto-layout.
- **Criterio de aceptación:** Las 5 pantallas usan los mismos colores, tipografías, radios de borde y estilo de botones.
- **Historia de usuario:** Como diseñador quiero componentes y colores consistentes para que la app se sienta como una sola marca.
