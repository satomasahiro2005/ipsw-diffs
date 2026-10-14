## WritingToolsUI

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/WritingToolsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d61c` | `0x6e178` | **`+0xb5c`** |
| `__TEXT.__oslogstring` | `0x21ed` | `0x23cd` | **`+0x1e0`** |
| `__DATA_CONST.__const` | `0xe48` | `0xeb8` | **`+0x70`** |
| `__DATA.__data` | `0x1ef0` | `0x1f38` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x1d08` | `0x1d50` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x2108` | `0x2148` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x6a28` | `0x6a68` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3180` | `0x31a8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x4dcc` | `0x4df4` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xa48` | `0xa68` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3777` | `0x3797` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xdc8` | `0xde0` | **`+0x18`** |
| `__DATA_CONST.__objc_catlist` | `0x28` | `0x30` | **`+0x8`** |

### Other Changes

```diff

-151.1.9.0.0
+151.1.11.0.0

-  Functions: 3035
-  Symbols:   3227
-  CStrings:  562
+  Functions: 3051
+  Symbols:   3239
+  CStrings:  571
Symbols:
+ -[NSUndoManager(WTTurnTracking) wt_registerTurnWithHandler:]
+ -[WTWritingToolsController _registerUndoTrackingTurnOnUndoManager:]
+ GCC_except_table124
+ GCC_except_table130
+ GCC_except_table167
+ GCC_except_table183
+ GCC_except_table186
+ GCC_except_table230
+ GCC_except_table239
+ GCC_except_table241
+ GCC_except_table76
+ GCC_except_table78
+ GCC_except_table85
+ _OBJC_CLASS_$_NSUndoManager
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSUndoManager_$_WTTurnTracking
+ __OBJC_$_CATEGORY_NSUndoManager_$_WTTurnTracking
+ ___48-[WTWritingToolsController beginTextPlaceholder]_block_invoke
+ ___60-[NSUndoManager(WTTurnTracking) wt_registerTurnWithHandler:]_block_invoke
+ ___65-[WTWritingToolsController didBeginWritingToolsSession:contexts:]_block_invoke
+ ___67-[WTWritingToolsController _registerUndoTrackingTurnOnUndoManager:]_block_invoke
+ ___block_descriptor_32_e8_v16?08l
+ ___block_descriptor_40_e8_32bs_e23_v16?0"NSUndoManager"8ls32l8
+ ___block_descriptor_40_e8_32w_e8_v12?0B8lw32l8
- GCC_except_table120
- GCC_except_table126
- GCC_except_table163
- GCC_except_table179
- GCC_except_table182
- GCC_except_table226
- GCC_except_table233
- GCC_except_table235
- GCC_except_table74
- GCC_except_table82
- _swift_retain_x27
CStrings:
+ "_registerUndoTrackingTurnOnUndoManager: %@"
+ "cancel-undo action fired for Proofread review: hasPendingSuggestions=%s"
+ "cancel-undo action fired for the generating placeholder"
+ "registering cancel-undo action for pending Proofread review on undoManager=%@"
+ "registering cancel-undo action for the generating placeholder on undoManager=%@"
+ "undo tracking turn fired: isUndo=%s remainingUndoCount=%lu remainingRedoCount=%lu"
+ "undo tracking turn reconciled: remainingUndoCount=%lu remainingRedoCount=%lu"
+ "v16@?0@\"NSUndoManager\"8"
+ "v16@?0@8"
```
