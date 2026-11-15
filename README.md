# IA aplicada a l'educació · web dels materials

Web (MkDocs Material) amb els materials del curs per a l'alumnat: diapositives, pràctiques, solucions i guies d'ús en PDF, sessió a sessió.

- Els PDF es generen al repositori de treball (`curso-intro-ia-educacion`, carpeta `materials`) i es copien a `docs/pdf/`.
- Cada sessió es desbloqueja el seu dia: les instruccions són al principi de `mkdocs.yml`.
- En fer `push` a `main`, GitHub Actions construïx i publica la web a GitHub Pages.

Provar-la en local:

```bash
pip install -r requirements.txt
mkdocs serve
```
