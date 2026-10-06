## replayd

> `/usr/libexec/replayd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb8c4c` | `0xb929c` | **`+0x650`** |
| `__TEXT.__oslogstring` | `0x1626c` | `0x1634a` | **`+0xde`** |
| `__TEXT.__cstring` | `0x17a78` | `0x17b48` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0xf060` | `0xf0e0` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x5cc0` | `0x5ce0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2a98` | `0x2ab8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x22f8` | `0x2310` | **`+0x18`** |
| `__DATA.__bss` | `0x258` | `0x268` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1910` | `0x1920` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xfbc` | `0xfc8` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0xc98` | `0xca0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 3634
-  Symbols:   801
-  CStrings:  7335
+  Functions: 3639
+  Symbols:   802
+  CStrings:  7343
Symbols:
+ _MGGetProductType
CStrings:
+ " [INFO] %{public}s:%d Captured initial displayID: %u"
+ " [INFO] %{public}s:%d Captured recording displayID: %u"
+ " [INFO] %{public}s:%d Display changed from %u to %u"
+ " [INFO] %{public}s:%d Display configuration changed: %u -> %u"
+ "-[RPSession setUpFrontBoardServices]_block_invoke"
+ "-[SCSystemServicesManager captureDidStartForSession:withConfig:]_block_invoke"
+ "-[SCSystemServicesManager setUpFrontBoardServices]_block_invoke"
+ "Localizable-V68"
```
