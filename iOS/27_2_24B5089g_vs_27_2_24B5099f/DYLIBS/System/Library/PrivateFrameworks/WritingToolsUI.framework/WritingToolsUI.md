## WritingToolsUI

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/WritingToolsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ce94` | `0x6d61c` | **`+0x788`** |
| `__AUTH_CONST.__objc_const` | `0x6968` | `0x6a28` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x212d` | `0x21ed` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x4d44` | `0x4dcc` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x3120` | `0x3180` | **`+0x60`** |
| `__TEXT.__cstring` | `0x3737` | `0x3777` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0xe3c` | `0xe7c` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0xcbc` | `0xce0` | **`+0x24`** |
| `__AUTH.__objc_data` | `0x14b0` | `0x14d0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x20f0` | `0x2108` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0xfec` | `0x1004` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xe38` | `0xe48` | **`+0x10`** |
| `__TEXT.__const` | `0x30a4` | `0x30b4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1cf8` | `0x1d08` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x384` | `0x390` | **`+0xc`** |
| `__DATA.__common` | `0x118` | `0x120` | **`+0x8`** |

### Other Changes

```diff

-151.1.6.0.0
+151.1.9.0.0

-  Functions: 3015
-  Symbols:   3216
-  CStrings:  560
+  Functions: 3035
+  Symbols:   3227
+  CStrings:  562
Symbols:
+ -[WTMainPopoverViewController adaptivePresentationStyleForPresentationController:traitCollection:]
+ -[WTWritingToolsController _targetIsWebKitTextInput]
+ -[WTWritingToolsController _targetPrefersLimitedUI]
+ -[WTWritingToolsController canPerformRequestedToolOnCurrentSession]
+ -[_WTReplaceTextEffect clipsToDestinationRect]
+ -[_WTReplaceTextEffect setClipsToDestinationRect:]
+ -[_WTTextEffectView hasManagedFrame]
+ -[_WTTextEffectView replaceSourceEffect]
+ -[_WTTextEffectView setHasManagedFrame:]
+ -[_WTTextEffectView setReplaceSourceEffect:]
+ GCC_except_table10
+ GCC_except_table120
+ GCC_except_table126
+ GCC_except_table163
+ GCC_except_table179
+ GCC_except_table182
+ GCC_except_table226
+ GCC_except_table233
+ GCC_except_table235
+ GCC_except_table237
+ GCC_except_table82
+ _OBJC_IVAR_$__WTReplaceTextEffect._clipsToDestinationRect
+ _OBJC_IVAR_$__WTTextEffectView._hasManagedFrame
+ _OBJC_IVAR_$__WTTextEffectView._replaceSourceEffect
+ _keypath_get.30Tm
+ _keypath_get.32Tm
+ _keypath_get.40Tm
+ _keypath_get.52Tm
+ _keypath_set.33Tm
- GCC_except_table119
- GCC_except_table125
- GCC_except_table162
- GCC_except_table178
- GCC_except_table181
- GCC_except_table223
- GCC_except_table230
- GCC_except_table232
- GCC_except_table234
- GCC_except_table62
- GCC_except_table64
- GCC_except_table68
- GCC_except_table81
- _keypath_get.29Tm
- _keypath_get.31Tm
- _keypath_get.39Tm
- _keypath_get.51Tm
- _keypath_set.32Tm
CStrings:
+ "DebugForceUnsafeOutput"
+ "startWritingTools requestedTool=%ld isWritingToolsActive=%d precomputedLen=%lu replacesExisting=%d"
+ "startupOptions: editable=%d wantsInlineEditing=%d targetPrefersLimitedUI=%d isWebKitView=%d precomputedLen=%lu"
+ "targetPrefersLimitedUI"
- "C"
- "startWritingTools"
```
