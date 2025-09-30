# TicketsBot (Discord)

Bot de tickets con **discord.py 2.x**.

## Archivos incluidos
- `main.py` → código del bot
- `requirements.txt` → dependencias
- `.gitignore` → evita subir `.env`
- `.env.template` → plantilla de variables de entorno

## Ejecución local
```bash
pip install -r requirements.txt
python main.py
```

## Despliegue en Railway (24/7)
1. Sube esta carpeta a un repo en **GitHub** (NO subas `.env` real).
2. Entra en [Railway](https://railway.app) → New Project → Deploy from GitHub Repo.
3. En **Variables**, pega los valores de `.env.template` con tus datos reales.
4. Start command: `python main.py`.
5. ¡Listo! El bot estará online 24/7.
