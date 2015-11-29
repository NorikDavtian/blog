# My Personal Blog
Personal blog based on Hexo.. Feel free to fork and contribute.

``` bash
$ git clone git@github.com:NorikDavtian/blog.git && cd blog
$ npm install hexo-cli -g
$ npm install
```
That should get you setup.. More info here: https://hexo.io/

## To run the blog
I created a few shortcuts to run the blog with ease.

### Run with Nodemon
```bash
$ nodemon
```
which will run: 

```bash
$ hexo server
```
#### Run in **debug** mode
```bash
$ nodemon --debug
```

### NPM run shortcuts
Available options you can run with NPM: `npm run (admin|generate|deploy|watch|clean)`
```js
    "admin": "hexo server -d",
    "generate": "hexo generate",
    "predeploy": "hexo clean",
    "deploy": "hexo generate -d",
    "watch": "hexo generate -w",
    "clean": "hexo clean"
```
*example:*
``` bash
$ npm run deploy
```

## Make it yours
Change the `_config.yml` file in project root
Change the menu items from `source/_data/menu.yml` file

## Credits
 - Theme Modified from [Apollo](https://github.com/pinggod/hexo-theme-apollo)
 - Powered by [HEXO.io](https://hexo.io)

## License
  - Project files: MIT
  - Blog Posts and Content: Creative Common with Attribution
