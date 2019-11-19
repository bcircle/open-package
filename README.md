## Package

### OCR Service

1. Login

```bash
docker login docker.pkg.github.com --username wk-j
```

2. Create `docker-compose.yml`

```yml
version: "3"

services:
  ocr-service:
    image: docker.pkg.github.com/bcircle/open-package/ocr-service:0.1
    ports:
      - 3000:3000
```

3. Execute 

```bash
docker-compose up
```
