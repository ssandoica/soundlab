# SoundLab — reglas de desarrollo compartidas

Autor: Sergio Bernardos Sandoica · IES Puerta Bonita · CFGS Sonido.
Proyecto docente: aprender escuchando, viendo y experimentando.

## Flujo de trabajo
- main: versión oficial. No publicar cambios en index.html sin aprobación explícita del profesor.
- beta: versión integrada de pruebas. Cada tarea parte de beta; usar una rama propia (desarrollo-chatgpt, desarrollo-claude o una rama por tarea) y abrir una pull request hacia beta.
- Antes de editar, revisar estado, tareas y cambios recientes; evitar modificar simultáneamente los mismos archivos.
- Una beta aprobada se copia al directorio beta/ de main para previsualización web; publicar en la raíz solo con autorización expresa. No confundir las ramas con la web desplegada.
- Registrar cada cambio, pruebas efectuadas, limitaciones y dependencias en la pull request. No afirmar que se probó lo que no se probó.
- No introducir claves, datos de alumnos ni material sin derechos; mantener créditos y licencias de audio.

## Alcance e identidad
- Conservar la portada atractiva y firma discreta del autor. Interior cálido, musical, estética rave sin sacrificar contraste ni legibilidad.
- Organizar CES y Electroacústica por las unidades reales del profesor, únicamente contenidos impartidos o autorizados. No inventar la programación ni anticipar unidades.
- Punto de partida deseado: SoundLab Aula (HTML con 19 laboratorios, pistas reales, circuitos y filtros básicos); confirmar su incorporación antes de tratarlo como código presente.
- Prioridades: localización binaural con cabeza interactiva, visualizaciones de ondas con escala espacial fija y zoom, electricidad (serie/paralelo/mixtos) y filtros pasivos de primer orden con carga ideal.
- Cada laboratorio: explicación, simulación, práctica guiada, ejercicio con autocorrección cuando proceda.
- Mantener controles y gráficas a la vista simultáneamente en escritorio; probar móvil, teclado, contraste y navegación por hash.
- Rigor: unidades explícitas, hipótesis físicas, signos ITD/ILD, escala fija cuando importa la magnitud; no presentar modelos de lateralización como ángulos medidos ni dB digitales como SPL calibrados.
- Audio: volumen físico bajo, evitar saltos de nivel, preservar sincronía, comprobar Play/Stop y que no queden nodos activos. No alterar el DSP sin una tarea explícita y pruebas.
- Conservar rutas/enlaces y funcionalidades existentes; migrar gradualmente a módulos HTML/CSS/JS y recursos de audio separados, sin reescritura indiscriminada.
- Antes de publicar: revisar consola, navegación, controles, cálculos, gráficos, audio, móvil y licencias. La escucha física corresponde al profesor.
