## com.apple.iokit.IODisplayPortFamily

> `com.apple.iokit.IODisplayPortFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x5b9c8` | `0x5b648` | **`-0x380`** |
| `__TEXT.__os_log` | `0x9fc4` | `0x9f68` | **`-0x5c`** |
| `__TEXT.__cstring` | `0x87e0` | `0x87b7` | **`-0x29`** |

### Other Changes

```diff

-775.0.2.0.0
+775.0.3.0.0

-  CStrings:  1628
+  CStrings:  1625
Functions:
~ sub_fffffff00a0065e4 -> sub_fffffff009ff4834 : 912 -> 16
CStrings:
- "Attempting to retrain link\n"
- "IOAV[%d] %s<0x%llx>::%s: Attempting to retrain link\n"
- "_retrainLink"
```
