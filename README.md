# nfalco79.github.io
Alternative Jenkins Update Center.
This update site contains other useful plugin for develop e pipeline that allow releases, traits and some other useful pipeline steps.

## Unmanaged Jenkins

To enable this public update site install the [update-sites-manager-plugin](https://github.com/jenkinsci/update-sites-manager-plugin).
Go to https://jenkins.mycompany.org/updatesites/ and configure a new "Custom update sites" as follow:

ID: nfalco79

URL: https://nfalco79.github.io/update-center.json

Need CA Certificate: enabled

CA Certificate
```
-----BEGIN CERTIFICATE-----
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
V4+hdVI1GAtsuyawuQ==
-----END CERTIFICATE-----
```

## Helm Chart + JCasC Managed

Until JCasC plugin does not support UpdateSite extension (see [this issue](https://github.com/jenkinsci/configuration-as-code-plugin/issues/1305)) a working around is to upload all the needed updateSite RootCA certificates under the ${JENKINS_HOME}/update-center-rootCAs.

When use helm to manager deployment than create a secret to contains all root CA you need like [this](https://nfalco79.github.io/updatesite-certificates.json)
```console
kubectl apply -n jenkins -f updatesite-certificates.json
```

Edit persistence section in the the [values.yml](https://github.com/jenkinsci/helm-charts/blob/main/charts/jenkins/values.yaml) as follow:
```yaml
persistence:
  enabled: true
  ...
  volumes:
    - name: updatesite-certificates
      projected:
        sources:
          - secret:
              name: updatesite-certificates
              items:
                - key: nfalco79-rootCA
                  path: nfalco79.crt
  mounts:
    - mountPath: /var/jenkins_home/update-center-rootCAs
      name: updatesite-certificates
      readOnly: true
```

Upgrade your chart.