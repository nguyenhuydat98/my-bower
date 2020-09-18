## How to setup bower in project

Requirements: nodejs, npm

npm install -g bower

bower init

Create .bowerrc and add {"directory" : "public/bower_components/"}

Add to gitignore: /public/bower_components

bower install (package)
  
bower uninstall (package)

## How to create a bower in your github

Create new a repository (Example: my-bower) add README.md (content random)

git clone (link http to repo)

Copy package to folder (my-bower)

push to git

Open Terminal to my-bower

bower install (link http to repo)

DONE
