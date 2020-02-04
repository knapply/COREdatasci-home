[![Netlify Status](https://api.netlify.com/api/v1/badges/2c413c6f-9898-4e99-8fcd-ae20d76366ad/deploy-status)](https://app.netlify.com/sites/coredatasci/deploys)
[![Build Status](https://travis-ci.com/knapply/COREdatasci-home.svg?branch=master)](https://travis-ci.com/knapply/COREdatasci-home)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-orange.svg)](https://creativecommons.org/licenses/by/4.0/)

# COREdatasci-home

Repository that produces the COREdatasci website. Uses Hugo with the Academic theme, wrapped by blogdown, and hosted by netlify. 

## Workflow

This repository is hooked up to Travis CI and Netlify. All you need to do is push a change to the `master` branch, and the site will automatically render and deploy.

Wondering where the `.html` files are? They've been `.gitignore`d, and produced by Travis/Netlify.

## Noteworthy Directory Structure

### `/content`

This is where the content of the website lives. Hugo/blogdown renders this to the `public` folder, which you don't need to touch.

### `config.toml` and `/config`

Website parameters used by Hugo are set in these `toml` files. Check out 

### `/static`

Static stuff like pictures that the site draws on.



