
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/balaji-singh/argocd-example-apps.git
# cd into the cloned directory
git checkout 870ed28b90b8762b401354ba44e60801fb8e3d3e
helm template . --name-template my-app --include-crds
```