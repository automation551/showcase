# Showcase #
Showcase is a simple Portfolio/Resume application for your professional web presence.
Present your resume and projects in a nice and easy way on the web.
The application is based on Sinatra and uses YAML files as data store.

## Features ##
- support for resume, contact details and project-portfolio
- multi language support
- easy configuration over YAML files for data storage
- edit your resume using markdown
- page caching in production

See a demo at http://resume.niwos.com

## Installation ##
### clone the showcase git project ###

`git clone git://github.com/niwo/showcase.git`

### install the dependencies with bundler ###

`cd showcase`

`bundle install`

### copy the sample config file ###
`cp config/config.example.yml config/config.yml`

### let's start the show ###

`bundle exec rackup`

## Fill in data ##

copy all data example files to the personal folder and adapt them to your needs  `cp -r data/example data/personal`

### Pictures ###
Add your personal picture under __public/pictures/personal/__ and projects pictures under __public/pictures/projects/__
