## MobileBackup

> `/System/Library/PrivateFrameworks/MobileBackup.framework/MobileBackup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x5760` | `0x5700` | **`-0x60`** |
| `__TEXT.__text` | `0x2e2f0` | `0x2e290` | **`-0x60`** |
| `__TEXT.__cstring` | `0x7a74` | `0x7a5b` | **`-0x19`** |

### Other Changes

```diff

-3039.2.2.0.0
+3039.40.8.0.0

-  CStrings:  1142
+  CStrings:  1139
Functions:
~ _MBBuildIsSeed : 172 -> 96
~ ____MBGetCachedGestaltValues_block_invoke : 708 -> 688
CStrings:
- "Beta"
- "Carrier"
- "ReleaseType"
```
