Gitlab (Git, Gitlab Runner oder jenkins) / Merge Requests - Gradle projekt
Gitflow & Rebase/Squash commits
Spring Boot
JUnit/Springtests (integrationstests) für die pipeline
Einbindung der Test in die gitlab/jenkins pipeline
Sonarqube und whitesource/trivy in die pipeline einbinden

=> Ziel bis hierhin ist eine Java Spring applikation mit Rest service anfragen zu ermöglichen und zu bauen.

Jetzt muss ein docker container erstellt werden, in welchem die nachfolgenden Komponenten hoch gezogen werden können. (kafka/cassandra/etc.)

Anbindung unerschiedlicher Persistenzframeworks:
Cassandra
MongoDB
Postgres/Oracle
Redis (caching)

=> Ziel ist jetzt eine DB anbindung zu haben.

Zweite Anwendung die parallel zur ersten laufen kann mit unterschiedlicher logik. Die miteinander sprechen möchten.
Confluent Kafka, Schemaregistry, RabbitMQ
Alternativ kann die Kommunikation über kafka auch in der gleichen anwendung stattfinden.

Zum Schluss müssen die docker files auch deployed werden in AWS:
Kubernetes ggf. mit Rancher
Helm charts

RDS
S3
Elastic Load Balancer
Service-Facade (Ingress) - DNS Proxy
Grafana + Prometheus (spring aviator)
Kibana + Elastic Search
Opensearch
Micronaut
Artifactory/Renovate (was ist das / was kann es)
