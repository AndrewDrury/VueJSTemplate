## Instructions

```bash
npm install
npm run serve
```

Now go to http://localhost:8080/

## Deployment

Go into vue.config.js and uncomment this line:

```
  // publicPath: "././"
```

Now enter this into terminal in your root dir:

```bash
npm run build
```

This will generate a bunch of production-ready files in the ./dist folder.
To deploy to GitHub pages, grab those files and put them into their own repo (preferably USERNAME.github.io as it automatically sets up the environment).

Re-comment the line

```
  publicPath: "././"
```

when you want to test on localhost again.
