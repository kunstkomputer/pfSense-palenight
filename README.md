forked from: [tyler-holm/pfSense-palenight](https://github.com/tyler-holm/pfSense-palenight)
Last updated for pfsense 2.7.0 

Later versions of pfsense are not officially support but will likely work fine.

# pfSense Palenight

View more [screenshots](screenshots) or checkout the [installation guide](#installation-guide).

<img src="screenshots/preview_main.png" alt="Dashboard preview" width="700">

## Installation Guide

1. Login to the web configurator
2. From the navigation menu select Diagnostics > Command Prompt
3. Download kunstkomputer-palenight.css and place it inside of /usr/local/www/css. This can be done manually **OR** by executing the following shell command

```
curl -s https://raw.githubusercontent.com/kunstkomputer/pfSense-palenight/main/install.php | php
```

4. From the navigation menu select System > General Setup
5. Change the theme to kunstkomputer-palenight and click save
6. Enjoy your new theme!
