# OBP Product ID import

Take a CSV file containing a mapping of custom IDs nad DOIs and submit new findings to the identifier translation service.

## Run via crontab
```
0 13,21 * * * docker run --rm --name "productid_importer" --env-file /path/to/config.env openbookpublishers/obp_product_import
```
