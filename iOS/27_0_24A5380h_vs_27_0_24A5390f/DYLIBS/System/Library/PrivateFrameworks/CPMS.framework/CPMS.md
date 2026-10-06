## CPMS

> `/System/Library/PrivateFrameworks/CPMS.framework/CPMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9818` | `0x99c8` | **`+0x1b0`** |
| `__AUTH_CONST.__cfstring` | `0x1300` | `0x1340` | **`+0x40`** |
| `__TEXT.__cstring` | `0xcd5` | `0xcf8` | **`+0x23`** |

### Other Changes

```diff

-1191.0.16.0.0
+1191.0.27.0.0

-  CStrings:  291
+  CStrings:  293
Functions:
~ +[CPMSStateReader getCPMSControlStateSnapshotDictionary:] : 2140 -> 2344
~ +[CPMSStateReader flattenSnapshot:index:into:] : 2760 -> 2988
CStrings:
+ "%@%@_Battery%d_%d"
+ "SystemCapability"
```
