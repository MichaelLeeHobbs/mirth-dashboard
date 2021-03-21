# mirth-dashboard
Mirth Connect Metabase Dashboard

## Tools
* https://pypi.org/project/metabase-import-export/

## Import?
* metabase-import-export-script.py --username "admin@localhost.local" --url http://localhost:8004/ import --collection-id 3 --import-file mirth_metabase.json
* collection must already exist

## Export
* metabase-import-export-script.py --username "admin@localhost.local" --url http://localhost:8004/ export --collection-id 3 --export-file mirth_metabase.json 
