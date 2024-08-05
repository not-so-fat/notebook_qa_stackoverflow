# Main function
- [ask question to get potential cause](./get_potential_causes.ipynb)
    - To execute this, you'll need Groq key and set it [in this file](./global.ipynb) and prepare Milvus database by following below
# Preparation
- [Crawl stackoverflow question with a specified tag](./stackoverflow_crawler.ipynb)
    - I now realized using [https://api.stackexchange.com/docs](https://api.stackexchange.com/docs) is better for this purpose, like https://github.com/not-so-fat/stackoverflow_crawler
- [Embed question & question title and create Milvus database](./create_stackoverflow_db.ipynb)
