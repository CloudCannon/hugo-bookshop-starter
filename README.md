# Hugo Bookshop Starter

A starter template for a new Hugo site using [Bookshop](https://github.com/CloudCannon/bookshop)

Implemented:
- [x] Component syntax
- [x] SCSS pipeline

Upcoming:
- [ ] CloudCannon structures generation
- [ ] Local component browser
- [ ] Live editing

To run locally:
```bash
cd site && hugo server -D
```

## Structure
The bookshop components live in `component-library`, which is loaded as a Hugo module in `site/config.toml`.

The site also pulls in the main dependency of `github.com/cloudcannon/bookshop/hugo/v2`.

For further help with Bookshop, see the [Bookshop Guides](https://github.com/CloudCannon/bookshop).