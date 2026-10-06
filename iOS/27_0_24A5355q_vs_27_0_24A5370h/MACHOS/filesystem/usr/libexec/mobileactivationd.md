## mobileactivationd

> `/usr/libexec/mobileactivationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x349dc0` | `0x34a01c` | **`+0x25c`** |
| `__TEXT.__gcc_except_tab` | `0x1a68` | `0x1a94` | **`+0x2c`** |
| `__DATA_CONST.__cfstring` | `0xd1e0` | `0xd200` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x5e8` | `0x600` | **`+0x18`** |
| `__TEXT.__cstring` | `0xeb89` | `0xeb94` | **`+0xb`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1137.0.0.0.0
+1144.0.0.0.0

-  Functions: 1642
-  Symbols:   3998
-  CStrings:  3032
+  Functions: 1643
+  Symbols:   4001
+  CStrings:  3033
Symbols:
+ _CTParseLeafSPKI
+ _OUTLINED_FUNCTION_47
+ _OUTLINED_FUNCTION_57
+ ___block_descriptor_56_e8_32s40s48r_e29_v24?0"NSError"8"NSError"16l
+ _kMAEnhancedActivationValidationBootSessionUUID
- _OUTLINED_FUNCTION_48
- ___block_descriptor_48_e8_32s40r_e29_v24?0"NSError"8"NSError"16l
CStrings:
+ "1144"
+ "Absinthe/2.0 iOS Device Activator (MobileActivation-1144 built on Jun 15 2026 at 23:58:33)"
+ "EnhancedActivationValidationBootSessionUUID"
+ "iOS Device Activator (MobileActivation-1144)"
+ "inboxupdaterd"
+ "x-jmet-serial"
- "1137"
- "Absinthe/2.0 iOS Device Activator (MobileActivation-1137 built on Jun  1 2026 at 21:23:09)"
- "Device is not configured for legacy activation."
- "iOS Device Activator (MobileActivation-1137)"
- "inboxupaterd"
```
