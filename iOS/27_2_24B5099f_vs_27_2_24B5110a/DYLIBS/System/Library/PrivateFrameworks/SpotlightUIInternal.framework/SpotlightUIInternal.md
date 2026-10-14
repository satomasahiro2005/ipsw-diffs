## SpotlightUIInternal

> `/System/Library/PrivateFrameworks/SpotlightUIInternal.framework/SpotlightUIInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x521fc` | `0x525c8` | **`+0x3cc`** |
| `__TEXT.__oslogstring` | `0x1476` | `0x14a6` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x4368` | `0x4390` | **`+0x28`** |
| `__DATA.__data` | `0x1720` | `0x1740` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xab0` | `0xac8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x5d78` | `0x5d90` | **`+0x18`** |
| `__TEXT.__const` | `0x1498` | `0x14a8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x16f8` | `0x1708` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2d0` | `0x2dc` | **`+0xc`** |

### Other Changes

```diff

-250.1.9.0.0
+250.1.12.200.0

-  Functions: 2108
-  Symbols:   3288
-  CStrings:  375
+  Functions: 2114
+  Symbols:   3290
+  CStrings:  376
Symbols:
+ -[SPUITextView _shouldAcceptAutocorrection]
+ -[SPUITextView spui_currentInputModeDidChange]
CStrings:
+ "shouldBeEnabled: %@, selectedItem: %@, isAskSiri: %@"
```
