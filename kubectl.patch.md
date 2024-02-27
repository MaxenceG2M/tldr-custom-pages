- Port forwarding

`kubectl port-forward {{pod_name}} {{dest_port}}:{{pod_port}}`

- Add/update a label on a resource - force update

`kubectl label namespace my-ns-dev istio-injection=enabled --overwrite`
