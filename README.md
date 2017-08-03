To use the `src` folder in the local root directory of the site (instead of theme),

1) copy the src folder to your root,
2) run `rm -rf node_modules`
3) run `npm install` a
4) add the following to your config:

`js_path = "/static/dist/js"`
`css_path = "/static/dist/css"`

5) Make any changes to your styles or JS and run
`npm run build:production`
