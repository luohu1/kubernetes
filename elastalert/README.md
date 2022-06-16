# elastalert

```shell
$ kubectl context set-context --current --namespace default

$ kubectl apply -f manifests/elasticsearch.yaml
$ kubectl apply -f manifests/kibana.yaml

$ kubectl port-forward -n default svc/elasticsearch 9200:9200
$ kubectl port-forward -n default svc/kibana 5601:5601
```

## 参考链接

- https://www.elastic.co/guide/en/elasticsearch/reference/7.7/docker.html
- https://www.elastic.co/guide/en/elasticsearch/reference/master/docker.html
- https://github.com/elastic/elasticsearch/blob/7.5/distribution/docker/src/docker/Dockerfile
- https://github.com/elastic/elasticsearch/blob/7.5/docs/reference/setup/install/docker-compose.yml
