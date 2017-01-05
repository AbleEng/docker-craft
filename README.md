# Docker for Craft CMS

An Nginx/php container suitable for Craft CMS taken nearly verbatim from Chris Fidao's excellent Shipping Docker course.

Build

```bash
docker build -f Dockerfile -t ablelending/craftcms:latest ./
```

Push to docker hub

```bash
docker push ablelending/craftcms
```
