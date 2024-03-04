# argocd-deploy

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] argocd-deploy`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree argocd-deploy`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init argocd-deploy
kpt live apply argocd-deploy --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
