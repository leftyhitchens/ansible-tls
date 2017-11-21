# About

Simple ansible script that uploads tls certificates. 

## Required Variables

```
# These represent the keys on the local machine running the playbook
local_key_file_path: /etc/pki/tls/keys/server.key
local_cert_file_path: /etc/pki/tls/certs/server.cert
local_ca_file_path: /etc/pki/tls/CA/root.cert
```

## Optional Variables

The variables below have the default values listed below.

```

# These are the paths on the server
key_file_path: /etc/pki/tls/keys/server.key
cert_file_path: /etc/pki/tls/certs/server.cert
ca_file_path: /etc/pki/tls/CA/root.cert
```