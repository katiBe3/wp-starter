Quick & simple WordPress plugin development server setup.

Works with VSCode & 🪟 **Windows**. Comes with Xdebug 3 and WP-CLI.🎁

**Preconditions:** Make sure to install [Lando](https://lando.dev/). Done? Let's go!👇

## Let's get started!🎈
1. Replace sample plugin **wp-starter** in `src\plugins` - or use it for a test ride.
1. Replace **project-name** in `lando.yml` (adjust more config ⚙️ if you like)
1. Replace **project-name** in `launch.json` for smooth debugging.
1. In the project root: run `lando start`
1. Download Wordpress: run `lando download-wordpress`...⌛
1. Check important infos about your app: `lando info`
Happy coding!🥳

## Useful commands 
- Stop containers & services with `lando stop`
- Changed `lando.yml`? Ran into problems? Rebuild containers 📦 with `lando rebuild`
- 💣 Destroy your containers with `lando destroy -y`

## 📖 Resources
- [Configure Lando for WordPress](https://docs.lando.dev/wordpress/config.html)
- [How to use Lando with VSCode](https://docs.lando.dev/guides/lando-with-vscode.html)
- [All Lando commands explained](https://docs.lando.dev/cli/config.html)
- [Great example of a more advanced Lando setup for Wordpress](https://github.com/timothyjensen/lando-wordpress)

PS: Yes, I'm still in love with [WordPress](https://wordpress.org/download/) after more than 12 years. Can't let go, haha! 🥰
