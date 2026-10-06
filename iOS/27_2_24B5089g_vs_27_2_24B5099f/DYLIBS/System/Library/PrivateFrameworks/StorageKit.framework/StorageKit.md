## StorageKit

> `/System/Library/PrivateFrameworks/StorageKit.framework/StorageKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bd00` | `0x2bd84` | **`+0x84`** |
| `__TEXT.__oslogstring` | `0x14ff` | `0x1540` | **`+0x41`** |

### Other Changes

```diff

-1076.40.3.0.0
+1076.40.4.0.0

-  CStrings:  677
+  CStrings:  678
Functions:
~ -[SKIOMedia initWithDevName:] : 276 -> 408
CStrings:
+ "IO entry for %{public}@ does not conform to %{public}@, refusing"
```
