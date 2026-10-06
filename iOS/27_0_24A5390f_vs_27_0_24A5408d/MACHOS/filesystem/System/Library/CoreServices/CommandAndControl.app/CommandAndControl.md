## CommandAndControl

> `/System/Library/CoreServices/CommandAndControl.app/CommandAndControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1360` | `0x1484` | **`+0x124`** |
| `__TEXT.__objc_methname` | `0xa42` | `0xa96` | **`+0x54`** |
| `__TEXT.__objc_stubs` | `0x780` | `0x7c0` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x265` | `0x28c` | **`+0x27`** |
| `__DATA.__objc_const` | `0x570` | `0x590` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x160` | `0x180` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x360` | `0x370` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x270` | `0x280` | **`+0x10`** |
| `__TEXT.__cstring` | `0x125` | `0x133` | **`+0xe`** |
| `__DATA_CONST.__auth_got` | `0x140` | `0x148` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xe0` | `0xe8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x30c` | `0x314` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x18` | `0x1c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-185.0.0.0.0
+188.0.0.0.0

-  Functions: 31
-  Symbols:   81
-  CStrings:  180
+  Functions: 32
+  Symbols:   83
+  CStrings:  185
Symbols:
+ _OBJC_CLASS_$_AXSecureIndicatorElevationAssertion
+ _objc_release_x1
CStrings:
+ "@\"AXSecureIndicatorElevationAssertion\""
+ "VoiceControl"
+ "_silElevationAssertion"
+ "_syncSecureIndicatorElevationAssertion"
+ "initWithStyle:reason:"
```
