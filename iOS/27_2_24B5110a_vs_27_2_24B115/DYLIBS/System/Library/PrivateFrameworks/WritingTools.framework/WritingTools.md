## WritingTools

> `/System/Library/PrivateFrameworks/WritingTools.framework/WritingTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaa94` | `0xab88` | **`+0xf4`** |
| `__TEXT.__gcc_except_tab` | `0x58` | `0x88` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x540` | `0x568` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x528` | `0x540` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1e8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3b8` | `0x3c8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x984` | `0x98c` | **`+0x8`** |

### Other Changes

```diff

-151.1.11.0.0
+151.1.11.100.0

-  Functions: 293
-  Symbols:   571
+  Functions: 294
+  Symbols:   578
Symbols:
+ -[NSUndoManager(WTTurnTracking) wt_registerUndoIfPossibleWithTarget:handler:]
+ GCC_except_table2
+ _NSInternalInconsistencyException
+ _OBJC_EHTYPE_$_NSException
+ _objc_begin_catch
+ _objc_end_catch
+ _objc_exception_rethrow
Functions:
~ -[NSUndoManager(WTTurnTracking) wt_registerTurnWithHandler:] : 152 -> 160
+ -[NSUndoManager(WTTurnTracking) wt_registerUndoIfPossibleWithTarget:handler:]
```
