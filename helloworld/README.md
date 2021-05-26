# helloworld

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] helloworld`
Details: https://kpt.dev/reference/pkg/get/

### View package content
`kpt pkg tree helloworld`
Details: https://kpt.dev/reference/pkg/tree/

### Apply the package
```
kpt live init helloworld
kpt live apply helloworld --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/live/
