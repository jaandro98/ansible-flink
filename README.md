# ansible-flink
Flink deployment with Ansible

## PREFLIGHT
```
ansible-playbook tasks/main.yml -i inventory/hosts F.Preflight.yml --extra-vars '{"newJarArtifactoryUrl":"","newConfArtifactoryUrl":"","latestStableJarArtifactoryUrl":"","latestStableConfArtifactoryUrl":"","clusterName":""}'
```

## INSTALL
```
ansible-playbook tasks/main.yml -i inventory/hosts F.Install.yml --extra-vars '{"newJarArtifactoryUrl":"","newConfArtifactoryUrl":"","latestStableJarArtifactoryUrl":"","latestStableConfArtifactoryUrl":"","clusterName":""}'
```
