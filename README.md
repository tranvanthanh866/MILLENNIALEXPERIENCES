## About app
- Build by html, css, js with bootstrap 4
## How to change style css

- Using nodejs
- install node and npm follow https://www.npmjs.com/get-npm
- After install less
```shell script
npm install -g less
```
- after change file .less run cmd bellow to generate file css
```shell script
lessc less/home.less css/home.css
lessc less/about-us.less css/about-us.css
lessc less/contact.less css/contact.css
```
- each file has been included 2 files: _reset.less and _common.less
    