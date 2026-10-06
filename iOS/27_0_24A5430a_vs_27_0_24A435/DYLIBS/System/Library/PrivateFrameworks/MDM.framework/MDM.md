## MDM

> `/System/Library/PrivateFrameworks/MDM.framework/MDM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5559c` | `0x55554` | **`-0x48`** |
| `__TEXT.__oslogstring` | `0x70d4` | `0x70a5` | **`-0x2f`** |

### Other Changes

```diff

-  CStrings:  1272
+  CStrings:  1271
Functions:
~ -[MDMServerCore migrateMDMWithContext:completion:] : 316 -> 244
CStrings:
- "Device is on seed build. Skip the random delay"
```
