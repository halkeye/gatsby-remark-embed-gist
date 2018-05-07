# gatsby-remark-embed-gist
Embed a Github Gist in your Markdown


## Install 
1. Install plugin to your site:

```bash
yarn add gatsby-remark-embed-gist
```

2. Add following to your `gatsby-config.js`:
```js
    plugins: [
      {
        resolve: "gatsby-transformer-remark",
        options: {
          plugins: [{ resolve: "gatsby-remark-embed-gist" }]
        }
      },
```

``` js
plugins: [
  "gatsby-remark-embed-gist",
]
```

3. Restart gastby.

## Usage

```markdown
# Check out this code

`gist:https://gist.github.com/halkeye/f061872eb4b47dc0928e`

```

## License

MIT
