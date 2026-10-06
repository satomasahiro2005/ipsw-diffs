## WiFiKitUI

> `/System/Library/PrivateFrameworks/WiFiKitUI.framework/WiFiKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9452c` | `0x94818` | **`+0x2ec`** |
| `__AUTH_CONST.__cfstring` | `0x61e0` | `0x6160` | **`-0x80`** |
| `__TEXT.__oslogstring` | `0x337d` | `0x33bd` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x12600` | `0x12630` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ce8` | `0x3d18` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x6600` | `0x6620` | **`+0x20`** |
| `__TEXT.__const` | `0x2b24` | `0x2b14` | **`-0x10`** |
| `__TEXT.__cstring` | `0x7d30` | `0x7d20` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1b90` | `0x1ba0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x8d8` | `0x8e0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x720` | `0x724` | **`+0x4`** |

### Other Changes

```diff

-1205.81.4.2.0
+1207.6.0.0.0

+  - /System/Library/Frameworks/Symbols.framework/Symbols

-  Functions: 3377
-  Symbols:   3976
-  CStrings:  1346
+  Functions: 3380
+  Symbols:   3981
+  CStrings:  1343
Symbols:
+ -[WFBuddyViewController _setUpHeaderSymbolView]
+ -[WFBuddyViewController didDrawOnHeaderSymbol]
+ -[WFBuddyViewController headerSymbolView]
+ -[WFBuddyViewController setDidDrawOnHeaderSymbol:]
+ -[WFBuddyViewController setHeaderSymbolView:]
+ GCC_except_table22
+ _OBJC_CLASS_$_NSSymbolDisappearEffect
+ _OBJC_CLASS_$_NSSymbolDrawOnEffect
+ _OBJC_CLASS_$_NSSymbolEffectOptions
+ _OBJC_IVAR_$_WFBuddyViewController._didDrawOnHeaderSymbol
+ _OBJC_IVAR_$_WFBuddyViewController._headerSymbolView
- -[WFBuddyViewController animationController]
- -[WFBuddyViewController setAnimationController:]
- GCC_except_table8
- _OBJC_CLASS_$_OBAnimationController
- _OBJC_CLASS_$_OBAnimationState
- _OBJC_IVAR_$_WFBuddyViewController._animationController
CStrings:
+ "Buddy header has no custom icon container, leaving the header symbol unset"
- "State 1"
- "State 2"
- "WIFI"
- "ca"
```
