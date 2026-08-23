# Tu Homenaje

Sitio conmemorativo digital para honrar seres queridos

## Stack

- **Static HTML/CSS** — vanilla, sin dependencias externas
- **Nginx Alpine** — contenedor ligero (~5 MB)
- **Docker** — deploy con un solo comando

## Deploy

```bash
docker build -t tuhomenaje-web .
docker run -d -p 8080:80 --name tuhomenaje-web tuhomenaje-web
curl http://localhost:8080/health
```

## Repo

[github.com/luishueicha/tuhomenaje-web](https://github.com/luishueicha/tuhomenaje-web)
