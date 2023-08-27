# VSCode Key bindings and Extensions

## Extensions

### Extensions backup

```shell
# Get the extensions.list file
code --list-extensions > extensions.list
```

### Extensions restore

```shell
# Restore using extensions.list file
cat extensions.list |% { code --install-extension $_}
```
