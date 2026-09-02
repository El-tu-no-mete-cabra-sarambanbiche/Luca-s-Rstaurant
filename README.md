# Luca's Restaurant

Página web responsive para **Luca's Restaurant**, un restaurante en La Fortuna, Costa Rica, pensado para visitantes de Norteamérica y Europa.

## Funciones

- Menú bilingüe en español e inglés.
- Platos costarricenses, italianos y opciones vegetarianas.
- Diseño responsive para teléfono, tablet y escritorio.
- Área de reservas con selección de fecha, hora, cantidad de personas y mesa.
- Disponibilidad visual de 30 mesas, con mesas libres y no disponibles.
- Confirmación visual de la solicitud de reserva.
- Área de pago en línea para un depósito de reserva de ₡10,000.
- Imágenes gastronómicas y navegación por secciones.

## Ejecutar localmente

No requiere instalación ni dependencias. Abre `index.html` en un navegador; este archivo redirige a `Restaurante.html`.

También puedes servir la carpeta con cualquier servidor web local, por ejemplo:

```powershell
python -m http.server 8000
```

Después visita `http://localhost:8000`.

## Estructura

```text
.
├── index.html
├── Restaurante.html
└── README.md
```

## Nota sobre reservas y pagos

La selección de mesas, la confirmación de reserva y el pago funcionan actualmente como demostración front-end. Los datos no se guardan y el formulario de pago no procesa tarjetas reales. Para producción se debe conectar un backend y una pasarela segura como Stripe, PayPal o el proveedor local elegido.

## Publicar en GitHub Pages

1. Sube los archivos del proyecto a un repositorio de GitHub.
2. En el repositorio, abre **Settings > Pages**.
3. Selecciona la rama principal y la carpeta raíz (`/root`).
4. Guarda la configuración y abre la URL que GitHub Pages genere.
