## Nexjs with Docker

The story is availabel on [Medium](https://menaiala.medium.com/how-to-dockerize-and-deploy-your-next-js-14-the-ultimate-guideline-for-beginners-6905df28484c).

Run these commands:

### Development

```bash
docker compose -f docker-compose.dev.yml up --build --force-recreate
```

### Build

```bash
docker build -t my-app:prod -f Dockerfile.prod .
```

