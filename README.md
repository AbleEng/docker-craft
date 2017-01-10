# Docker for Craft CMS

An Nginx/php container suitable for Craft CMS taken nearly verbatim from Chris Fidao's excellent Shipping Docker course.

The instructions below are for the Able development team. This repo remains public in the spirit of sharing.

## Build

After making changes, rebuild the image with the `latest` tag.

```bash
docker build -f Dockerfile -t ablelending/craftcms-nginx-php:latest ./
```

## Push to Docker Hub

After rebuilding the image, be sure to push it to Docker Hub.

```bash
docker push ablelending/craftcms-nginx-php
```

## License

[MIT License](/LICENSE).
