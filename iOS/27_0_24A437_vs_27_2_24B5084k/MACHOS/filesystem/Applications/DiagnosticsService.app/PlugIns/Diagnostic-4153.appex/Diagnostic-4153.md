## Diagnostic-4153

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4153.appex/Diagnostic-4153`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8f84` | `0x9268` | **`+0x2e4`** |
| `__TEXT.__objc_methtype` | `0xced` | `0xd57` | **`+0x6a`** |
| `__TEXT.__auth_stubs` | `0x460` | `0x4b0` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x27e0` | `0x2820` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x3109` | `0x3142` | **`+0x39`** |
| `__DATA_CONST.__auth_got` | `0x240` | `0x268` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xcd8` | `0xcf0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xd20` | `0xd30` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1d8` | `0x1e8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1374.2.2.0.0
+1374.40.35.0.0

-  Functions: 219
-  Symbols:   180
-  CStrings:  767
+  Functions: 221
+  Symbols:   185
+  CStrings:  771
Symbols:
+ _CGRectGetHeight
+ _CGRectGetMaxX
+ _CGRectGetMaxY
+ _CGRectGetMinX
+ _CGRectGetMinY
+ _CGRectGetWidth
- _CGRectContainsPoint
CStrings:
+ "clampRectangleToDrawableBounds:"
+ "hugPointToDrawableEdges:"
+ "{CGPoint=dd}32@0:8{CGPoint=dd}16"
+ "{CGRect={CGPoint=dd}{CGSize=dd}}48@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16"
```
