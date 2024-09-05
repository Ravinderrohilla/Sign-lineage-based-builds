```bash
git clone https://github.com/ProjectMatrixx/android_vendor_lineage-priv_keys-template.git -b master vendor/lineage-priv/keys
```

```bash
cd vendor/lineage-priv/keys
```

```bash
./generate.sh
```
#include in device.mk
```bash
-include vendor/lineage-priv/keys/keys.mk
