## deleted_helper

> `/System/Library/PrivateFrameworks/CacheDelete.framework/deleted_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9cc0` | `0x9f30` | **`+0x270`** |
| `__TEXT.__oslogstring` | `0x1e24` | `0x1ebf` | **`+0x9b`** |
| `__TEXT.__cstring` | `0x8fd` | `0x961` | **`+0x64`** |
| `__DATA_CONST.__cfstring` | `0x680` | `0x6c0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x508` | `0x548` | **`+0x40`** |
| `__DATA_CONST.__objc_arrayobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0xf0` | `0x100` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x800` | `0x810` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x410` | `0x418` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x198` | `0x1a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 84
-  Symbols:   378
-  CStrings:  334
+  Functions: 85
+  Symbols:   382
+  CStrings:  341
Symbols:
+ _OBJC_CLASS_$_NSConstantArray
+ ___block_descriptor_32_e51_B24?0r*8^{?=BBqiIQQQ{timespec=qq}{timespec=qq}B}16l
+ ___periodic_block_invoke
+ _os_variant_has_internal_diagnostics
Functions:
~ ___main_block_invoke_2 : 204 -> 768
+ ___periodic_block_invoke
CStrings:
+ "/var/mobile/Library/AutoBugCapture/"
+ "/var/mobile/Library/Logs/AutoBugCapture/"
+ "Customer build, clearing %@"
+ "com.apple.cache_delete"
+ "customerReleaseBuild IS INTERNAL BUILD"
+ "customerReleaseBuild IS NOT INTERNAL BUILD"
+ "customerReleaseBuild IS NOT SEED BUILD"
+ "unable to get address of MGGetBoolAnswer"
- "customerReleaseBuild IS SEED BUILD"
```
