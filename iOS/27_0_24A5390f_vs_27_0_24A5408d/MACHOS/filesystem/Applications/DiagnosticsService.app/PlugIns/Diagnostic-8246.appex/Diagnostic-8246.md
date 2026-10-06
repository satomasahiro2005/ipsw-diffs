## Diagnostic-8246

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8246.appex/Diagnostic-8246`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c60` | `0x50f0` | **`+0x490`** |
| `__TEXT.__objc_methname` | `0x1802` | `0x1b47` | **`+0x345`** |
| `__TEXT.__objc_stubs` | `0x1660` | `0x18e0` | **`+0x280`** |
| `__TEXT.__objc_methtype` | `0x41e` | `0x52e` | **`+0x110`** |
| `__DATA.__objc_const` | `0xaf8` | `0xbe8` | **`+0xf0`** |
| `__DATA.__objc_selrefs` | `0x760` | `0x800` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x6ac` | `0x74c` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x3e0` | `0x400` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x7c` | `0x90` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0x1f8` | `0x208` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1e8` | `0x1f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1374.0.27.0.0
+1374.2.1.0.0

-  Functions: 126
-  Symbols:   144
-  CStrings:  441
+  Functions: 139
+  Symbols:   147
+  CStrings:  478
Symbols:
+ _CGRectEqualToRect
+ _UIEdgeInsetsZero
+ _objc_opt_respondsToSelector
CStrings:
+ ";"
+ "@\"NSLayoutConstraint\""
+ "T@\"NSLayoutConstraint\",&,N,V_instructionLeadingConstraint"
+ "T@\"NSLayoutConstraint\",&,N,V_instructionTopConstraint"
+ "T@\"NSLayoutConstraint\",&,N,V_instructionTrailingConstraint"
+ "T{CGRect={CGPoint=dd}{CGSize=dd}},N,V_latchedSafeAreaBounds"
+ "T{UIEdgeInsets=dddd},N,V_latchedSafeAreaInsets"
+ "_instructionLeadingConstraint"
+ "_instructionTopConstraint"
+ "_instructionTrailingConstraint"
+ "_latchedSafeAreaBounds"
+ "_latchedSafeAreaInsets"
+ "_peripheryInsets"
+ "activateConstraints:"
+ "constant"
+ "dk_instructionInsets"
+ "dk_peripheryInsets"
+ "dk_updateSafeAreaLatch"
+ "instructionLeadingConstraint"
+ "instructionTopConstraint"
+ "instructionTrailingConstraint"
+ "latchedSafeAreaBounds"
+ "latchedSafeAreaInsets"
+ "leadingAnchor"
+ "safeAreaInsets"
+ "screen"
+ "setConstant:"
+ "setInstructionLeadingConstraint:"
+ "setInstructionTopConstraint:"
+ "setInstructionTrailingConstraint:"
+ "setLatchedSafeAreaBounds:"
+ "setLatchedSafeAreaInsets:"
+ "trailingAnchor"
+ "v48@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16"
+ "v48@0:8{UIEdgeInsets=dddd}16"
+ "window"
+ "{CGRect=\"origin\"{CGPoint=\"x\"d\"y\"d}\"size\"{CGSize=\"width\"d\"height\"d}}"
+ "{CGRect={CGPoint=dd}{CGSize=dd}}16@0:8"
+ "{UIEdgeInsets=\"top\"d\"left\"d\"bottom\"d\"right\"d}"
+ "{UIEdgeInsets=dddd}16@0:8"
- "8"
- "safeAreaLayoutGuide"
- "setActive:"
```
