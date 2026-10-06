## Diagnostic-6004

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6004.appex/Diagnostic-6004`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0xe10` | `0xdb0` | **`-0x60`** |
| `__TEXT.__objc_methname` | `0x1368` | `0x1310` | **`-0x58`** |
| `__TEXT.__objc_methlist` | `0x544` | `0x504` | **`-0x40`** |
| `__TEXT.__text` | `0x14888` | `0x14868` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x4c0` | `0x4b0` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x508` | `0x500` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1374.0.27.0.0
+1374.2.1.0.0

-  Functions: 482
+  Functions: 478

-  CStrings:  385
+  CStrings:  383
Functions:
~ sub_1000081f4 : 8 -> 356
- sub_1000081fc
- sub_100008858
- sub_10000d1c8
- sub_100012290
CStrings:
- "TB,N,R"
- "prefersStatusBarHidden"
```
