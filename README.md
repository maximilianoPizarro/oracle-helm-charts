# Oracle 12C Helm Charts Single Instance on Red Hat OpenShift
<p align="left">
<img src="https://img.shields.io/badge/redhat-CC0000?style=for-the-badge&logo=redhat&logoColor=white" alt="Redhat">
<img src="https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white" alt="kubernetes">
<img src="https://img.shields.io/badge/helm-0db7ed?style=for-the-badge&logo=helm&logoColor=white" alt="Helm">
<img src="https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="shell">
<a href="https://www.linkedin.com/in/maximiliano-gregorio-pizarro-consultor-it"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" /></a>
<a href="https://artifacthub.io/packages/search?repo=oracle-helm-charts"><img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/oracle-helm-charts" alt="Artifact Hub" /></a>
</p>


# Installation

## Charts Values Parameters


## Add repository

```bash
helm repo add oracle12c https://maximilianopizarro.github.io/oracle-helm-charts/
```

## Install Chart with parameters

```bash
helm install oracle12c oracle12c/oracle12c --version "VERSION"
```

```bash
Example:
helm install oracle12c oracle12c/oracle12c --version 0.1.0
```


## Uninstall Chart

```bash
helm uninstall oracle12c
```

## Package Info

- [GitHub Page](https://maximilianopizarro.github.io/oracle-helm-charts/)
- [GitHub Repo](https://github.com/maximilianoPizarro/oracle-helm-charts)

## Package Steps

```bash
helm package . -d charts
helm repo index .
```
