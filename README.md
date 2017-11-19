### WIP

| Feature        | Kubernetes           | openshift  |  Details |
| -------------  |:-------------:       | ----------:|---------:|
| User object    | NO                   | YES        | `oc get users` |
| Default Roles  | NO                   | YES        | `admin/edit/view system:imagepuller etc` |
| User Role Management| DIY             | YES        | `oc adm policy add-role-to-user admin joe -n dev`|
