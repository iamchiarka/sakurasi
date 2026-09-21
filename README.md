# sakurasi

Personal homepage for sakurasi.de. Built with [Astro](https://astro.build) + Tailwind CSS, deployed via Dokku (Dockerfile-based, like `taff`).

## Develop

```bash
npm install
npm run dev
```

## Check the production build locally

```bash
docker build -t sakurasi:local .
docker run --rm -p 8080:80 sakurasi:local
```

Then open http://localhost:8080.

## Deploy

```bash
git push dokku main
```
