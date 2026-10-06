## AVKit

> `/System/Library/AccessibilityBundles/AVKit.axbundle/AVKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc184` | `0xc730` | **`+0x5ac`** |
| `__AUTH.__objc_data` | `0xbe0` | `0xb40` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x3120` | `0x31c0` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x1450` | `0x14f0` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x240` | `0x260` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x7a0` | `0x7c0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1350` | `0x1370` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2781` | `0x279d` | **`+0x1c`** |
| `__TEXT.__unwind_info` | `0x540` | `0x550` | **`+0x10`** |
| `__TEXT.__ustring` | `0x4` | `0xc` | **`+0x8`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  Functions: 390
-  Symbols:   1095
-  CStrings:  423
+  Functions: 396
+  Symbols:   1101
+  CStrings:  428
Symbols:
+ -[AVNowPlayingTransportBarAccessibility _axSpokenRemainingTime]
+ -[AVPlayerLayerViewAccessibility _axPlayerViewController]
+ -[AVPlayerLayerViewAccessibility accessibilityHint]
+ GCC_except_table105
+ GCC_except_table153
+ GCC_except_table166
+ GCC_except_table168
+ GCC_except_table177
+ GCC_except_table185
+ GCC_except_table229
+ GCC_except_table267
+ GCC_except_table306
+ GCC_except_table319
+ GCC_except_table339
+ GCC_except_table359
+ GCC_except_table378
+ GCC_except_table65
+ GCC_except_table92
+ _AXAVKitSpokenDurationForTimeText
+ _AXAVKitTransportBarDisplaysDates
+ ___57-[AVPlayerLayerViewAccessibility _axPlayerViewController]_block_invoke
- GCC_except_table104
- GCC_except_table149
- GCC_except_table162
- GCC_except_table164
- GCC_except_table173
- GCC_except_table181
- GCC_except_table225
- GCC_except_table263
- GCC_except_table300
- GCC_except_table313
- GCC_except_table327
- GCC_except_table347
- GCC_except_table372
- GCC_except_table64
- GCC_except_table91
CStrings:
+ "-− "
+ "endDate"
+ "isLive"
+ "live"
+ "startDate"
+ "tv.player.paused"
- "remainingTimeLabel"
```
