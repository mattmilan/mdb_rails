## Purpose
This repo contains a default skeleton rails app with the minimum additions required to present a functional DEV environment for the style/functional demonstration included with the mdb-ui-kit package.

Ensure both puma and ./bin/webpack-dev-server are running.

The demo will display at the root url. 

## Getting Started
The repo can be cloned or an existing rails app modified as follows
#### From the console
- yarn add jquery @popperjs/core mdb-ui-kit

#### Then browse this repo's diffs for
- app/assets/stylesheets/application.scss (formerly application.css)
- app/javascript/packs/application.js
- app/javascript/packs/mdb-ui-kit.js
- app/views/application.html.erb
- config/webpacker.yml


### Versions
[Rails - 6.1.4.1](https://rubyonrails.org/)  |
[Webpacker - 5.0](https://github.com/rails/webpacker)  |
[MDB-UI-KIT - 3.9.0](https://mdbootstrap.com/)
