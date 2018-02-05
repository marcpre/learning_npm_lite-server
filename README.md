# learning_npm_lite-server

This server should ONLY be used for development.

##Install

1. 

`npm install lite-server --save-dev`

2. 

Add this to your `script {` section:

```Inside package.json...
  "scripts": {    
    "dev": "lite-server"
  },```

3. 

Add a `bs-config.json` and add the following configuration:

```
{
  "port": 8000,
  "files": ["./src/**/*.{html,htm,css,js}"],
  "server": { "baseDir": "./src" }
}
```

[Github lite-server](https://github.com/johnpapa/lite-server)
