```sh
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj-labs/applicationset/master/manifests/install.yaml
```
```sh
kubectl apply -f https://raw.githubusercontent.com/ContainerCraft/kargo-deploy/main/applicationset.yaml
```
```
.
├── applicationset.yaml
├── clusters
│   └── uswest1-dev
│       └── config.json
├── LICENSE
├── overlays
│   └── dev
│       └── Kustomization
└── README.md

4 directories, 5 files
```
