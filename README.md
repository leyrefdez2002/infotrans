# index
# infotrans

**Información, recursos y herramientas para personas trans que viven en España, hayan nacido aquí o hayan llegado de fuera.**

infotrans es una aplicación web pensada para el móvil. No pide registro, no usa cookies y no guarda nada de lo que escribe quien la usa.

> **Estado: prototipo.** El contenido es orientativo y debe revisarse con entidades y profesionales antes de difundirla ampliamente (ver [Avisos importantes](#avisos-importantes)).

---

## Qué incluye

| Sección | Contenido |
| --- | --- |
| **Inicio** | Bienvenida y filtro según la situación: vivo aquí con documentación / acabo de llegar o soy migrante. |
| **Recursos** | Directorio de asociaciones y servicios con enlaces, buscador, filtros por tipo (asociaciones, asilo y migración, familias, VIH y salud sexual, salud mental, hormonas y salud trans) y por comunidad autónoma. |
| **Trámites** | Guías sobre cambio de nombre y mención de sexo, sanidad, empadronamiento, protección internacional, nombre sentido en servicios y una serie sobre VIH (prueba, PrEP, PEP, vivir con VIH, VIH y migración). |
| **Comunidad** | Descripción del espacio comunitario previsto y formulario para recoger ideas (no se guarda en esta versión). |
| **Ayuda urgente** | Teléfono de emergencias 112 y pautas básicas ante violencia, discriminación o malestar emocional. |
| **Aprender** | Conceptos básicos, mitos y realidades, preguntas frecuentes, salud sexual y fertilidad, cirugías, voz, guías para familias, docentes y empresas, derechos, modelo de reclamación, preparador de consultas, calculadora de gastos y consejos de privacidad. |
| **Herramientas** | Tarjeta de emergencia, carta para pedir que se use el nombre sentido, lista de primeros pasos al llegar a España, glosario en español, inglés y francés, información sobre hormonas con reducción de riesgos y calculadoras de conversión (volumen y unidades de analítica). |

Además, hay un botón de **salida rápida** siempre visible, que saca a la persona de la página al instante.

## Idiomas

Español, inglés, francés, catalán/valenciano, gallego y euskera.

La interfaz está traducida a todos. Los textos largos (guías de trámites, descripciones de muchas entidades, secciones de Aprender y Herramientas) están por ahora solo en castellano y la app lo indica con un aviso. **Las traducciones deben revisarlas personas nativas.**

## Privacidad

- No hay registro ni cuentas.
- No se usan cookies, almacenamiento local ni analítica.
- Lo que se escribe en formularios y herramientas no sale del dispositivo ni se guarda.
- Los enlaces externos se abren en una pestaña nueva.
- La única petición externa de la página es la tipografía Nunito de Google Fonts, que es opcional: si no carga, se usa la fuente del sistema.

## Cómo verla

Es un único archivo HTML, sin dependencias ni proceso de compilación.

1. Descarga `index.html`.
2. Ábrelo con doble clic en cualquier navegador.

## Cómo publicarla con GitHub Pages

1. Sube `index.html` a este repositorio (debe llamarse así).
2. En **Settings → Pages**, en *Branch*, elige `main` y la carpeta `/ (root)`, y pulsa **Save**.
3. En uno o dos minutos estará disponible en `https://TU-USUARIO.github.io/infotrans`.

## Estructura del proyecto

```
index.html   # Toda la aplicación: estructura, estilos y lógica
README.md    # Este archivo
```

Se ha escrito con HTML, CSS y JavaScript sin librerías.

## Avisos importantes

- **No es asesoría legal ni médica.** Los contenidos legales y sanitarios son orientativos. La normativa cambia y los circuitos sanitarios varían entre comunidades autónomas.
- **La sección de hormonas no recomienda dosis.** Ofrece información de reducción de riesgos y calculadoras de conversión. La pauta debe fijarla un profesional sanitario.
- **Hay que verificar** los enlaces, nombres y datos de contacto de las entidades y los teléfonos antes de difundir la app.
- **Las traducciones** a lenguas distintas del castellano deben revisarse con personas nativas.

## Hoja de ruta

Funciones previstas que necesitan servidor, cuentas y moderación:

- Chat, foros y grupos moderados.
- Mentoría y acompañamiento entre personas trans.
- Mapa de servicios inclusivos con valoraciones.
- Agenda de eventos LGTBIQ+.

Funciones que se podrían hacer guardando los datos solo en el dispositivo:

- Diario y seguimiento de salud con PIN.
- Recordatorios discretos de citas y tratamientos.
- Cuaderno de pruebas para solicitudes de asilo.
- Ejercicios y simulador de voz.

Otras ideas en estudio: red de acompañantes voluntarios, directorio de profesionales amigables validado por la comunidad, alojamiento temporal seguro, bolsa de empleo inclusiva y fondo de apoyo mutuo.

## Cómo colaborar

Se agradece especialmente:

- Revisar y corregir recursos, enlaces y datos de contacto.
- Añadir entidades de comunidades autónomas que aún no aparecen.
- Revisar traducciones y traducir los textos largos.
- Revisar los contenidos legales y sanitarios (personas expertas o entidades).
- Probar la app con personas trans, nacionales y migrantes, y compartir qué falta o qué sobra.

Puedes abrir un *issue* en este repositorio con tus sugerencias.

## Licencia

Pendiente de elegir. Una opción habitual para proyectos de este tipo es una licencia abierta como MIT para el código y Creative Commons (CC BY 4.0) para los contenidos.
