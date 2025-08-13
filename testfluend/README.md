kubectl create configmap fluentd-config --from-file=fluent.conf=fluent.conf -n logging  ##use this command to create configmap or run config yaml file to create configmap which is in same location

references-
https://github.com/fluent/fluentd-kubernetes-daemonset/blob/master/docker-image/v1.17/debian-elasticsearch8/conf/fluent.conf

https://medium.com/@pradeep.kakarlapudi/setting-up-fluentd-in-kubernetes-for-elasticsearch-kibana-0945f142d310

https://github.com/fluent/fluentd-kubernetes-daemonset/blob/master/fluentd-daemonset-elasticsearch-rbac.yaml

https://github.com/pradeepkakarlapudi/fluentd-k8/blob/master/fluentd-daemonset-k8.yaml

https://github.com/fluent/fluentd-kubernetes-daemonset/tree/master


