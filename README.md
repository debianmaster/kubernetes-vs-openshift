### WIP
| Feature        | Kubernetes           | Openshift  |  Details |
| -------------  |:-------------:       | ----------:|---------:|
| User object    | DIY                   | YES        | `oc get users` |
| Default Roles  | Basic                   | YES        | `fine grained` |
| User Role Management| DIY             | YES        | `oc adm policy add-role-to-user admin joe -n dev`|
| CI/CD | DIY             | YES        | `Jenkinsfile is first class citizen`|
| UI | Basic             | Advanced        | `k8s UI is not multitenant and basic vs Multitenant Advanced UI`|
| Routing | DIY             | YES        | `via default HAPROXY Ingress`|
| Logging | DIY             | YES        | `Elastic Search, Fluentd, Kibana`|
| Logs multitenancy | TODO             | YES        | `All logs are user specific`|
| Metrics | DIY             | YES        | `Hawkular / Prometheus (coming)`|
| SDN | Options             | Options,default        | `openvswitch by default`|
| Multitenant Registry | DIY             | YES        | `Full Auth/ACL registry`|


