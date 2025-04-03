this repo contains all the Homebrew casks and formulae that i install on my macbook for my development environment, along with global npm packages.

prerequisites:
- install [homebrew](https://brew.sh/)

to install formulae: `xargs brew install < brew-formulae.txt`
to install casks: `xargs brew install --cask < brew-casks.txt`
to install global npm packages: `xargs npm install -g < npm-global.txt`
