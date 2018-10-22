# OBP Product ID import

Take a CSV file containing title and URIs associated to a DOI and submit new findings to the identifier translation service.

## Run via crontab
```
0 13,21 * * * docker run --rm --name "book_importer" --env-file /path/to/config.env openbookpublishers/obp_product_import
```
