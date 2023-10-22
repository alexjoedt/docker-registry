# Docker-Registry

## Authentication

1. `sudo apt-get install apache2-utils`

2. `htpasswd -cB ./auth/htpasswd alex`

3. Create `.env`

4. Add `SECRET=`

5. Generate secret with `openssl rand -hex 64`

## NGINX

See the [offcial documentation](https://github.com/distribution/distribution/blob/main/docs/content/recipes/nginx.md) for details.
