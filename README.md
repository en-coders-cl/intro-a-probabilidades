# Clase: Intro a Probabilidades
**en_coders** 

---

## Cómo renderizar

```bash
# Documento HTML completo (requiere Python + scipy + matplotlib)
quarto render clase_intro-probabilidades.qmd

# Presentación Beamer (requiere LaTeX: TinyTeX o TeX Live)
quarto render slides_intro-probabilidades.qmd

# Instalar TinyTeX si no tienes LaTeX:
quarto install tinytex

# Presentación RevealJS (no requiere LaTeX)
quarto render revealjs_intro-probabilidades.qmd
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

