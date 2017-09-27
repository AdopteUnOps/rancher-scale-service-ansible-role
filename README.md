# docker-ansible-role

Scale rancher service in an existing rancher environment.


Mandatory Variables
-------------------
```
rancher_api_key: "mykey"
rancher_api_secret: "mysecret"
rancher_project_name: "default"

service_fqdn: mystack
service_scale: 1
```

Role Variables
--------------

```
rancher_master_url: "http://localhost:8080"
```

License
-------

Apache License 2
