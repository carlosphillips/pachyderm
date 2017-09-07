## ./pachctl auth login

Login to Pachyderm with your GitHub account

### Synopsis


Login to Pachyderm with your GitHub account. Any resources that have been restricted to the email address registered with your GitHub account will subsequently be accessible.

```
./pachctl auth login
```

### Options

```
      --user string   GitHub username of the user logging in. If unset, the username will be inferred from the github authorization code
```

### Options inherited from parent commands

```
      --no-metrics   Don't report user metrics for this command
  -v, --verbose      Output verbose logs
```

### SEE ALSO
* [./pachctl auth](./pachctl_auth.md)	 - Auth commands manage access to data in a Pachyderm cluster

###### Auto generated by spf13/cobra on 7-Sep-2017