# WikiUtils
A set of utility scripts to process Wikipedia related data, forked from @napsternxg


## parse\_mysqldump

A script for parsing wikipedia mysqldump `sql.gz` files. Can be extended to parse arbitraty mysqldump files. 

```
usage: parse_mysqldump.py [-h] [--column-indexes COLUMN_INDEXES]
                          filename filetype outputfile

positional arguments:
  filename              name of the wikipedia sql.gz file.
  filetype              following filetypes are supported: [categorylinks,
                        pagelinks, redirect, category, page_props, page, templatelinks]
  outputfile            name of the output file

optional arguments:
  -h, --help            show this help message and exit
  --column-indexes COLUMN_INDEXES, -c COLUMN_INDEXES
                        column indexes to use in output file
```


## Information about the dumpfiles available from Wikimedia

Can be found here https://www.mediawiki.org/wiki/Manual:Database_layout 
