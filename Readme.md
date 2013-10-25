# Vim Snippets for Node.js

Here is a updated fork of Vim Nodejs Snippets. Focuses on the core api and also handles common NPMs.
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
* StringDecoder
* Plus More +++

###Full Snippet List
* addLis.snippet
* app.post.snippet
* app.snippets
* assert.notE.snippet
* assertdeep.snippet
* asserteq.snippet
* bcrypt.snippets
* cluster.snippets
* colors.snippets
* crypto.snippets
* env.snippet
* express.snippet
* filt.snippet
* foreEach.snippet
* fs.snippets
* func.snippet
* http.snippets
* javascript.snippets
* json.pa.snippet
* json.st.snippet
* log.snippet
* mongoose.snippets
* net.createServer.snippet
* on.snippet
* os.snippets
* path.snippets
* pipe.snippets
* process.snippet
* querystrings.snippets
* readline.snippets
* relp.snippets
* req.snippet
* reqfs.snippet
* reqhttp.snippet
* reqio.snippet
* reqmongoose.snippet
* reqpath.snippet
* reqstream.snippet
* reqvows.snippet
* res.render.snippet
* setinterv.snippet
* settime.snippet
* sys.snippets
* timers.snippets
* websocket.snippet
* writeHead.snippet




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
