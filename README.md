[profile file](https://docs.strongswan.org/docs/latest/os/androidVpnClientProfiles.html) format:
```
{
    "uuid": "random_generated",
    "name": "^",
    "type": "ikev2-eap",
    "local": {
        "eap_id": "username",
        "shared_secret": "password"
    },
    "remote": {
        "addr": "server",
        "port": "port",
        "keys": "key_in key_out",
        "cert": "MII..."
    }
}
```
