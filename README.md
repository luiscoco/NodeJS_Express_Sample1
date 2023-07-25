# NodeJS_Express_Sample1

## How to set your first Express application

1. First open VSCode and create an "index.js" file with this code

```javascript
var express = require('express');
var app = express();

app.get('/', function (req, res) { 
    res.send("Hello World from Express Luis!");
});

app.listen(3000);
```

2. Create a package.json file with this command:

```
npm init -y
```

3. Install the "Express" dependency typing this command:

```javascript
npm install express
```

4. Run the application with the following command:

```
node index.js
```

or

```
nodemon index.js
```

