## BackBoard

> `/System/Library/AccessibilityBundles/BackBoard.axbundle/BackBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27d9c` | `0x27e4c` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x1e8a` | `0x1e62` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bc8` | `0x1bd8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x6a0` | `0x6a8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd10` | `0xd08` | **`-0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 1018
+  Functions: 1017

-  CStrings:  487
+  CStrings:  486
Symbols:
+ -[AXBAccessibilityManager _sendPressFingerEvent:location:force:flags:contextId:secureName:displayId:fingerIndex:]
+ -[AXBAccessibilityManager simulatePressAtPoint:withContextId:withDelay:withForce:withSecureName:displayId:fingerIndex:]
+ GCC_except_table520
+ GCC_except_table566
+ GCC_except_table595
+ GCC_except_table612
+ GCC_except_table625
+ GCC_except_table637
+ GCC_except_table670
+ GCC_except_table708
+ GCC_except_table722
+ GCC_except_table796
+ _kAXSimulatePressAtPointActionKeyDisplayID
- -[AXBAccessibilityManager _sendPressFingerEvent:location:force:flags:contextId:secureName:fingerIndex:]
- -[AXBAccessibilityManager simulatePressAtPoint:withContextId:withDelay:withForce:withSecureName:fingerIndex:]
- GCC_except_table521
- GCC_except_table567
- GCC_except_table596
- GCC_except_table613
- GCC_except_table626
- GCC_except_table638
- GCC_except_table671
- GCC_except_table709
- GCC_except_table723
- GCC_except_table797
- __deviceInStateRequiringVoiceOverTripleClickInBuddy
CStrings:
- "Buddy running: %d, LoginUI: %d, IOD: %d"
```
