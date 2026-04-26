# Ola

> Saluda a muchos de uno en uno.

Convierte una lista de números en mensajes de WhatsApp personalizados. Sin spam, sin servidores, sin cuenta.

## Demo

Activa GitHub Pages en este repo (Settings → Pages → Branch: `main` / `/root`) y la app queda disponible en:

```
https://paumartifelip-cpu.github.io/ola/
```

## Cómo funciona

1. Pega una lista de números (uno por línea, opcionalmente con nombre: `3312345678, María`).
2. Escribe el mensaje. Usa `{nombre}` para personalizar.
3. Pulsa **Generar links** y obtén un `wa.me` por contacto, listo para abrir.

## Características

- 25 países soportados con código de área.
- Plantilla con variable `{nombre}`.
- Vista previa en vivo del mensaje.
- Validación de números inválidos.
- Estadísticas: total / válidos / inválidos.
- Copiar individual, copiar todos, exportar CSV.
- Persistencia local (recuerda tu mensaje y país).
- 100% client-side. Tus datos nunca salen del navegador.

## Stack

Single-file HTML. Cero dependencias. Cero build. Cero tracking.

## Licencia

MIT.
