# test-prebuild-fail

#### .gitpod.yml
```yaml
tasks:
  - init: |
      # fail prebuild
      exit 1
  - command: |
      echo hello
```

touch