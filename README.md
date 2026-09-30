# Claws Studio

Prototipo interactivo en español para un spa, con colores rosados pastel.

- **Web:** https://eheyen.github.io/aura-spa/
- **Código:** https://github.com/Eheyen/aura-spa

GitHub Pages publica la carpeta `docs/` de la rama `main`. Los cambios enviados a esa rama actualizan la web después de que finalice la publicación.

## Abrir en Visual Studio Code

Abrir esta carpeta desde **Archivo → Abrir carpeta**, o clonar el repositorio:

```sh
git clone https://github.com/Eheyen/aura-spa.git
cd aura-spa
code .
```

## Incluye

- Página de clientes con tratamientos, galería y solicitud de cita por WhatsApp al +51 914 889 367.
- Login de demostración para administración.
- Agenda, registro de clientes, historial y frecuencia de visitas.
- Diseño adaptable a celular y escritorio.

## Ejecutar localmente

Con Node.js instalado, ejecutar desde esta carpeta:

```sh
node preview.cjs
```

Abrir http://127.0.0.1:4173.

## Acceso de demostración

- Correo: `admin@auraspa.demo`
- Contraseña: `AuraDemo2026`

Estas credenciales son públicas y solo simulan el flujo de acceso. No existe autenticación de servidor. Los datos de administración son ficticios, están en el navegador y se reinician al recargar. No utilizar la maqueta de administración para almacenar datos personales.

La reserva pública abre WhatsApp con un mensaje preparado que incluye nombre, tratamiento, fecha y hora de preferencia y teléfono de contacto. El cliente debe enviar el mensaje; el spa confirma disponibilidad y precio por el chat. La web no envía mensajes automáticamente, no confirma citas y no guarda solicitudes en la agenda de maqueta.

## Archivos

`docs/` contiene el sitio estático (HTML, CSS, JavaScript y fotografías). `preview.cjs` es el servidor de vista previa local. No requiere compilación ni instalación de dependencias.

Para alojar el diseño en un servicio de páginas estáticas, publicar el contenido de `docs/`. Un repositorio en GitHub comparte el código; GitHub Pages u otro alojamiento permite navegar la página.

## Fotografías de referencia

Las imágenes no representan trabajos reales de Aura Spa. Fuentes:

- [Andrea Prochilo — Pexels](https://www.pexels.com/photo/relaxing-spa-massage-therapy-at-wellness-center-31234759/)
- [Gustavo Fring — Pexels](https://www.pexels.com/photo/woman-getting-facial-treatment-3985323/)
- [ikhbale — Unsplash](https://unsplash.com/photos/a-spa-room-with-a-spa-bed-and-a-shower-lyicBM-7zFA)

Revisar las condiciones de cada fuente antes de reutilizar sus fotografías.


## Datos del negocio

Nombre, servicios y zona tomados de la biografía pública de https://www.instagram.com/clawsstudio2026/: Claws Studio; manicure, pedicure, diseño de cejas y lash lifting; Chorrillos, Lima, Perú. Referencia: frente al Real Plaza de Av. Guardia Civil, Chorrillos. Mapa verificado: https://maps.app.goo.gl/yHJDQrnFAMLaTJYN8. Precios publicados de preventa: soft gel S/ 55, rubber gel S/ 49, esmaltado gel S/ 29, laminado de cejas S/ 39; vigencia pendiente de confirmación. WhatsApp corregido según las capturas del perfil y publicación del negocio: +51 914 889 367.

