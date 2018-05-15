# example reproducing issue of akka-persistence-redis plugin with cluster-mode

## how to reproduce

```bash
docker-compose -f docker-compose.yml up --build
```

## references and credits
* using [Grokzen/docker-redis-cluster](https://github.com/Grokzen/docker-redis-cluster) docker-image
* akka sample code based on official [akka-sample-persistence-java](https://github.com/akka/akka-samples)
