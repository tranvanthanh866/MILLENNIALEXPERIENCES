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
lessc less/app.less css/app.css
lessc less/home.less css/home.css
lessc less/about-us.less css/about-us.css
lessc less/contact.less css/contact.css
lessc less/contact-form.less css/contact-form.css
lessc less/blog.less css/blog.css
lessc less/faq.less css/faq.css
lessc less/post-detail.less css/post-detail.css

```
- each file has been included 2 files: _reset.less and _common.less
    