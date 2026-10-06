## AccessibilityUIService

> `/System/Library/PrivateFrameworks/AccessibilityUIService.framework/AccessibilityUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f61c` | `0x1fc60` | **`+0x644`** |
| `__TEXT.__oslogstring` | `0x16eb` | `0x1784` | **`+0x99`** |
| `__AUTH_CONST.__objc_const` | `0x27f0` | `0x2880` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x1870` | `0x18d8` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x1c14` | `0x1c64` | **`+0x50`** |
| `__TEXT.__cstring` | `0x152e` | `0x1561` | **`+0x33`** |
| `__DATA_CONST.__const` | `0x8f8` | `0x920` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x488` | `0x4b0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x8a0` | `0x8c8` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x18c` | `0x19c` | **`+0x10`** |
| `__TEXT.__const` | `0x858` | `0x868` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x888` | `0x890` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x508` | `0x510` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 740
-  Symbols:   1470
-  CStrings:  220
+  Functions: 749
+  Symbols:   1488
+  CStrings:  222
Symbols:
+ -[AXUIDisplayManager _activateActiveDisplayObserverIfNeeded]
+ -[AXUIDisplayManager _handleActiveInterfaceOrientationState:]
+ -[AXUIDisplayManager activeDisplayID]
+ -[AXUIDisplayManager addActiveDisplayObserver:]
+ -[AXUIDisplayManager removeActiveDisplayObserver:]
+ -[AXUIDisplayManager setActiveDisplayID:]
+ -[AXUIDisplayManager shouldPresentUIForWindowScene:]
+ GCC_except_table328
+ GCC_except_table329
+ GCC_except_table338
+ GCC_except_table339
+ GCC_except_table357
+ GCC_except_table358
+ GCC_except_table365
+ GCC_except_table373
+ GCC_except_table378
+ GCC_except_table394
+ GCC_except_table426
+ GCC_except_table428
+ GCC_except_table445
+ _AXDeviceIsViridian
+ _OBJC_CLASS_$_FBSActiveInterfaceOrientationObserver
+ _OBJC_IVAR_$_AXUIDisplayManager._activeDisplayID
+ _OBJC_IVAR_$_AXUIDisplayManager._activeDisplayObservers
+ _OBJC_IVAR_$_AXUIDisplayManager._activeInterfaceOrientationObserver
+ _OBJC_IVAR_$_AXUIDisplayManager._hasResolvedActiveDisplay
+ ___60-[AXUIDisplayManager _activateActiveDisplayObserverIfNeeded]_block_invoke
+ ___60-[AXUIDisplayManager _activateActiveDisplayObserverIfNeeded]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e50_v16?0"FBSActiveInterfaceOrientationStateUpdate"8lw32l8
- GCC_except_table326
- GCC_except_table327
- GCC_except_table348
- GCC_except_table349
- GCC_except_table356
- GCC_except_table364
- GCC_except_table369
- GCC_except_table385
- GCC_except_table417
- GCC_except_table419
- GCC_except_table436
CStrings:
+ "[ActiveDisplay] Active display changed to displayID=%u; notifying %lu observer(s)."
+ "[ActiveDisplay] FBS delivered displayID=%u (current=%u, resolved=%d)."
+ "v16@?0@\"FBSActiveInterfaceOrientationStateUpdate\"8"
- "\x81"
```
