# JBang Camel Kubernetes Examples

Here you find a set of Camel Kubernetes projects generated with [jbang camel kubernetes](https://camel.apache.org/manual/camel-jbang-kubernetes.html).

These projects are organized by their respective runtime option.

* [main](./camel-main)
* [quarkus](./quarkus)
* [spring-boot](./spring-boot)

For convenience, you'll find a Makefile in each subdir. You could inspect/try ...

```
make package

make run-java
make run-docker

make k8s-export
make k8s-deploy
make k8s-delete
```