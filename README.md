Easy peasy Wordpress development starter pack. 
Comes with XDebug and WP-CLI.🎁

Precondition: Make sure to install https://lando.dev/. Done? Let's go!👇

## Let's get started!🎈
1. Configure `.lando.yml` and insert your project name
1. In the project root: run `lando start` 
1. Change to WordPress installation folder: `cd wordpress` 
1. Download brandnew WordPress: `lando wp core download` 
1. Head over to `projectname.lndo.site/wordpress/` and finish the installation. 
1. Enter: Database name `wordpress`, username: `wordpress`, password: `wordpress`, host: `database`

## Useful commands 
- Changed `lando.yml`? Rebuild project 📦 with `lando rebuild`
- 💣 Destroy your app with `lando destroy -y`
