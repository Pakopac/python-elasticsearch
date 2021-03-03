# python-elasticsearch

## Clone the repo
```
git@github.com:Pakopac/python-elasticsearch.git
cd python-elasticsearch
```

## Run docker
```
docker-compose up -d
```

## Check if running

### Elasticsearch
```
curl localhost:9200
```

### Kibana
http://localhost:5601

## Import datas
when all is running:
```
cd data/
sh bulk.sh
```

## Check the notebook python_API_example.ipynb :smiley: