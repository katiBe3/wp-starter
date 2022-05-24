Easy peasy WordPress development environment starter pack.
Comes with XDebug and WP-CLI.🎁

**Preconditions:** Works with VSCode & Windows. Make sure to install https://lando.dev/. Done? Let's go!👇

## Let's get started!🎈
1. Configure `.lando.yml` and insert your project name
1. In the project root: run `lando start` 
1. Change to WordPress installation folder: `cd wordpress` 
1. Download brandnew WordPress: `lando wp core download` 
1. Head over to `projectname.lndo.site/wordpress/` and finish the installation. 
1. Enter: Database name `wordpress`, username: `wordpress`, password: `wordpress`, host: `database`

## Useful commands 
- Stop your containers & services with `lando stop`
- Changed `lando.yml`? Rebuild containers 📦 with `lando rebuild`
- 💣 Destroy your containers with `lando destroy -y`
