# VSCode Key bindings, User Settings, Extensions

## Extensions

- for `React` + `Typescript`
  - Prettier
    - VSCode 기본 formatter로 사용.
  - Tailwind CSS
  - Headwind
    - Tailwind CSS 코드 이해하기 쉬운 순서로 재배치
  - PostCSS
    - `@tailwind base;` 와 같은 구문 사용 시, ide 경고메세지 출력X

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
