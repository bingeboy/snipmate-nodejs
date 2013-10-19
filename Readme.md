# Vim Snippets for Node.js

Here be various snippets for use with Vim SnipMate to make node.js development quicker and easier.
You'll need snipmate installed.

This fork's goals layers many updated node core api along witha few popular npm's.

##Additions In This Fork
* REPL
* streams
* timers
* Cluster
* Crypto
* OS
* Timers
* Query Strings
* Path
* bcrypt
* File System
* Process


#How to Install For Snipmate
Recommend downloading files to ```~/.vim/bundle/``` then symbolic linking to ```~/.vim/snippets/```

```
cd ~/.vim/bundle/
git submodule add https://github.com/bingeboy/snipmate-nodejs.git
ln -s ~/.vim/bundle/javascript ~/.vim/snippets/
```

## Examples
```
fs.readFile
fs.writeFile
reqsys
reqhttp
```
