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

## Dependencias Python

```bash
pip install numpy pandas matplotlib scipy
```

