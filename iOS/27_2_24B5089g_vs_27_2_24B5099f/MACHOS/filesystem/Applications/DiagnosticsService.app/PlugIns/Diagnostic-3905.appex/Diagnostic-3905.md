## Diagnostic-3905

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-3905.appex/Diagnostic-3905`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a20` | `0x3ac4` | **`+0xa4`** |
| `__TEXT.__objc_methname` | `0x10f1` | `0x1111` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1200` | `0x1220` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x5a8` | `0x5b8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x4dc` | `0x4ec` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x100` | `0x108` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1374.40.40.0.0
+1374.40.54.0.0

-  Functions: 80
+  Functions: 81

-  CStrings:  306
+  CStrings:  308
Functions:
~ sub_100002460 : 4720 -> 164
+ sub_100002504
CStrings:
+ "setFrame:"
+ "viewDidLayoutSubviews"
```
