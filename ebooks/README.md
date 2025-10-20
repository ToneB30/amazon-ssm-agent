# Jaylen's Big Game Ebook

This directory contains the LaTeX source for the picture book **"Jaylen's Big Game: A Basketball Story About Courage, Teamwork & Believing in Yourself."**

## Building the PDF

The document relies on `fontspec`, so it must be compiled with an engine that supports modern fonts, such as XeLaTeX or LuaLaTeX. After installing a TeX distribution that includes Noto Sans, run:

```bash
xelatex JaylensBigGame.tex
```

If XeLaTeX is unavailable, install it via your platform's TeX distribution (for example, TeX Live's `texlive-xetex` package) before compiling.
