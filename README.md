# prisma-airs-vertex-chat

## Run with Docker - ARM64 (If you re using MAC)

```bash
docker pull --platform linux/amd64 ghcr.io/chinthakaek/prisma-vertex-gateway:latest
docker run --platform linux/amd64 --rm -p 8000:8000 ghcr.io/chinthakaek/prisma-vertex-gateway:latest
```

## Run with Docker - Intel/AMD (x86_64)

```bash
docker pull ghcr.io/chinthakaek/prisma-vertex-gateway:latest
docker run --rm -p 8000:8000 ghcr.io/chinthakaek/prisma-vertex-gateway:latest
```

Access the UI with below
```bash
http://localhost:8000
```

<img width="1577" height="906" alt="image" src="https://github.com/user-attachments/assets/936dd64c-a0e6-43bd-9bf4-8613c9951e32" />
