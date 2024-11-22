# ¡Radio en Vivo!

Este proyecto te permite montar una estación de radio en vivo, transmitiendo desde tu PC a través de Icecast. Si tienes un micrófono y quieres comenzar a transmitir, este es tu lugar.

## ¿Qué tienes aquí?

1. **index.html**: La página web que te deja escuchar la radio en vivo. Solo abre este archivo en un navegador y listo.
2. **Icecast**: El archivo `icecast.xml` que configura tu servidor de transmisión (Icecast).
3. **BUTT**: Un archivo `butt.exe` (simulado por ahora) que te permite transmitir audio desde tu micrófono.  
4. **Liquidsoap**: Un script básico `transmitir.liq` para transmitir audio a través de Liquidsoap.
5. **Archivos de audio**: Algunos ejemplos de archivos de audio (aunque por ahora son solo simulaciones).

## ¿Cómo hacerlo funcionar?

1. **Configura Icecast**:
   - Si no tienes Icecast instalado, descárgalo desde [aquí](https://icecast.org/download/).
   - Asegúrate de poner `icecast.xml` en la carpeta correcta de Icecast y configúralo para escuchar en el puerto `8000`.

2. **Configura BUTT**:
   - Descarga [BUTT (Broadcast Using This Tool)](https://butt.sourceforge.io/), que es lo que vas a usar para transmitir.
   - Usa el archivo `butt.exe` para transmitir tu voz a Icecast (conéctalo a `localhost:8000`).

3. **Ver la página**:
   - Abre el archivo `index.html` en tu navegador para empezar a escuchar la radio en vivo.

## ¿Por qué no usas otro software de radio?

La idea aquí es que sea fácil y rápido, y este setup no necesita de muchas configuraciones complicadas. Si quieres algo más avanzado, puedes cambiar las configuraciones de Icecast o Liquidsoap como prefieras.

## Cosas que puedes cambiar

- **Configuración de Icecast**: Si te da problemas, revisa el archivo `icecast.xml` y edita las opciones.
- **Script Liquidsoap**: Si te interesa añadir más fuentes de audio o algo más avanzado, edita el archivo `transmitir.liq`.

## ¿Qué falta?

Este proyecto está en constante mejora. Algunas cosas que podrías agregar:
- Más opciones de transmisión de audio.
- Un diseño más bonito para la página web.
- Un sistema para mostrar lo que estás transmitiendo en la web.

## ¡Eso es todo!

Espero que te diviertas transmitiendo. Si tienes problemas, o si sabes de algo que podría mejorar, ¡no dudes en avisarme! ¡Que comience la transmisión! 🎶🎤

