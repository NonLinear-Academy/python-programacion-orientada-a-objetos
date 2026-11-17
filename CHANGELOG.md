# CHANGELOG.md

## 2026-11-16
- Se creó `temario.md` con el temario aprobado.
- Se creó `01-del-procedimiento-al-objeto.ipynb`.
- Se aprobó `01-del-procedimiento-al-objeto.ipynb` sin cambios.
- Se creó y validó `02-clases-e-instancias.ipynb`.
- Se aprobó `02-clases-e-instancias.ipynb` sin cambios.
- Se creó y validó `03-metodos-de-instancia-de-clase-y-estaticos.ipynb`.
- Se creó y validó `04-encapsulamiento-propiedades-e-invariantes.ipynb`.
- Se creó y validó `05-metodos-especiales-dunder.ipynb`.
- Se creó y validó `06-herencia-super-y-mro.ipynb`.
- Se creó y validó `07-polimorfismo-y-clases-abstractas.ipynb`.
- Se creó y validó `08-composicion-frente-a-herencia-y-proyecto-integrador.ipynb`.
- Se ejecutó la auditoría global sobre los ocho cuadernos (videos 1 a 8) sin errores.
- Juliho aprobó sin cambios los cuadernos 3 a 8 (completando los ocho cuadernos de la serie en local).
- Se creó la carpeta `videos/` y se generó y verificó el paquete piloto del Video 1 (`01-del-procedimiento-al-objeto.mp4`, `01-del-procedimiento-al-objeto-miniatura.png`, `01-del-procedimiento-al-objeto.srt` y `01-del-procedimiento-al-objeto-youtube.md`) usando `edge-tts` (`es-MX-DaliaNeural`) y aceleración por hardware NVIDIA (`h264_nvenc`).
- Se regeneró el paquete piloto del Video 1 con la voz multilingüe `en-US-AvaMultilingualNeural` a petición de Juliho (para mejorar la pronunciación de `Python` y términos en inglés) usando `h264_nvenc`.
- Se regeneró el paquete piloto del Video 1 con `es-MX-DaliaNeural` aplicando un diccionario de pronunciación fonética únicamente al audio (`Páiton`, `Valiu Érror`, `Non Línier Acádemy`, `Fols`, `Tru`, `ínit`, `clas`, `mat`, `ge ce de`, `crear fracción`) y codificación NVIDIA (`h264_nvenc`).
- Se rediseñó por completo la presentación visual del Video 1 con diseño editorial moderno en HTML, CSS y SVG (45 cuadros en `1920` por `1080` píxeles con diagramas vectoriales, fórmulas vectoriales y resaltado progresivo de líneas de código) renderizados con Microsoft Edge y codificados con `h264_nvenc`, junto con la nueva miniatura (`1280` por `720` píxeles).
- Se actualizó la paleta completa del Video 1 (45 cuadros, diagramas vectoriales, editor de código y miniatura) al tema oscuro de alto contraste Monokai (`#272822`, `#1E1F1C`, `#F8F8F2`, `#A6E22E`, `#66D9EF`, `#F92672`, `#E6DB74`, `#FD971F`, `#AE81FF`) y se recodificó con `h264_nvenc`.
- Se instaló `eng-to-ipa`, se construyó el conversor determinista de IPA a fonética española y se regeneró el paquete piloto del Video 1 con la voz grave `es-MX-JorgeNeural` (`pitch='-16Hz'`), nivelación de sonoridad `loudnorm` y codificación NVIDIA (`h264_nvenc`).
- Juliho aprobó el piloto del Video 1 y se generaron y verificaron los paquetes audiovisuales completos de los Videos 2 a 8 en `videos/` (32 archivos totales para los 8 episodios) en tema Monokai con `es-MX-JorgeNeural`, fonética IPA y codificación `h264_nvenc`.
- A petición de Juliho (`/learn`), se persistió el flujo técnico de producción audiovisual en el skill global `nonlinear-video-tutorial` y se actualizaron las reglas de estilo audiovisual en `AGENTS.md`.
- Se crearon localmente `README.md`, `.gitignore` y `LICENSE` (licencia MIT) para el futuro repositorio `NonLinear-Academy/python-programacion-orientada-a-objetos`.
- Se inicializó el repositorio Git local en rama `main` con el primer commit de la serie completa.
- Con autorización de Juliho, se creó el repositorio público `NonLinear-Academy/python-programacion-orientada-a-objetos` en GitHub y se subió la rama `main`.
