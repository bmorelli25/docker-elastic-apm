# docker-elastic-apm
---

Get everything up and running:
```
docker-compose up
```

Add an agent to a locally running application, then visit:
```
// Elasticsearch
http://localhost:9200

// Kibana
http://localhost:5601
```

Note: `apm-server` listens on port `8200`.