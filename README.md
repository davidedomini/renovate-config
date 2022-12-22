# Custom Renovate configurations
In order to reuse them you only need to set your ``renovate.json`` file as follows:
``` json
{
  "extends": [
      "github>davidedomini/renovate-config:file-name"
  ]
}
```
If you want to specify a specific file you can replace ``file-name``, otherwise you can remove ``:file-name`` and the ``default.json`` configuration will be used.
