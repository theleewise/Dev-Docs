## Install Theme

** Install the latest version from wordpress.org and activate **
`wp theme install twentysixteen --activate`

** Install from a local zip file **
`wp theme install PATH_TO_LOCAL_FILE`

** Install from a remote zip file **
`wp theme install URL_HERE`

## Flags

[--activate]
If set, the theme will be activated immediately after install.

[More](https://developer.wordpress.org/cli/commands/theme/install/)

## Install Plugins

`wp plugin install all-in-one-wp-migration --activate`

## Fix for Issues w/ Permissions

`chown [SERVER_USERNAME] wp-content/[DIRECTORY]`
      - upgrade
    - plugins
    - content

daemon

https://www.interserver.net/tips/kb/fix-uploaded-file-not-moved-wp-contentuploads/

## Virtual Hosts

https://www.thermalexposure.com/2014/02/25/set-up-your-own-local-domains-for-web-development-on-mac-osx/