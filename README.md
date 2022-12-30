# full-snacks-react

## Express
#### Definitions
1. expressjs.com
   - > ***"A fast, unopinionated, minimalist web framework for Node.js"***
2. wikipedia
   - > ***"is a back end web application framework for building RESTful APIs with Node.js, released as free and open-source software"***
Pretty much, it allows you to easily write a server in JS to handle clients requests.

#### Install Express
1. **Initialize a project and create a *package.json* file**
```
$ npm init
```
2. **Install Express package**
```
$ npm install express
```

#### Creating an Express application
```
const express = require('express');
const app = express();
```


#### Urls and URIs
###### If your server has the **domain name** of *http://www.thebestapi.com*, then:
- The **URL (Uniform Resource Locator)** is http://www.thebestapi.com
- And you handle any requests to **URIs (Uniform Resource Identifier)**
[The difference between URLs and URIs](https://danielmiessler.com/study/difference-between-uri-url/)
