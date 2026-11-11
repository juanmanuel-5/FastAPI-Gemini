# 🍳 API de Recetas con Gemini y FastAPI

Genera recetas en JSON usando el nivel gratuito de Gemini.

## Instalación
1. `python -m venv .venv` y actívalo
2. `pip install -r requirements.txt`
3. Copia `.env.ejemplo` a `.env` y pon tu API key de https://aistudio.google.com/apikey

## Uso
    fastapi dev main.py

- Documentación interactiva: http://127.0.0.1:8000/docs
- Ejemplo: http://127.0.0.1:8000/recetas/generar?tipo=postres&cantidad=3

## Estructura
    main.py            # La API
    index.html         # Cliente web de ejemplo
    requirements.txt   # Dependencias
    .env.ejemplo       # Plantilla de variables de entorno
