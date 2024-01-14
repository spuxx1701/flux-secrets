# flux-secrets

## Managing secrets

Guide: https://fluxcd.io/flux/guides/mozilla-sops/

Encrpyt a secret:

```bash
sops --age=age1xae7v2fsvs42znxu8zaz3cmgtktmqwmmrs5wp62w0pgvy5d9pf6q3qjg82 \
--encrypt --encrypted-regex '^(data|stringData)$' --in-place secret.yaml
```
