# ClarIA

Aplicación web de un solo fichero que convierte los **materiales que ya has elaborado** (PDF, Word, PowerPoint, texto) en una explicación clara, diagramas, una página web interactiva y un vídeo explicativo con voz.

**Usar la app:** https://fborrasumh.github.io/claria/

## Qué hace

1. **Explicación clara.** Reescribe el contenido en inglés según las reglas de **ASD-STE100** (Simplified Technical English) y en español con una adaptación de esas reglas. El código comprueba longitud de frase, voz pasiva, tiempos verbales, formas -ing, contracciones y puntuación, y pide a la IA que reescriba las frases que no cumplen. Muestra el porcentaje de conformidad antes y después.
2. **Diagramas.** La IA propone la estructura (proceso, ciclo, jerarquía, comparación o línea de tiempo); el código la valida y la dibuja en SVG con un estilo uniforme y texto alternativo.
3. **Página web.** Un único HTML con cambio de idioma, diagramas paso a paso, preguntas de comprobación y una presentación narrada.
4. **Vídeo.** Escenas con diagramas animados, narración y subtítulos, grabadas en el navegador y descargables en WebM.
5. **Paquete ZIP** con todo lo anterior, el audio, el informe de calidad y la lista de fuentes.

## Fidelidad al material

La IA trabaja solo con tu material. Cada idea clave lleva una cita literal que el código comprueba; las cifras que no aparecen en el material se señalan. El texto es editable antes de compartirlo.

## Privacidad

Los ficheros y el proyecto se guardan en el navegador. Al generar, el texto del material y de la narración sale hacia OpenAI con tu propia clave. No subas datos personales de estudiantes ni de pacientes.

## Límites

- ASD-STE100 está definida solo para inglés. ClarIA aplica sus reglas medibles; **no incluye el diccionario oficial de palabras aprobadas ni certifica conformidad** con la especificación.
- El vídeo se graba en tiempo real: dura lo mismo que la narración y requiere dejar la pestaña visible.
- No hace OCR de PDF escaneados y no usa las imágenes de los materiales.
- La IA puede equivocarse; la responsabilidad del contenido es de quien lo publica.

## Autoría

Fernando Borrás Rocher · Universidad Miguel Hernández de Elche.

## Cómo citar

Borrás Rocher, F. (2026). *ClarIA* (v1.0.0) [Software]. Universidad Miguel Hernández de Elche. (DOI en trámite)

## Licencia

MIT. Véase [LICENSE](LICENSE).
