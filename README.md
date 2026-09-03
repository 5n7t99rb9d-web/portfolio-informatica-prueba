# Informática I · Portfolio

Plantilla del portfolio individual de Informática I de 1.º de Bachillerato para el curso 2026-2027.

- `docs/` contiene las páginas y las imágenes del portfolio web.
- `src/` contiene el código fuente de los proyectos.

## Ejecutar el portfolio localmente

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
mkdocs serve
```

Después, abre `http://127.0.0.1:8000/` en el navegador. En macOS o Linux, el comando de activación es `source .venv/bin/activate`.

## Flujo normal de trabajo

1. Actualizar el repositorio desde GitHub Desktop.
2. Trabajar en los documentos o programas.
3. Guardar los cambios.
4. Hacer un commit en GitHub Desktop.
5. Hacer push para publicar los cambios.

GitHub Actions construye y publica automáticamente el portfolio en GitHub Pages después de cada push a `main`.
