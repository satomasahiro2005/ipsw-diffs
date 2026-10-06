## SpringBoard

> `/System/Library/AccessibilityBundles/SpringBoard.axbundle/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xd70` | `0xb90` | **`-0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0x50f0` | `0x52d0` | **`+0x1e0`** |
| `__TEXT.__text` | `0x3a764` | `0x3a738` | **`-0x2c`** |
| `__AUTH_CONST.__const` | `0x790` | `0x770` | **`-0x20`** |
| `__TEXT.__cstring` | `0xa66e` | `0xa657` | **`-0x17`** |
| `__DATA_CONST.__objc_selrefs` | `0x2628` | `0x2630` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x4d04` | `0x4d0c` | **`+0x8`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0
Symbols:
+ -[SpringBoardAccessibility _accessibilityElementsForStatusBar:sorted:]
+ ___70-[SpringBoardAccessibility _accessibilityElementsForStatusBar:sorted:]_block_invoke
+ ___70-[SpringBoardAccessibility _accessibilityElementsForStatusBar:sorted:]_block_invoke_2
+ ___70-[SpringBoardAccessibility _accessibilityElementsForStatusBar:sorted:]_block_invoke_3
- ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_6
- ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_7
- ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_8
- ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_9
Functions:
~ +[SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility _accessibilityPerformValidations:] : 220 -> 244
~ -[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:] : 3816 -> 3720
~ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_4 : 436 -> 272
~ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_5 : 96 -> 84
~ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_6 -> -[SpringBoardAccessibility _accessibilityElementsForStatusBar:sorted:] : 8 -> 284
~ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_7 -> ___70-[SpringBoardAccessibility _accessibilityElementsForStatusBar:sorted:]_block_invoke : 16 -> 196
~ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_8 -> ___70-[SpringBoardAccessibility _accessibilityElementsForStatusBar:sorted:]_block_invoke_2 : 272 -> 96
~ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_9 -> ___70-[SpringBoardAccessibility _accessibilityElementsForStatusBar:sorted:]_block_invoke_3 : 84 -> 8
CStrings:
+ "SBSceneView"
- "AXStatusBarHasSyntheticElementsKey"
```
