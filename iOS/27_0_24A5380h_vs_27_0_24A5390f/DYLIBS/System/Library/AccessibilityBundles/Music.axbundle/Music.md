## Music

> `/System/Library/AccessibilityBundles/Music.axbundle/Music`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc458` | `0xc4dc` | **`+0x84`** |
| `__TEXT.__cstring` | `0x29b8` | `0x29de` | **`+0x26`** |
| `__AUTH_CONST.__cfstring` | `0x3660` | `0x3680` | **`+0x20`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Symbols:   1039
-  CStrings:  485
+  Symbols:   1040
+  CStrings:  486
Symbols:
+ -[SyncedLyricsLineViewAccessibility _despacitoAccessibilityElements]
+ _NSStringFromClass
+ ___68-[SyncedLyricsLineViewAccessibility _despacitoAccessibilityElements]_block_invoke
+ ___68-[SyncedLyricsLineViewAccessibility _despacitoAccessibilityElements]_block_invoke_2
+ ___68-[SyncedLyricsLineViewAccessibility _despacitoAccessibilityElements]_block_invoke_3
+ ___68-[SyncedLyricsLineViewAccessibility _despacitoAccessibilityElements]_block_invoke_4
+ ___68-[SyncedLyricsLineViewAccessibility _despacitoAccessibilityElements]_block_invoke_5
+ ___68-[SyncedLyricsLineViewAccessibility _despacitoAccessibilityElements]_block_invoke_6
+ ___68-[SyncedLyricsLineViewAccessibility _despacitoAccessibilityElements]_block_invoke_7
- -[SyncedLyricsLineViewAccessibility _despacityAccessibilityElements]
- ___68-[SyncedLyricsLineViewAccessibility _despacityAccessibilityElements]_block_invoke
- ___68-[SyncedLyricsLineViewAccessibility _despacityAccessibilityElements]_block_invoke_2
- ___68-[SyncedLyricsLineViewAccessibility _despacityAccessibilityElements]_block_invoke_3
- ___68-[SyncedLyricsLineViewAccessibility _despacityAccessibilityElements]_block_invoke_4
- ___68-[SyncedLyricsLineViewAccessibility _despacityAccessibilityElements]_block_invoke_5
- ___68-[SyncedLyricsLineViewAccessibility _despacityAccessibilityElements]_block_invoke_6
- ___68-[SyncedLyricsLineViewAccessibility _despacityAccessibilityElements]_block_invoke_7
Functions:
~ -[SyncedLyricsLineViewAccessibility accessibilityElements] : 220 -> 352
CStrings:
+ "AXSyncedLyricsCachedContentLayerClass"
```
