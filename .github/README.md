# Color-Chan.Wiki

The repository for the official [Color-Chan Wiki](https://wiki.colorchan.com), containing all the guides and documentation related to Color-Chan.

## Local development

The wiki is built with [Zensical](https://zensical.org/). To preview it locally, run it with Docker Compose:

```bash
docker compose up -d
```

The site is served at <http://127.0.0.1:7562> and reloads automatically when files change. Check the build output with `docker logs color-chan-wiki`, and stop the server with `docker compose down`.
