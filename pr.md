# Test a feature request


```bash
git checkout -b new-branch-name
```

```bash
humctl create env test --type development --from development
```

Update the Score file with the following changes:
```diff

```

```bash
humctl score deploy -f score.yaml --env test --wait
```

```bash
humctl diff
```

```bash
humctl resources graph deploy . --env test
```

FIXME - push commit in branch a create PR.

[<< Previous: Set up your local environment](codespace.md) |