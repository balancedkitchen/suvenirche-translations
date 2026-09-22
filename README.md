# Suvenirche Translations

Public translation catalogs for the Suvenirche WordPress plugins. This repository contains **only UI translations**, never plugin source, API keys, customer addresses, or credentials.

The Suvenirche Translation Manager reads [manifest.json](manifest.json) and downloads the locale catalogs listed there. Adding a new language requires only a new `<locale>.json` catalog and a matching manifest entry; existing WordPress plugins do not need to be replaced.

Each catalog is a JSON object with `version` and `domains`; the domains currently supported are `suvenirche-cj-routing` and `commerce-address-registry`. Keep English source-message keys and printf placeholders unchanged.

Source project: private `balancedkitchen/suvenirche`.
