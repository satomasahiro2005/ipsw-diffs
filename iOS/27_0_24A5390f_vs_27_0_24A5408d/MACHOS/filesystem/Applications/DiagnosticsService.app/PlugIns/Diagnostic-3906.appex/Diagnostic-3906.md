## Diagnostic-3906

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-3906.appex/Diagnostic-3906`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c30` | `0x7d54` | **`+0x124`** |
| `__TEXT.__objc_methtype` | `0x70e` | `0x75e` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x7e0` | `0x820` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x400` | `0x420` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x23d4` | `0x23f4` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x20e0` | `0x2100` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xa78` | `0xa80` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xb18` | `0xb20` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2f8` | `0x300` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
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
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1374.0.27.0.0
+1374.2.1.0.0

-  Functions: 260
-  Symbols:   176
-  CStrings:  567
+  Functions: 261
+  Symbols:   180
+  CStrings:  569
Symbols:
+ _CGRectGetMaxX
+ _CGRectGetMaxY
+ _CGRectGetMinX
+ _CGRectGetMinY
CStrings:
+ "clampRectangleToViewBounds:"
+ "{CGRect={CGPoint=dd}{CGSize=dd}}48@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16"
```
