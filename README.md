# Akademik Işler Boty — Render Deployment

## Render'e goýmak:

### Gadam 1: GitHub
```bash
git init
git add .
git commit -m "bot deploy"
git remote add origin https://github.com/username/repo.git
git push -u origin main
```

### Gadam 2: Render
1. render.com → New → Background Worker
2. GitHub repo-ny saýla
3. Environment Variables goş:

| Açar | Bahasy |
|------|--------|
| BOT_TOKEN | senin tokenin |
| DEEPSEEK_API_KEY | senin açaryň |

### Gadam 3: Deploy
Deploy basyň — bot işläp başlar!

## Faýllar:
- bot.py — esasy kod
- requirements.txt — Python 3.11 paketleri
- render.yaml — Render sazlamalary
- runtime.txt — Python wersiýasy
