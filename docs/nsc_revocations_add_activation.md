## nsc revocations add_activation

Revoke an accounts access to an export

### Synopsis

Revoke an accounts access to an export

```
nsc revocations add_activation [flags]
```

### Options

```
  -a, --account string          account name
      --at int                  revokes all user credentials created before a Unix timestamp ('0' is treated as now)
  -h, --help                    help for add_activation
      --service                 service
  -s, --subject string          export subject
  -t, --target-account string   target-account
```

### Options inherited from parent commands

```
  -i, --interactive          ask questions for various settings
  -K, --private-key string   private key
```

### SEE ALSO

* [nsc revocations](nsc_revocations.md)	 - Manage revocation for users and activations from an account

###### Auto generated by spf13/cobra on 26-Nov-2019
