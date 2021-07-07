don't directly use it, but use `docker-slim` to create a smaller image.

`docker-slim build --copy-meta-artifacts . --include-path=/app/carbon/.next --include-path=/app/carbon/public --include-path=/app/carbon/node_modules/next/dist yuuuxt/carbon:4.8.1`

ref:

https://github.com/docker-slim/docker-slim/issues/211