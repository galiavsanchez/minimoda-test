# Capacidades: Clase 2 – MCP

## Herramienta

Hice la práctica con **Claude Code** en lugar de Codex.

## Playwright MCP

Abrió MiniModa, eligió la **Remera Dino Aventurero** (tenía stock), la agregó al carrito, sacó capturas y contó el recorrido.

- Tiempo del agente: **48 s**

## MCP casos

Tiene las herramientas `crear_caso_prueba` y `listar_casos`. Creó el caso **CP-001** y lo listó.

- Tiempo del agente: **15 s**
- Crear el MCP: **1 min 38 s** (sin contar el tiempo de mis aprobaciones)

## Comparación de tiempos

> Los tiempos a mano son **medidos**.

| Tarea | A mano (medido) | Agente | Ahorro |
|---|---|---|---|
| Recorrer la tienda y agregar el producto | 1 min 36 s | 48 s | 48 s |
| Escribir el caso de prueba | 1 min 16 s | 15 s | 1 min 01 s |
| **Total** | **2 min 52 s** | **1 min 03 s** | **1 min 49 s** |

Si se suma el tiempo de crear el MCP (1 min 38 s), el agente tarda 2 min 41 s en total y el ahorro en esta primera vez baja a 11 s. Ese tiempo se invierte una sola vez: en los usos siguientes el MCP ya está creado.

## Límites

- Como no abrió la tienda para crear el caso, escribió pasos genéricos. Hay que revisar el caso o pedirle que use Playwright para ajustarlo a la página real.
- Necesité reiniciar Claude Code para que cargara los MCP nuevos.
