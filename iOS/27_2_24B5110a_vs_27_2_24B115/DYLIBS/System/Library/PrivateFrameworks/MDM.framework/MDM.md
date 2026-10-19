## MDM

> `/System/Library/PrivateFrameworks/MDM.framework/MDM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x56644` | `0x565fc` | **`-0x48`** |
| `__TEXT.__oslogstring` | `0x737e` | `0x734f` | **`-0x2f`** |

### Other Changes

```diff

-  CStrings:  1284
+  CStrings:  1283
Functions:
~ -[MDMServerCore migrateMDMWithContext:completion:] : 316 -> 244
CStrings:
- "Device is on seed build. Skip the random delay"
```
