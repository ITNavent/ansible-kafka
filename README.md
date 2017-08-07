# Kafka

Rol para instalar Apache Kafka.

Requiere los siguientes roles:
```
- src: https://tecnologianavent:********@github.com/ITNavent/ansible-java.git
  version: check-java
  name: java

- src: https://tecnologianavent:********@github.com/ITNavent/ansible-navent-folders.git
  version: v1.0.0
  name: folders

- src: https://tecnologianavent:********@github.com/ITNavent/ansible-zookeeper.git
  version: v1.0.0
  name: zookeeper
```

Es necesario especificar el nombre del cluster (en el caso de maquinas de openstack, la metadata)
```
zookeeper_cluster_name: kafka
```