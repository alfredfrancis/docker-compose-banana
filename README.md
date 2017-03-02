# docker-compose for Banana Dashboards
Docker compose for starting banana dashboards

## Installation

Clone the repo

edit config.js & add your solr instance details for storing banana dashboards and metadata

add/edit dashboards in dashboards/ directory



```sh
docker-compose build
docker-compose up -d
```
for enabling cors, reffer to [Official banana Documentation](https://github.com/lucidworks/banana/tree/release/resources/enable-cors)
