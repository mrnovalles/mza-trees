# mza-trees
https://zucaritask.github.io/mza-trees/
> I am not a tree, I am an ent

Search for trees by specie using a [Datasette](https://github.com/simonw/datasette) application hosted on zeit.co.

This project is almost identical to https://github.com/simonw/sf-tree-search replacing San Francisco
with Mendoza, Argentina. It started as a simple test on how to use dattasette and became the same project as Simon's after he mentioned sf-tree-search existed.

## The looks
<img src="screenshot.png?raw=true" alt="Screenshot" width="720">

My contribution on top of [Simon's](https://github.com/simonw/) is minimal. Just to obtain the data and do a bit of parsing around until the data fitted the Javascript in this file. Big props to him for building all the parts included in this project. Datasette, csv-to-sql-lite and lastly the sf-tree-search project.

## Dataset
The dataset was obtained from https://ckan.ciudaddemendoza.gov.ar/dataset/arbolado-de-la-ciudad-de-mendoza
The complete dataset is available online and can be queried using SQL already on the browser url at:
https://datasette-kqxlerehng.now.sh/csv-data-70a5b6e?sql=select+*+from+arbolado

> For further explanations on how this can be replicated or how it's all done, please refer to https://github.com/simonw/sf-tree-search/blob/master/README.md
