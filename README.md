# Linkcare Home Page

Home page of Link Care

### Setup for the first time

sudo gem install -n /usr/local/bin jekyll webrick bundler --no-document
alias jk='jekyll'

### Create the project

# to project mother folder
cd 

git clone https://github.com/gambaldia/linkcare_home.git

PROJ='linkcare_home'
jekyll new $PROJ --force
cd $PROJ
vi Gemfile
gem 'webrick'
gem "jekyll-agency"

mkdir _data
mkdir _includes
mkdir _layouts
mkdir _sass
mkdir assets
mkdir assets/images
mkdir assets/pdf

### Install from GitHub

PROJ='linkcare_home'
git clone https://github.com/gambaldia/linkcare_home.git



