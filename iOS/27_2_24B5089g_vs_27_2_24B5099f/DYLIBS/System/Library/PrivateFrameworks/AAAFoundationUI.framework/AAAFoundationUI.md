## AAAFoundationUI

> `/System/Library/PrivateFrameworks/AAAFoundationUI.framework/AAAFoundationUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fbe8` | `0x201d4` | **`+0x5ec`** |
| `__AUTH_CONST.__objc_const` | `0x950` | `0xb90` | **`+0x240`** |
| `__TEXT.__objc_methlist` | `0x1ec` | `0x294` | **`+0xa8`** |
| `__DATA_CONST.__objc_selrefs` | `0x170` | `0x208` | **`+0x98`** |
| `__AUTH.__objc_data` | `0x118` | `0x168` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x920` | `0x968` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0xc70` | `0xca0` | **`+0x30`** |
| `__DATA.__objc_ivar` | `—` | `0x2c` | **`+0x2c`** |
| `__TEXT.__cstring` | `0x309` | `0x319` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-117.125.3.0.0
+117.125.6.0.0

+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  Functions: 859
-  Symbols:   531
-  CStrings:  51
+  Functions: 872
+  Symbols:   573
+  CStrings:  53
Symbols:
+ -[AAFInkCoverageTracker .cxx_destruct]
+ -[AAFInkCoverageTracker _checkForCover:]
+ -[AAFInkCoverageTracker dealloc]
+ -[AAFInkCoverageTracker delegate]
+ -[AAFInkCoverageTracker initWithSize:touchLifetime:recoveryEnabled:]
+ -[AAFInkCoverageTracker isUncovered]
+ -[AAFInkCoverageTracker recordTouchAtPoint:]
+ -[AAFInkCoverageTracker reset]
+ -[AAFInkCoverageTracker setDelegate:]
+ -[AAFInkCoverageTracker setSize:]
+ -[AAFInkCoverageTracker setUncovered:]
+ -[AAFInkCoverageTracker size]
+ -[AAFInkCoverageTracker touchLifetime]
+ _CFAbsoluteTimeGetCurrent
+ _OBJC_CLASS_$_AAFInkCoverageTracker
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSTimer
+ _OBJC_IVAR_$_AAFInkCoverageTracker._cellHeight
+ _OBJC_IVAR_$_AAFInkCoverageTracker._cellWidth
+ _OBJC_IVAR_$_AAFInkCoverageTracker._delegate
+ _OBJC_IVAR_$_AAFInkCoverageTracker._expiryTimes
+ _OBJC_IVAR_$_AAFInkCoverageTracker._height
+ _OBJC_IVAR_$_AAFInkCoverageTracker._recoverTimer
+ _OBJC_IVAR_$_AAFInkCoverageTracker._recoveryEnabled
+ _OBJC_IVAR_$_AAFInkCoverageTracker._size
+ _OBJC_IVAR_$_AAFInkCoverageTracker._touchLifetime
+ _OBJC_IVAR_$_AAFInkCoverageTracker._uncovered
+ _OBJC_IVAR_$_AAFInkCoverageTracker._width
+ _OBJC_METACLASS_$_AAFInkCoverageTracker
+ __OBJC_$_INSTANCE_METHODS_AAFInkCoverageTracker
+ __OBJC_$_INSTANCE_VARIABLES_AAFInkCoverageTracker
+ __OBJC_$_PROP_LIST_AAFInkCoverageTracker
+ __OBJC_CLASS_RO_$_AAFInkCoverageTracker
+ __OBJC_METACLASS_RO_$_AAFInkCoverageTracker
+ _malloc_type_malloc
+ _objc_autoreleaseReturnValue
+ _objc_claimAutoreleasedReturnValue
+ _objc_destroyWeak
+ _objc_loadWeakRetained
+ _objc_release_x1
+ _objc_storeStrong
+ _objc_storeWeak
CStrings:
+ "Q"
+ "q"
```
