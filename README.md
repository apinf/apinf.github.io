apinf.github.io
===============

Website is powered by [Hugo](https://gohugo.io/).
At the moment we store Hugo related code in develop and generated site in master branch.

This is a temporary solution (see this [issue](https://github.com/apinf/apinf.github.io/issues/8)), these steps you need to take in order update the website.

1. Install [Hugo](https://gohugo.io/overview/quickstart/)
2. Clone this repo
3. Pull changes from develop
4. After you made changes run `hugo server`
5. After running `hugo server` for local web development, you need to do a final `hugo` run without the server part of the command to rebuild the site. You may then deploy the site by copying the public/ directory (by FTP, SFTP, SSH) to our production web server.

Also it worth mentioning, that we store all content of the site in this [file](https://github.com/apinf/apinf.github.io/blob/develop/config.toml), so in order to change text/image, make those changes in this file.
 
