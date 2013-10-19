# Vim Snippets for Node.js

Here is a updated fork of Vim Nodejs Snippets. Focuses on the core api and also handles common NPMs (TODO: List NPM).
You'll need snipmate installed.

###Supporting v.0.10.2X

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
* ReadLine (partial)

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
