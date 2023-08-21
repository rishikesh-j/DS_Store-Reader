# DS_Store-Reader
An update to lijiejie/ds_store_exp 

A **`.DS_Store`** file disclosure exploit. 

It parses .DS_Store file and reads files recursively.

    Usage: python DS_Store-Reader.py https://example.com/.DS_Store

## Install ##

	pip install ds-store requests

## Example ##

	ds_store_exp.py http://example.com/.DS_Store

	[200] https://example.com/.DS_Store
	[200] https://example.com/ExampleSchema.json
