## AACCore

> `/System/Library/PrivateFrameworks/AACCore.framework/AACCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1b91` | `0x1bc7` | **`+0x36`** |
| `__AUTH_CONST.__cfstring` | `0x1700` | `0x1720` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1d8` | **`-0x8`** |
| `__TEXT.__text` | `0x1254c` | `0x12548` | **`-0x4`** |

### Other Changes

```diff

-56.0.3.0.0
+56.2.1.0.0

-  Symbols:   1505
-  CStrings:  229
+  Symbols:   1504
+  CStrings:  230
Symbols:
- _AXGuidedAccessActiveStatusDidChangeBroadcastNotification
Functions:
~ -[AEConcreteAccessibilityServerPrimitives observeGuidedAccessActiveStateChangeOnQueue:withHandler:] : 32 -> 28
CStrings:
+ "com.apple.accessibility.guidedaccess.restrictedForAAC"
```
