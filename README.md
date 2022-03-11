# Hugo Bookshop Starter

A starter template for a new Hugo site using [Bookshop](https://github.com/CloudCannon/bookshop)

To run locally:
```bash
hugo server -D
```

To see the component browser locally:
```bash
npm i
npx @bookshop/browser
```
You can now load `/components` on your site and see the component library.

If building on CloudCannon, this page will also show a hosted version of the component library.

## Structure
The bookshop components live in `component-library`, which is loaded as a Hugo module in `config.toml`.

The site also pulls in the main dependency of `github.com/cloudcannon/bookshop/hugo/v2`.

For further help with Bookshop, see the [Bookshop Guides](https://github.com/CloudCannon/bookshop).
