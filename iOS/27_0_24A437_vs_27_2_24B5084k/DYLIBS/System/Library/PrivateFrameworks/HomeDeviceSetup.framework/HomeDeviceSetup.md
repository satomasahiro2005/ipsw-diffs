## HomeDeviceSetup

> `/System/Library/PrivateFrameworks/HomeDeviceSetup.framework/HomeDeviceSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72af8` | `0x72c3c` | **`+0x144`** |
| `__TEXT.__cstring` | `0x1ab54` | `0x1aae4` | **`-0x70`** |
| `__TEXT.__objc_methlist` | `0x345c` | `0x3484` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x78b8` | `0x78d8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2db0` | `0x2dd0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x848` | `0x850` | **`+0x8`** |
| `__DATA.__data` | `0xb70` | `0xb78` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1978` | `0x1980` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xcb` | `0xd3` | **`+0x8`** |

### Other Changes

```diff

-405.0.11.0.0
+405.10.26.0.0

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 3082
-  Symbols:   3338
-  CStrings:  3124
+  Functions: 3080
+  Symbols:   3341
+  CStrings:  3122
Symbols:
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftIntents_$_HomeDeviceSetup
+ _symbolic _____Sg 12FindMyLocate12ClientTargetV
CStrings:
+ "sysDropBuildMode: Seed path + profile -> %s\n"
- "sysDropBuildMode: internal build + sysDropEnabled -> %s\n"
- "sysDropBuildMode: no path matched -> %s\n"
- "sysDropBuildMode: prod + profile installed -> %s\n"
```
