#Just a quick reference on handy http server

##Python 2.7
    python -m SimpleHTTPServer [port]

##Python 3.5
    python -m http.server [port]

##Node.js
    npm install http-server -g
    http-server [path] [options]

    path defaults to ./public, else ./
-  -p           Port to use [8080]
-  -a           Address to use [0.0.0.0]
-  -d           Show directory listings [true]
-  -i           Display autoIndex [true]
-  --cors       Enable CORS via the "Access-Control-Allow-Origin" header


##Twisted (Preinstalled on OSX since 10.5)
    twistd -no web --path=.
