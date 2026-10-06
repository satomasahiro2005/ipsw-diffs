## CoverSheetKit

> `/System/Library/PrivateFrameworks/CoverSheetKit.framework/CoverSheetKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b9ac` | `0x3bf1c` | **`+0x570`** |
| `__TEXT.__oslogstring` | `0x555` | `0x855` | **`+0x300`** |
| `__AUTH_CONST.__objc_const` | `0x4fa8` | `0x4fc8` | **`+0x20`** |
| `__TEXT.__const` | `0x243c` | `0x245c` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f70` | `0x1f80` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x788` | `0x778` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x6a8` | `0x6a0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x11d8` | `0x11d0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x2cc` | `0x2d0` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-159.2.1.0.0
+159.2.4.0.0

-  Functions: 1763
+  Functions: 1762

-  CStrings:  121
+  CStrings:  124
Symbols:
+ _OBJC_IVAR_$_CSProminentTextElementView._lastLoggedLabelRect
- ___57-[CSProminentTextElementView insertPrefixViews:animated:]_block_invoke_4
Functions:
~ -[CSProminentTimeView layoutSubviews] : 868 -> 872
~ -[CSProminentTextElementView layoutSubviews] : 356 -> 1104
~ -[CSProminentDisplayView layoutSubviews] : 2092 -> 2724
- -[CSProminentDisplayView layoutSubviews].cold.1
~ -[CSProminentDisplayViewController setDateTimeAlignment:] : 260 -> 376
~ ___57-[CSProminentTextElementView insertPrefixViews:animated:]_block_invoke : 472 -> 572
CStrings:
+ "CSProminentTimeView textLabel is not centered with timeViewFrame: %{public}@, textLabel frame: %{public}@, measurementFont: %{public}@, labelSize: %{public}@."
+ "Setting date and time textAlignment to: %lu, reachedTimeView: %{bool}u, reachedSubtitleView: %{bool}u"
+ "Skipping setting time frame due to applied transform: %{public}@"
+ "Subtitle box is not centered in prominentDisplayView. boundingRect: %{public}@, subtitleFrame: %{public}@, appliedFrame: %{public}@, usesEditingLayout: %{bool}u."
+ "Text element is switching to stack layout permanently. elementType: %lu, bounds: %{public}@."
+ "Text element label is not centered despite center alignment. elementType: %lu, bounds: %{public}@, label: %{public}@, measured: %{public}@, contentIsStack: %{bool}u, stack: %{public}@, leadingSpacer: %{public}@, contentStack: %{public}@, trailingSpacer: %{public}@, font: %{public}@, contentSizeCategory: %{public}@, textLength: %lu, text: %@."
+ "Time is not centered in prominentDisplayView, boundingRect: %{public}@, timeFrame: %{public}@, timeView frame: %{public}@, adaptsTextHeight: %{bool}u, calculated textHeight: %f, baseFont: %{public}@."
- "CSProminentTimeView textLabel is not centered with timeViewFrame: %@, textLabel frame: %@, measurementFont: %@, labelSize: %@."
- "Setting date and time textAlignment to: %lu"
- "Skipping setting time frame due to applied transform: %@"
- "Time is not centered in prominentDisplayView, timeView frame: %@, adaptsTextHeight: %{bool}u, calculated textHeight: %f, baseFont: %@."
```
