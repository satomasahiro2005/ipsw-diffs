## libBasebandManagerICE.dylib

> `/usr/lib/libBasebandManagerICE.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2737f8` | `0x2737a4` | **`-0x54`** |
| `__AUTH_CONST.__objc_const` | `0xa68` | `0xa98` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0xcf7d` | `0xcf98` | **`+0x1b`** |
| `__TEXT.__objc_methlist` | `0x52c` | `0x544` | **`+0x18`** |
| `__TEXT.__cstring` | `0x8612` | `0x8622` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xac60` | `0xac70` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x39918` | `0x39924` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x688` | `0x690` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x4c` | `0x50` | **`+0x4`** |

### Other Changes

```diff

-1580.0.0.0.0
+1585.0.0.0.0

-  Functions: 6830
-  Symbols:   11794
-  CStrings:  2596
+  Functions: 6832
+  Symbols:   11797
+  CStrings:  2597
Symbols:
+ -[AccessoryDetection fAlreadyStarted]
+ -[AccessoryDetection setFAlreadyStarted:]
+ _OBJC_IVAR_$_AccessoryDetection._fAlreadyStarted
CStrings:
+ ".*ATCS_TIMEOUT.*"
+ "AppleBasebandManager-AppleBasebandServices_Manager-1585"
+ "AppleBasebandServices_Manager-1585"
+ "Re-sending %zu cached accessory(ies) to baseband on start"
- "AppleBasebandManager-AppleBasebandServices_Manager-1580"
- "AppleBasebandServices_Manager-1580"
- "Failed to get Accessory State!"
```
