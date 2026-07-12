# opentv-config

Version policy for the OpenTV update gate. Edit `version.json` to force old app versions to update:

```json
{ "iosMinVersion": "1.1.0" }
```

Any install older than `iosMinVersion` shows an "Update required" screen at launch. `1.0.0` forces nothing.
