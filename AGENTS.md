# AGENTS.md

## Propósito de la carpeta
Material de la serie «Programación orientada a objetos con Python» del canal NonLinear Academy.

## Estructura
- `temario.md`: temario aprobado de 8 videos.
- `NN-titulo.ipynb`: un cuaderno de Colaboratory por video.
- `videos/`: paquete audiovisual por video (`NN-titulo.mp4`, `NN-titulo-miniatura.png`, `NN-titulo.srt` y `NN-titulo-youtube.md`).

## Reglas para agentes
- Escribe en español, sin abreviaturas.
- En matemáticas y algoritmos, usa estilo formal: definiciones, entrada y salida, y notación sin ambigüedad.
- No incluyas votaciones del grupo.
- Un solo archivo por video; sin copias con otros nombres.
- No publiques sin aprobación de Juliho.

## Producción audiovisual y estilo
- **Diseño visual:** tema oscuro de alto contraste Monokai (`#1E1F1C`, `#272822`, texto `#F8F8F2`, acentos `#A6E22E`, `#66D9EF`, `#F92672`, `#E6DB74`, `#FD971F`, `#AE81FF`), maquetación editorial en HTML, CSS y SVG con tres pasos progresivos por escena (`1920` por `1080` píxeles) y miniaturas en `1280` por `720` píxeles.
- **Voz y fonética:** usar voz masculina mexicana grave `es-MX-JorgeNeural` (`pitch='-16Hz'`) con nivelación estándar (`loudnorm`). No usar voces multilingües (`MultilingualNeural`). Convertir términos técnicos en inglés mediante transcripción fonética oficial IPA (`eng-to-ipa`) únicamente para el audio, conservando la ortografía original en pantalla, subtítulos y fichas.
- **Navegador y hardware:** usar Microsoft Edge en modo sin interfaz y con perfil temporal aislado (sin interferir con Brave) para renderizar cuadros, y codificar video con aceleración por hardware NVIDIA (`h264_nvenc`).
