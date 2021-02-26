# Installation
Place the `kubectl-util` file anywhere in your `$PATH`.

# Usage:

```
➜  ~ kubectl util --help
  Usage:
    config:set FOO=BAR APP_ENV=staging
    config:get
  -a, --app=APP
  -e, --environment=ENV
```

```
kubectl util config:set FOO=BAR -a my-app -e staging
```

```
kubectl util config:get -a my-app -e staging
```