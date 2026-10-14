## WritingTools

> `/System/Library/PrivateFrameworks/WritingTools.framework/WritingTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa994` | `0xaa94` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x1520` | `0x1560` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x248` | `0x270` | **`+0x28`** |
| `__TEXT.__cstring` | `0x6f7` | `0x717` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x528` | `0x540` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x96c` | `0x984` | **`+0x18`** |
| `__DATA_CONST.__objc_catlist` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3b0` | `0x3b8` | **`+0x8`** |

### Other Changes

```diff

-151.1.9.0.0
+151.1.11.0.0

-  Functions: 291
-  Symbols:   565
-  CStrings:  79
+  Functions: 293
+  Symbols:   571
+  CStrings:  80
Symbols:
+ -[NSUndoManager(WTTurnTracking) wt_registerTurnWithHandler:]
+ _OBJC_CLASS_$_NSUndoManager
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSUndoManager_$_WTTurnTracking
+ __OBJC_$_CATEGORY_NSUndoManager_$_WTTurnTracking
+ ___60-[NSUndoManager(WTTurnTracking) wt_registerTurnWithHandler:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e23_v16?0"NSUndoManager"8ls32l8
CStrings:
+ "v16@?0@\"NSUndoManager\"8"
```
