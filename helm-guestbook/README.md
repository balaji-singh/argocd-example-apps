
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/balaji-singh/argocd-example-apps.git
# cd into the cloned directory
git checkout 4773b9f1f8fd425f84174c338012771c4e9a989c
helm template . --name-template my-app --include-crds
```