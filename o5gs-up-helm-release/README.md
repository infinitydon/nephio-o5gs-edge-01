# o5gs-up-helm-release

## Description
o5gs-up-helm-release description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] o5gs-up-helm-release`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree o5gs-up-helm-release`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init o5gs-up-helm-release
kpt live apply o5gs-up-helm-release --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
