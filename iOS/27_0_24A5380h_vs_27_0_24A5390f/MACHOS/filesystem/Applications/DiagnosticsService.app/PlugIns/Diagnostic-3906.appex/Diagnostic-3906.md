## Diagnostic-3906

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-3906.appex/Diagnostic-3906`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7aa8` | `0x7c30` | **`+0x188`** |
| `__TEXT.__objc_methname` | `0x234e` | `0x23d4` | **`+0x86`** |
| `__TEXT.__objc_stubs` | `0x2060` | `0x20e0` | **`+0x80`** |
| `__DATA.__objc_const` | `0x1098` | `0x10f8` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xad8` | `0xb18` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x6ce` | `0x70e` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xa50` | `0xa78` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x7d0` | `0x7e0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xb0` | `0xb8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x3f8` | `0x400` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x118` | `0x120` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2f0` | `0x2f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1374.0.5.0.0
+1374.0.27.0.0

-  Functions: 255
-  Symbols:   174
-  CStrings:  555
+  Functions: 260
+  Symbols:   176
+  CStrings:  567
Symbols:
+ _CGRectIsEmpty
+ _CGSizeZero
CStrings:
+ "TB,N,V_hasSetup"
+ "T{CGSize=dd},N,V_lastLaidOutSize"
+ "_hasSetup"
+ "_lastLaidOutSize"
+ "hasSetup"
+ "lastLaidOutSize"
+ "setHasSetup:"
+ "setLastLaidOutSize:"
+ "v32@0:8{CGSize=dd}16"
+ "viewDidLayoutSubviews"
+ "{CGSize=\"width\"d\"height\"d}"
+ "{CGSize=dd}16@0:8"
```
