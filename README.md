Repro of an issue where specifying a `protocol` in the base config causes
patches with the same port numbers but without a protocol field to be ignored.

Usage:

```sh
kustomize build . > build_output.yaml
```
