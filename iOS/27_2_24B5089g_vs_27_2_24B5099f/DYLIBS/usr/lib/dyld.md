## dyld

> `/usr/lib/dyld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9f00c` | `0x9ee60` | **`-0x1ac`** |
| `__TEXT.__cstring` | `0x12587` | `0x1263d` | **`+0xb6`** |
| `__DATA_DIRTY.__data` | `0x6c` | `0x64` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x35c0` | `0x35b8` | **`-0x8`** |

### Other Changes

```diff

-27102.0.0.0.0
-  Functions: 3425
-  Symbols:   3277
-  CStrings:  2256
+27104.0.0.0.0
+  Functions: 3423
+  Symbols:   3272
+  CStrings:  2260
Symbols:
+ __ZNK6mach_o6Header22parse_dylinker_commandERKNS0_15LoadCommandInfoEPNS_5ErrorE
- _OUTLINED_FUNCTION_38
- _OUTLINED_FUNCTION_41
- _OUTLINED_FUNCTION_42
- _OUTLINED_FUNCTION_44
- _OUTLINED_FUNCTION_45
- __ZZ16get_xprr_versionvE19cached_xprr_version
CStrings:
+ "27104"
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Wed Sep 30 20:51:37 PDT 2026; root:libignition-64~29579/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Wed Sep 30 20:51:37 PDT 2026; root:libignition-64~29579/libignition_core/RELEASE_ARM64E"
+ "load command #%d %.*s name offset too small"
+ "load command #%d %.*s not a dylib load command"
+ "load command #%d %.*s path offset too small"
+ "load command #%d string start offset too small"
- "27102"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Sun Sep 13 19:37:18 PDT 2026; root:libignition-64~27375/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Sun Sep 13 19:37:18 PDT 2026; root:libignition-64~27375/libignition_core/RELEASE_ARM64E"
```
