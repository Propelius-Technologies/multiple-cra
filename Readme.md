### Prerequisites

- node 16.x.x
- yarn

```bash
# Build apps
- yarn build-all
```

### Add script relative paths of the apps

```html
<!-- at the end of body tag -->
<script src="<relative path to apps chunk js files>"></script>
<script src="<relative path to apps main js files>"></script>
```

For example if path to client1's static files is
`./client1/build/static/js/[something]chunk.js` & `./client1/build/static/js/main.[something].js`, add them to script src.


### Add css relative paths of the apps

```html
<!-- in the head tag -->
<link rel="stylesheet" href="<relative path to apps main css files>" />
```

For example if path to client1's static files is
`./client1/build/static/css/main.[something].css`, add them to script src.


### Running the app

open/serve index.js file in a browser
