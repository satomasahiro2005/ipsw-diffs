## libBasebandManager.dylib

> `/usr/lib/libBasebandManager.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x279d28` | `0x279cd4` | **`-0x54`** |
| `__AUTH_CONST.__objc_const` | `0xa68` | `0xa98` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0xd1f2` | `0xd20d` | **`+0x1b`** |
| `__TEXT.__objc_methlist` | `0x52c` | `0x544` | **`+0x18`** |
| `__TEXT.__cstring` | `0x8c0f` | `0x8c20` | **`+0x11`** |
| `__TEXT.__gcc_except_tab` | `0x3a0dc` | `0x3a0e8` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x688` | `0x690` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xad08` | `0xad10` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x4c` | `0x50` | **`+0x4`** |

### Other Changes

```diff

-1580.0.0.0.0
+1585.0.0.0.0

-  Functions: 6807
-  Symbols:   11817
-  CStrings:  2692
+  Functions: 6809
+  Symbols:   11820
+  CStrings:  2693
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
