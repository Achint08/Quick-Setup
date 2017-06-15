# Quick Setup on Linux(Only for Debian based systems) and Mac

This script helps people set up their Terminal for development.

Packages it installs:
- git
- Homebrew (Mac only)
- Heroku Toolbelt
- pip/Django/Flask
- rbenv/rvm/Rails
- Postgres
- MySQL

# How to run the setup

Assuming user doesn't have git installed already, download and unzip: https://github.com/Achint08/Quick_Setup/archive/master.zip

From terminal, move to the folder just unzipped and then from the Terminal, run `sudo setup.sh`

**Important**: It is essential that you run this script with sudo privileges. In other words `sudo ./setup.sh` and not just `./setup.sh`.

# Known Issues

- Rails might take a long to install. So please be patient.
- If at any time the script hangs, press Ctrl C and it should move on to the next item to install.

# Contributions, Bug Reports, Feature Requests

I would be happy to see contributors who report bugs and file feature requests submitting pull requests as well.

Happy Open Source! :)