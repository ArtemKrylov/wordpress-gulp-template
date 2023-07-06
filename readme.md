Gulp for WordPress template

To work with this startup template, you need `Gulp`, any `local server`,  and the `CMS WordPress`!

## A list of tasks and assign


* **browser-sync** - Auto-update of your page
* **sass** - Compiles all SASS files in your project into a single CSS file
* **js** - Collects and compresses all your JS files into one large file
* **watch** - Keeps track of changes in all files of your website template to auto-update and show you the changes
* **imgmin-theme** - Compresses all images to the best state in your template
* **imgmin-uploads** - Compresses all images in the uploads folder to the best state
* **deploy-site** - Sends all your website to web hosting via FTP
* **deploy-theme** - Sends your ready-made website template to web hosting via FTP
* **rsync** - Sends a ready-made website template or a full website for hosting via SSH


## Call/use Task

```
$ gulp imgmin-theme
$ gulp imgmin-uploads
$ gulp deploy-site
$ gulp deploy-theme
$ gulp rsync
```
