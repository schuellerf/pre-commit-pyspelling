# Pre Commit Plugin to call pyspelling

[pre-commit](https://pre-commit.com) plugin to call [pyspelling](https://github.com/facelessuser/pyspelling)


## Change config file

**Optionally** you might want to change the config file in your `.pre-commit-config.yaml` like so:

```
 - repo: https://github.com/schuellerf/pre-commit-pyspelling
      rev: master
      hooks:
          - id: pyspelling
            args: ["--config", ".spellcheck.yml"]
```
