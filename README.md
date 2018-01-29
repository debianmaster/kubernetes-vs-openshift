### WIP
| Feature        | Kubernetes           | Openshift  |  Details |
| -------------  |:-------------:       | ----------:|---------:|
| OS support     | DIY  |  YES | Atomic host or RHEL |
| User object    | DIY                   | YES        | `oc get users` |
| User Role Management| DIY yamls            | YES        | `oc adm policy add-role-to-user admin joe -n dev`|
| CI/CD | DIY             | YES        | `Jenkinsfile is first class citizen`|
| UI | Very Basic             | Advanced        | `k8s UI is not multitenant and basic vs Multitenant Advanced UI`|
| Registry UI | No UI         | Advanced        | `ACL Registry UI`|
| Routing | DIY             | YES        | `via default HAPROXY Ingress`|
| Logging | DIY             | YES        | `Elastic Search, Fluentd, Kibana`|
| Security | DIY | YES  | `selinux, scc, builds are optimized for security` |
| Logs multitenancy | TODO             | YES        | `All logs are user specific`|
| Metrics | DIY             | YES        | `Hawkular / Prometheus (coming)`|
| SDN | Options             | Options,default        | `openvswitch by default`|
| Multitenant Registry | DIY             | YES        | `Full Auth/ACL registry`|
| Default Roles  | Basic                   | YES        | `fine grained & frequently used` |
| Ansible Service Broker | Community | YES  | `supported solution` |
| AWS Service Broker | Community | YES  | `supported solution` |
| Container Native Storage | Community | YES  | `supported with Gluster File/Block/Object storage` |
| Supported Runtimes | Community | YES  | `Support for various language runtimes via RHOAR` |
| Istio | Community | Community  | `Potential support in future` |


