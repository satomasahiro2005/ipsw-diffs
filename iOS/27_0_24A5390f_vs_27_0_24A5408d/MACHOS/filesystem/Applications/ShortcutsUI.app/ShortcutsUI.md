## ShortcutsUI

> `/Applications/ShortcutsUI.app/ShortcutsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f954` | `0x1fe70` | **`+0x51c`** |
| `__TEXT.__objc_methname` | `0x85cd` | `0x87d5` | **`+0x208`** |
| `__TEXT.__objc_stubs` | `0x5960` | `0x5b00` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x1edd` | `0x1f6a` | **`+0x8d`** |
| `__DATA.__objc_selrefs` | `0x1d30` | `0x1da0` | **`+0x70`** |
| `__DATA.__objc_const` | `0x4128` | `0x4188` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x25fc` | `0x2654` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x7d8` | `0x7e8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x27c` | `0x284` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x408` | `0x410` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-5034.0.12.100.0
+5037.103.100.0.0

-  Functions: 781
-  Symbols:   257
-  CStrings:  1875
+  Functions: 788
+  Symbols:   258
+  CStrings:  1895
Symbols:
+ _OBJC_CLASS_$_WFWindowSceneManager
CStrings:
+ "%s Asked to stop tracking a nil running context (%{public}@); ignoring"
+ "%s completePersistentMode called with a nil running context; ignoring"
+ "Td,N,V_cachedMeasuredContainerWidth"
+ "Td,N,V_cachedReservedWidth"
+ "_cachedMeasuredContainerWidth"
+ "_cachedReservedWidth"
+ "_window"
+ "availableContainerWidth"
+ "cachedMeasuredContainerWidth"
+ "cachedReservedWidth"
+ "keyWindow"
+ "mainScene"
+ "platterContentSize"
+ "platterSafeAreaInsets"
+ "preferredContainerSafeAreaInsets"
+ "preferredSizeForPresentingInContainerViewOfSize:safeAreaInsets:"
+ "presentedViewFrameInContainerView:containerViewSize:safeAreaInsets:withSizeCalculation:withKeyboardObservation:ofPresentedPlatter:"
+ "safeAreaInsets"
+ "setCachedMeasuredContainerWidth:"
+ "setCachedReservedWidth:"
+ "viewIfLoaded"
- "preferredSizeForPresentingInContainerViewOfSize:"
```
