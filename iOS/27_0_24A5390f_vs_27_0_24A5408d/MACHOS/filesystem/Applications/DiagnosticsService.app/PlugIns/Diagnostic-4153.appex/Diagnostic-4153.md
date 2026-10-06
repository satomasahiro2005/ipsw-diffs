## Diagnostic-4153

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4153.appex/Diagnostic-4153`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8940` | `0x8dd0` | **`+0x490`** |
| `__TEXT.__objc_methname` | `0x2db0` | `0x30f2` | **`+0x342`** |
| `__TEXT.__objc_stubs` | `0x2560` | `0x27c0` | **`+0x260`** |
| `__DATA.__objc_const` | `0x1268` | `0x1358` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0xc38` | `0xcd8` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0xc80` | `0xd18` | **`+0x98`** |
| `__TEXT.__objc_methtype` | `0xc72` | `0xced` | **`+0x7b`** |
| `__TEXT.__auth_stubs` | `0x440` | `0x460` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xe0` | `0xf4` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0x230` | `0x240` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1f8` | `0x200` | **`+0x8`** |

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

-  Functions: 207
-  Symbols:   175
-  CStrings:  730
+  Functions: 220
+  Symbols:   178
+  CStrings:  763
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
+ "setConstant:"
+ "setInstructionLeadingConstraint:"
+ "setInstructionTopConstraint:"
+ "setInstructionTrailingConstraint:"
+ "setLatchedSafeAreaBounds:"
+ "setLatchedSafeAreaInsets:"
+ "trailingAnchor"
+ "v48@0:8{UIEdgeInsets=dddd}16"
+ "{UIEdgeInsets=\"top\"d\"left\"d\"bottom\"d\"right\"d}"
+ "{UIEdgeInsets=dddd}16@0:8"
- "8"
- "safeAreaLayoutGuide"
```
