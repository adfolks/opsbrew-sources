# Monitor your entire Kubernetes cluster with Ops_brew

We are using filebeat to run as Daemonset in your K8s cluster. 
Apply the filebeat.yaml file using below command after changing the example IP to logstash in filebeat.yaml
`kubectl apply -f filebeat.yaml`

