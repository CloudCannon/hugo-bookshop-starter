# Hugo Bookshop Starter

A starter template for a new Hugo site using [Bookshop](https://github.com/CloudCannon/bookshop)

To run locally:
```bash
cd bookshop-starter-site && hugo server -D
```

To generate the component browser:
```bash
npm run bookshop-browser
```
This will create browser files in the site's static directory. Running a Hugo build after this will show a live component browser at `/components` 

## Structure
The bookshop components live in `component-library`, which is loaded as a Hugo module in `site/config.toml`.

The site also pulls in the main dependency of `github.com/cloudcannon/bookshop/hugo/v2`.

For further help with Bookshop, see the [Bookshop Guides](https://github.com/CloudCannon/bookshop).
