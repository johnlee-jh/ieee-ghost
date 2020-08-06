# Liebling-IEEE

## How to Install Ghost for Development
1. Download NodeJS
2. Verify that you have NodeJS by running `npm --version`
3. Run `sudo npm install -g ghost-cli@latest`. This installs the latest version of the ghost-cli. **NOTE** You must run this with `sudo`. If you are using Windows, you can install this by running an elevated command prompt and running `npm install -g ghost-cli@latest`.
4. Verify that you have Ghost installed by running `ghost --version`
5. Create an empty directory (this is where the ghost development environment will be) and `cd` into it
6. Run `ghost install local --no-start` and check to see whether or not the folder is populated with files
7. Navigate to `your_ghost_folder->content->themes`
8. While inside of the themes folder, clone this repo.
9. Exit back to `your_ghost_folder` and then run `ghost start --development`
10. Go to the specified admin console link (it should be a localhost). Make an account and login.
11. Go to Design under Settings and scroll down to see where the themes are. Activate the `liebling-ieee` theme.
12. Modifications to the theme will change the page. **Before adding your own changes, make a new branch!**

## How to Modify the Theme
When you modify a file within your current theme, you will have to reload the page to see your changes. For help on actual development, see [https://ghost.org/docs/api/v3/handlebars-themes/](https://ghost.org/docs/api/v3/handlebars-themes/).

**IMPORTANT: From now on, this theme is only compatible with Ghost 3+**

## Features

### General features

* Clean and beautiful design 💅🏼
* Lightning fast ⚡️
* Fully responsive, looks great on any device 📱
* Compatible with modern browsers 💻
* Fast support 📞

### Ghost features

* Subscription form [more info here](https://github.com/eddiesigner/liebling/wiki/How-to-enable-subscribers)
* Multiple authors
* Logo support
* Featured posts and pages
* Post, Page, Tag, Authors, pages
* Koenig editor
* Bookmark card
* Gallery card
* Blog title and description
* Cover image for Home, Post, Page, Tag, Author pages
* Author avatar, bio, location, website and social links
* Facebook and Twitter social links
* Reading time
* Next and Previous post navigation
* Primary tag in posts

### Liebling unique features

* Dark mode
* Search
* Custom Subscribe page
* Custom authors page
* Custom error page
* Medium style image zoom
* Comments with Disqus
* Share post on Facebook and Twitter
* Slider for featured posts
* Support for normal, wide and full images in posts
* Reading progress indicator
* RTL language support

## Localization

* English
* Spanish
* German by [D3473R](https://github.com/D3473R)
* Informal german by [D3473R](https://github.com/D3473R)
* Bulgarian by [clappingmonkey](https://github.com/clappingmonkey)
* Vietnamese by [hiensarahly](https://github.com/hiensarahly)
* Italian by [vignini](https://github.com/vignini)
* French by [v1nc3nt-fr](https://github.com/v1nc3nt-fr)
* Informal french by [v1nc3nt-fr](https://github.com/v1nc3nt-fr)
* Portuguese by [ivomota](https://github.com/ivomota)
* Arabic by [allamiro](https://github.com/allamiro)
* Polish by [otlet](https://github.com/otlet)
* Brazilian portuguese by [pedrinholula](https://github.com/pedrinholula)
* Russian by [stereohorse](https://github.com/stereohorse)
* Kyrgyz by [januchaos](https://github.com/januchaos)
* Hebrew by [cohen604](https://github.com/cohen604)
* Turkish by [mskoroglu](https://github.com/mskoroglu)
* Romanian by [dsecareanu](https://github.com/dsecareanu)
* Chinese Simplified by [IvyB](https://github.com/IvyB)
* Indonesian by [iqbalbinsb](https://github.com/iqbalbinsb)
* Lithuanian by [pintom](https://github.com/pintom)
* Dutch by [Qballjos](https://github.com/Qballjos)

## Tests performed

* W3C Markup Validation: [Correct validation](https://validator.w3.org/nu/?doc=https%3A%2F%2Fliebling.eduardogomez.io%2F)
* Ghost GScan: [100/100 points](https://gscan.ghost.org/)
* GTmetrix PageSpeed Score: **A (97%)**
* PageSpeed Insights: **94/100** (mobile) **99/100** (desktop)
* Pingdom Performance Grade: **A 91**

## Theme development

Thanks to [D3473R](https://github.com/D3473R) 💪🏼 for creating a development environment with Docker. From now on you can work on this theme without installing a Ghost instance on your local machine. With two commands you have an instant development setup and you can build the theme for production.

Please take a look to this page to see how it works: https://github.com/eddiesigner/liebling/wiki/Theme-development-with-Docker

## Help and Support

To know how to enable the search, comments, subscribers and more, please head to the [Wiki](https://github.com/eddiesigner/liebling/wiki).

If you have any questions or troubles with this product, please feel free to open an issue [here](https://github.com/eddiesigner/liebling/issues).

## Related

* [Weiss Pro](https://blog.eduardogomez.io/weiss-pro-modern-and-clean-ghost-theme/) - Modern and beautiful Ghost theme ready to make your content shine ✨

## License

Copyright (c) 2019-2020 Eduardo Gómez. Released under the [MIT license](https://github.com/eddiesigner/liebling/blob/master/LICENSE).

## Credits

All the photos I used in this theme were taken from [Unsplash](https://unsplash.com)
