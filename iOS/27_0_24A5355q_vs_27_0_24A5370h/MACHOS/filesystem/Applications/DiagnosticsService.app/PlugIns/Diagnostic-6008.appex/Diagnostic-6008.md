## Diagnostic-6008

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6008.appex/Diagnostic-6008`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6404` | `0x64a0` | **`+0x9c`** |
| `__TEXT.__objc_methname` | `0xd8f` | `0xddb` | **`+0x4c`** |
| `__DATA.__objc_const` | `0x950` | `0x990` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x3c0` | `0x400` | **`+0x40`** |
| `__DATA.__objc_data` | `0x4e0` | `0x508` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x69c` | `0x6bc` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x2a0` | `0x2b8` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x2b8` | `0x2d0` | **`+0x18`** |
| `__DATA.__data` | `0x6c0` | `0x6d0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x248` | `0x258` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x12c` | `0x138` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xb8` | `0xc0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1351.0.0.0.0
+1369.0.0.0.0

-  Symbols:   107
-  CStrings:  203
+  Symbols:   108
+  CStrings:  207
Symbols:
+ _OBJC_CLASS_$_NSLock
Functions:
~ sub_100004c08 : 1540 -> 1652
~ sub_100005330 -> sub_1000053a0 : 756 -> 796
~ sub_10000567c -> sub_100005714 : 128 -> 144
~ sub_100005948 -> sub_1000059f0 : 280 -> 276
~ sub_100006794 -> sub_100006838 : 392 -> 384
CStrings:
+ "endTestLock"
+ "lock"
+ "testFinished"
+ "unlock"
```
