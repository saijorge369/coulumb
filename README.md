# Rife Audio Studio

Aplicación HTML local para generar tonos de audio a partir del listado extraído de `281696481-Frecuencias-Rife.pdf`.

## Cómo abrirlo

1. Abra `index.html` con Safari, Chrome, Edge o Firefox.
2. En iPhone o Android, suba la carpeta completa a un servidor o alojamiento gratuito y abra la URL.
3. Mantenga juntos estos tres archivos: `index.html`, `styles.css`, `app.js` y `frequency-data.js`.

## Uso

- Busque una entrada por nombre o escriba una frecuencia manual, por ejemplo `528 Hz`.
- Presione `Agregar` para programar hasta 6 frecuencias consecutivas.
- La duración por frecuencia va de 1 a 15 minutos; por defecto son 3 minutos.
- Entre una frecuencia y otra hay 5 segundos de espera automática.
- Use `PLAY`, `PAUSE` y `STOP` para controlar la sesión.
- El volumen se ajusta con el deslizador.
- El modo binaural separa ligeramente la frecuencia entre izquierda y derecha, por lo que funciona mejor con audífonos.
- El ruido blanco agrega una capa suave de audio continuo.
- Si una frecuencia es demasiado alta para reproducirse por audio, el programa usa un armónico menor dentro del rango audible.

## Setup administrador

- Usuario: `admin`
- Password: `OmSaiRam1594`

Desde Setup puede cambiar:

- Nombre del programa.
- Autor.
- Texto de licencia.
- Copyright.
- Tema visual entre 8 modelos: equipo sofisticado, blanco, negro, clásico, minimalista, aqua médica, grafito y solar suave.

Los cambios se guardan en el navegador mediante `localStorage`.

## Protección de copia

La protección incluida es disuasiva: bloquea clic derecho y reemplaza el texto copiado mientras el interruptor esté activo. En una aplicación HTML local no existe protección fuerte contra copia, porque el navegador necesita descargar el código para ejecutarlo. Para protección real en servidor conviene agregar autenticación, licencias por usuario, ofuscación/minificación y control de acceso.

## Texto original corregido

Quiero un programa en HTML que pueda generar todas estas frecuencias por audio y que, al reproducirlas, duren de 1 a 15 minutos; por defecto, 3 minutos. También debe poder programar hasta 6 frecuencias consecutivas, dejando 5 segundos de espera entre una y otra.

El usuario puede escribir el nombre de la frecuencia o seleccionarla desde el listado. La presentación debe ser moderna, tipo equipo sofisticado. Cada vez que se reproduce una frecuencia debe mostrarse en ejecución: `Frec. 1 = xxxxxxx`, junto con el tiempo que falta para terminar la primera frecuencia. El resto debe mostrarse en espera.

Debe existir la posibilidad de digitar una frecuencia especial que aún no exista y poder guardarla. Al inicio debe haber un setup para escoger idioma: español, inglés o francés.

Autor: Prof Wong Om Sai Ram. Copyright 2026. Licencia Especial: Dr. Luis Almeida. Debe existir la opción de cambiar todos estos datos. El setup solo entra con administrador: usuario `admin`, password `OmSaiRam1594`.

Debe servir para cualquier navegador: iPhone, Android, Safari, Chrome, etc. Debe incluir alguna protección contra copia ilícita. En el futuro se pondrá en un servidor gratuito; por ahora será para probar en mi MacBook.

La entrega debe incluir explicación de uso. En setup debe haber por lo menos 8 modelos de pantalla: fondo blanco, negro, clásico, minimalista, etc. También debe incluir botones STOP, PLAY y PAUSE, control de volumen con deslizador, opción binaural, opción de ruido blanco y clasificación de ondas cerebrales.

Si hay frecuencias muy altas, se pueden usar armónicos menores. Al terminar, debe presentarse una infografía a color de todo lo que hace el programa para entregar a los pacientes.

Incluir beneficios y referencias científicas reales sobre cómo el sonido, la música, la estimulación auditiva o la vibración pueden influir en salud y bienestar. No incluir afirmaciones falsas ni testimonios inventados; todo debe ser real y comprobable.

## Nota médica

Esta herramienta es educativa y complementaria. No diagnostica, trata, cura ni previene enfermedades. Las referencias científicas incluidas apoyan áreas como música, estimulación auditiva, ansiedad, dolor, sueño o vibración en contextos específicos; no demuestran que las frecuencias Rife curen enfermedades.
