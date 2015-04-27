# Intro

Life-Index is a personal search engine based on [Norch](https://github.com/fergiemcdowall/norch) and [Search-index](https://github.com/fergiemcdowall/search-index), making my digital life searchable. Proof of concept.

Life-Index is a forked version of [Norch-bootstrap](https://github.com/fergiemcdowall/norch-bootstrap). It uses [iftt-norch-tools](https://github.com/eklem/iftt-norch-tools) for document processing and [Life-Indexer](https://github.com/eklem/life-indexer) for indexing.

The data comes from several IFTTT IF-recipes, storing it in several Google Drive Spreadsheets. Life-Indexer pulls this information from Google Drive and index it.

# Setup
## IFTTT IF-recipes
Activate the recipes you want to make searchable
* [Starred email in Gmail](https://ifttt.com/recipes/283693-lifeindex-searchable-gmail)
* [Your Twitter tweets](https://ifttt.com/recipes/283696-lifeindex-searchable-tweets)
* [Flickr uploads](https://ifttt.com/recipes/283697-lifeindex-searchable-flickr-uploads)

![Life-index - An example on personal searh](https://cloud.githubusercontent.com/assets/236656/7343405/8e55cf8a-ecc1-11e4-9906-a410ea108cbf.png)
