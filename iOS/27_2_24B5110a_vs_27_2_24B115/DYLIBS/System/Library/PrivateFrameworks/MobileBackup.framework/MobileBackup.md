## MobileBackup

> `/System/Library/PrivateFrameworks/MobileBackup.framework/MobileBackup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x5700` | `0x5760` | **`+0x60`** |
| `__TEXT.__text` | `0x2e290` | `0x2e2f0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x7a5b` | `0x7a74` | **`+0x19`** |

### Other Changes

```diff

-  CStrings:  1139
+  CStrings:  1142
Functions:
~ _MBBuildIsSeed : 96 -> 172
~ ____MBGetCachedGestaltValues_block_invoke : 688 -> 708
CStrings:
+ "Beta"
+ "Carrier"
+ "ReleaseType"
```
