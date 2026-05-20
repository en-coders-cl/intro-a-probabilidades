# Clase: Intro a Probabilidades
**en_coders** — Ciencia de Datos Aplicada

---

## Cómo renderizar

```bash
# Documento HTML completo (requiere Python + scipy + matplotlib)
quarto render clase_intro-probabilidades.qmd

# Presentación Beamer (requiere LaTeX: TinyTeX o TeX Live)
quarto render slides_intro-probabilidades.qmd

# Instalar TinyTeX si no tienes LaTeX:
quarto install tinytex
```

## Estructura del paquete

```
class_intro-probabilidades/
├── clase_intro-probabilidades.qmd   # Documento detallado (el "libro")
├── slides_intro-probabilidades.qmd  # Presentación Beamer para el stream
├── assets/
│   └── logo_en_coders.png           # Logo del canal
└── README.md                        # Este archivo
```

## Notas para el stream

- **Los primeros 10 minutos** son warm-up informal — charla libre, sin slides. Conéctate antes de la hora para recibir a la gente.
- **La pausa de memes** va alrededor del minuto 60, al terminar la Parte 1.
- Los comentarios `<!-- PIZARRA: ... -->` en el .qmd son señales para usar la pizarra física. Están en las secciones de: teoría de la medida, axiomas de Kolmogorov, variable aleatoria, PMF vs PDF, y LLN/CLT.
- El meme del día es el **"Two Buttons"** — preparar la imagen antes del stream o improvisar el slide de texto incluido.

## Dependencias Python

```bash
pip install numpy pandas matplotlib scipy
```

## Segmentos de la clase

| Tiempo | Segmento | Contenido |
|--------|----------|-----------|
| 0–10 min | Warm-up | Charla libre (fuera de slides) |
| 10–15 min | Intro | Bienvenida + contexto empresarial |
| 15–60 min | Parte 1 | Conjuntos → Medida → Kolmogorov → VA → Discretas/Continuas → VA vs Muestra |
| 60–65 min | Pausa memes | Two Buttons slide |
| 65–110 min | Parte 2 | PMF/PDF → CDF → E[X]/Var → LLN → CLT → Z-Test + Demo Python |
| 110–120 min | Cierre | Resumen + recursos + próxima clase |
# intro-a-probabilidades
