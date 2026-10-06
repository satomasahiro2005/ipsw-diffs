## HomeDeviceSetup

> `/System/Library/PrivateFrameworks/HomeDeviceSetup.framework/HomeDeviceSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x729fc` | `0x72af8` | **`+0xfc`** |
| `__TEXT.__cstring` | `0x1aae4` | `0x1ab54` | **`+0x70`** |

### Other Changes

```diff

-  Functions: 3080
+  Functions: 3082

-  CStrings:  3122
+  CStrings:  3124
CStrings:
+ "sysDropBuildMode: internal build + sysDropEnabled -> %s\n"
+ "sysDropBuildMode: no path matched -> %s\n"
+ "sysDropBuildMode: prod + profile installed -> %s\n"
- "sysDropBuildMode: Seed path + profile -> %s\n"
```
