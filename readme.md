# Examples of .gitignore configurations

## First configuration

```
# -------------------------
# BEGIN .gitignore Files
# -------------------------

###################
# Compiled source #
###################
*.com
*.class
*.dll
*.exe
*.o
*.so

# Packages #
############
# it's better to unpack these files and commit the raw source
# git has its own built in compression methods
*.7z
*.dmg
*.gz
*.iso
*.jar
*.rar
*.tar
*.zip

# Logs and databases #
######################
*.log
*.sql
*.sqlite

# OS generated files #
######################
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db

# Ignore node/grunt dependency directories
node_modules/

# Ignore composer vendor directory
/vendor

# Ignore components loaded via Bower
/bower_components

# Ignore public / dist directory
/dist
/public

# Ignore Editor files
*.sublime-project
*.sublime-workspace
*.komodoproject
.vscode/*

# -------------------------
# BEGIN Whitelisted Files
# -------------------------

# Track these files, if they exist
!.gitignore
!.editorconfig
!.babelrc
!.phpcs.xml.dist

```
