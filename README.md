# elasticstack-commands 7.x
Comandos avançados de todos os componentes do ElasticSearch

## Status infraestrutura

## Index

## Template
```
Criação do template:
PUT _template/nome-template
{
  "template": "nome-template-*",
  "settings": {
    "number_of_shards":   5,
    "number_of_replicas": 1,
    "routing.allocation.include.box_type": "hot",
    "routing.allocation.total_shards_per_node": 2
  },
  "aliases": {
    "search-logs": {}
  }
}
```

## Logstash

## Curator


