---
id: CP-001
titulo: "Agregar un producto con stock al carrito"
requisito: "Carrito de compras - Agregar producto con stock disponible (MiniModa)"
prioridad: alta
fecha: 2026-11-01
---

# CP-001 — Agregar un producto con stock al carrito

**Requisito:** Carrito de compras - Agregar producto con stock disponible (MiniModa)
**Prioridad:** alta
**Fecha de creación:** 2026-11-01

## Pasos

1. Abrir https://minimoda-navy.vercel.app/ en el navegador
2. Verificar que el carrito esté vacío (contador en 0 o sin ítems)
3. Seleccionar un producto del catálogo que tenga stock disponible
4. Si el producto tiene variantes (talle/color), seleccionar una opción con stock
5. Hacer clic en el botón 'Agregar al carrito'
6. Abrir el carrito y revisar su contenido

## Datos de prueba

Sitio: https://minimoda-navy.vercel.app/ — Producto: cualquier producto del catálogo con stock > 0 — Cantidad: 1 — Estado inicial: carrito vacío

## Resultado esperado

El producto se agrega al carrito sin errores; el contador del carrito se incrementa a 1; en el carrito aparece el producto con nombre, variante seleccionada (si aplica), precio correcto, cantidad 1 y el subtotal/total coincide con el precio del producto.
