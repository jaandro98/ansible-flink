# ansible-flink
Flink deployment with Ansible

## PREFLIGHT
```
ansible-playbook -i inventory/local.ini F.Preflight.yml --extra-vars '{"newJarArtifactoryUrl":"","newConfArtifactoryUrl":"","latestStableJarArtifactoryUrl":"","latestStableConfArtifactoryUrl":"","clusterName":""}'
```

## INSTALL
```
ansible-playbook -i inventory/local.ini F.Install.yml --extra-vars '{"newJarArtifactoryUrl":"","newConfArtifactoryUrl":"","latestStableJarArtifactoryUrl":"","latestStableConfArtifactoryUrl":"","clusterName":""}'
```
