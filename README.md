Easy peasy WordPress development environment starter pack.
Comes with XDebug and WP-CLI.🎁

**Preconditions:** Works with VSCode & Windows. Make sure to install https://lando.dev/. Done? Let's go!👇

## Let's get started!🎈
1. Configure `.lando.yml` and insert your project name
1. In the project root: run `lando start`
1. Install Wordpress: run `lando install-wordpress`...⌛

## Useful commands 
- Stop containers & services with `lando stop`
- Changed `lando.yml`? Rebuild containers 📦 with `lando rebuild`
- 💣 Destroy your containers with `lando destroy -y`