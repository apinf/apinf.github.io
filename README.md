apinf.github.io
===============

Website is powered by [Hugo](https://gohugo.io/).
At the moment we store Hugo related code in develop and generated site in master branch.

Temp solution, these steps you need to take now in order update the website.
Install [Hugo](https://gohugo.io/overview/quickstart/)

1. Clone this repo
2. Pull changes from develop
3. After you made changes run `hugo server`
4. After running `hugo server` for local web development, you need to do a final `hugo` run without the server part of the command to rebuild the site. You may then deploy the site by copying the public/ directory (by FTP, SFTP, SSH) to our production web server. Credentials can be obtained from @cssr.

Also it worth mentioning, that we store all content of the site in this [file](https://github.com/apinf/apinf.github.io/blob/develop/config.toml), so in order to change text/image, make those changes in this file.
 
