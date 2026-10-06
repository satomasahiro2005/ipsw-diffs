## InstalledContentLibrary

> `/System/Library/PrivateFrameworks/InstalledContentLibrary.framework/InstalledContentLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xf00` | `0x1180` | **`+0x280`** |
| `__DATA_DIRTY.__objc_data` | `0x780` | `0x500` | **`-0x280`** |
| `__AUTH_CONST.__cfstring` | `0xd640` | `0xd4e0` | **`-0x160`** |
| `__TEXT.__text` | `0xcee4c` | `0xcef94` | **`+0x148`** |
| `__TEXT.__cstring` | `0x185ce` | `0x1855e` | **`-0x70`** |
| `__DATA.__bss` | `0x280` | `0x2d0` | **`+0x50`** |
| `__DATA_DIRTY.__bss` | `0x50` | `—` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x1010` | `0xfd8` | **`-0x38`** |
| `__AUTH_CONST.__auth_got` | `0xbf8` | `0xc08` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4f0` | `0x500` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x5b94` | `0x5ba4` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3088` | `0x3090` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x19c8` | `0x19d0` | **`+0x8`** |

### Other Changes

```diff

-1660.0.0.0.0
+1663.0.0.0.1

-  Functions: 2407
-  Symbols:   3825
-  CStrings:  2273
+  Functions: 2409
+  Symbols:   3830
+  CStrings:  2263
Symbols:
+ -[MIAppExtensionBundle parentBundleAllowsPrivatePersonaEntitlements]
+ ____CopyRunnablePlatforms_block_invoke
+ ___block_descriptor_40_e8_32s_e12_v20?0I8^B12ls32l8
+ _macho_for_each_runnable_platform
+ _macho_platform_name
CStrings:
+ "v20@?0I8^B12"
- "Mac Catalyst"
- "bridgeOS"
- "iOS"
- "iOS Simulator"
- "macOS"
- "tvOS"
- "tvOS Simulator"
- "visionOS"
- "visionOS Simulator"
- "watchOS"
- "watchOS Simulator"
```
