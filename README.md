# qrank

Wikidata hosts the [QRank dataset](https://github.com/brawer/wikidata-qrank), which scores Wikidata items by popularity. This can be useful for ranking Wikipedia pages or OpenStreetMap entities.

They publish the dataset as a gzipped CSV file, [qrank.csv.gz](https://qrank.wmcloud.org/download/qrank.csv.gz).

This repository republishes the data as a SQLite database with an index, so that random-access queries are fast.

You can download [qrank.db here](https://github.com/hikeratlas/qrank/releases/download/latest/qrank.db).
