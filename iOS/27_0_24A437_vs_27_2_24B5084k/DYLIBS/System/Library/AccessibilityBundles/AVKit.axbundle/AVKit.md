## AVKit

> `/System/Library/AccessibilityBundles/AVKit.axbundle/AVKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbfb4` | `0xc184` | **`+0x1d0`** |
| `__AUTH_CONST.__cfstring` | `0x3080` | `0x3120` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x270e` | `0x2781` | **`+0x73`** |
| `__AUTH_CONST.__const` | `0x220` | `0x240` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x360` | `0x380` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x788` | `0x7a0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1338` | `0x1350` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x178` | `0x180` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x538` | `0x540` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 387
-  Symbols:   1090
-  CStrings:  417
+  Functions: 390
+  Symbols:   1095
+  CStrings:  423
Symbols:
+ -[AVMobileGlassPlaybackControlButtonAccessibility setPlaybackControlButtonIconState:]
+ -[_AVFocusContainerViewAccessibility _axUnifiedPlayerControlsViewController]
+ GCC_except_table162
+ GCC_except_table164
+ GCC_except_table173
+ GCC_except_table181
+ GCC_except_table225
+ GCC_except_table263
+ GCC_except_table300
+ GCC_except_table313
+ GCC_except_table327
+ GCC_except_table333
+ GCC_except_table347
+ GCC_except_table353
+ GCC_except_table372
+ ___104-[AVUnifiedPlayerPlaybackControlsViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_2
+ ___NSArray0__struct
+ ___block_descriptor_32_e15_B32?08Q16^B24l
- GCC_except_table161
- GCC_except_table163
- GCC_except_table172
- GCC_except_table180
- GCC_except_table224
- GCC_except_table262
- GCC_except_table298
- GCC_except_table311
- GCC_except_table325
- GCC_except_table331
- GCC_except_table345
- GCC_except_table351
- GCC_except_table369
Functions:
~ +[AVUnifiedPlayerPlaybackControlsViewControllerAccessibility _accessibilityPerformValidations:] : 296 -> 328
~ ___104-[AVUnifiedPlayerPlaybackControlsViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke : 276 -> 336
+ ___104-[AVUnifiedPlayerPlaybackControlsViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_2
~ +[AVMobileGlassPlaybackControlButtonAccessibility _accessibilityPerformValidations:] : 72 -> 172
~ -[AVMobileGlassPlaybackControlButtonAccessibility setImageName:] : 208 -> 216
+ -[AVMobileGlassPlaybackControlButtonAccessibility setPlaybackControlButtonIconState:]
+ -[_AVFocusContainerViewAccessibility _axUnifiedPlayerControlsViewController]
~ -[_AVFocusContainerViewAccessibility _accessibilityShouldIncludeMediaDescriptionsRotor] : 128 -> 96
CStrings:
+ "B32@?0@8Q16^B24"
+ "pause"
+ "play"
+ "playbackControlButtonIconState"
+ "playbackControlsState"
+ "setPlaybackControlButtonIconState:"
```
