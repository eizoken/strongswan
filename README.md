profile format:
```
{
    "uuid": "random_generated",
    "name": "^",
    "type": "ikev2-eap",
    "local": {
        "eap_id"  : "username",
        "eap_pass": "password"
    },
    "remote": {
        "addr": "server",
        "port": "port",
        "keys": "key_in key_out",
        "cert": "MII..."
    }
}
```
