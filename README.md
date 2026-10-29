# DREVOS dealer feeds

Public product feeds for dealers and catalog import tools.

**Stable URL:** https://mykhailo-vorona.github.io/drevos-dealer-feeds/

| Market | Currency | XML | JSON | Shopify CSV | WooCommerce CSV |
| --- | --- | --- | --- | --- | --- |
| Ukraine | UAH | [XML](https://mykhailo-vorona.github.io/drevos-dealer-feeds/ua/catalog.xml) | [JSON](https://mykhailo-vorona.github.io/drevos-dealer-feeds/ua/catalog.json) | [CSV](https://mykhailo-vorona.github.io/drevos-dealer-feeds/ua/shopify.csv) | [CSV](https://mykhailo-vorona.github.io/drevos-dealer-feeds/ua/woocommerce.csv) |
| Poland | PLN | [XML](https://mykhailo-vorona.github.io/drevos-dealer-feeds/pl/catalog.xml) | [JSON](https://mykhailo-vorona.github.io/drevos-dealer-feeds/pl/catalog.json) | [CSV](https://mykhailo-vorona.github.io/drevos-dealer-feeds/pl/shopify.csv) | [CSV](https://mykhailo-vorona.github.io/drevos-dealer-feeds/pl/woocommerce.csv) |
| Germany | EUR | [XML](https://mykhailo-vorona.github.io/drevos-dealer-feeds/de/catalog.xml) | [JSON](https://mykhailo-vorona.github.io/drevos-dealer-feeds/de/catalog.json) | [CSV](https://mykhailo-vorona.github.io/drevos-dealer-feeds/de/shopify.csv) | [CSV](https://mykhailo-vorona.github.io/drevos-dealer-feeds/de/woocommerce.csv) |

Feeds are generated daily at 03:20 UTC from the public DREVOS storefronts. GitHub scheduled jobs may start later during busy periods. JSON includes `generated_at` for freshness checks.

Prices are public retail prices in each market's currency. Products are made to order; stock quantities are intentionally omitted. Removed products remain marked `deleted`. Review changes before importing into a production store.

Only generated catalog files and this README are stored here. The generator, validation reports and Shopify theme source are maintained in a separate private repository. No credentials are required to download the feeds.

GitHub Pages publishes generated files from the root of `main` with its built-in deployment pipeline. A dedicated deploy key allows the private generator to update this repository without granting access to the theme repository.
