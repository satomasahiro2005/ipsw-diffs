## PromotedContentUI

> `/System/Library/PrivateFrameworks/PromotedContentUI.framework/PromotedContentUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19602c` | `0x1960a0` | **`+0x74`** |
| `__TEXT.__const` | `0xe984` | `0xe974` | **`-0x10`** |
| `__TEXT.__cstring` | `0x7aa1` | `0x7ab1` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d60` | `0x1d68` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4bc8` | `0x4bd0` | **`+0x8`** |

### Other Changes

```diff

-557.1.32.0.0
+557.1.33.0.0
Functions:
~ sub_1c264d4ac -> sub_1c26654ac : 16 -> 12
~ sub_1c264d4bc -> sub_1c26654b8 : 12 -> 16
~ sub_1c2683e20 -> sub_1c269be20 : 368 -> 480
~ sub_1c2684b40 -> sub_1c269cbb0 : 848 -> 852
CStrings:
+ "Checking for isScrolling - isDragging: %d, isDecelerating: %d, isTracking: %d, touchType: %ld"
- "Checking for isScrolling - isDragging: %d, isDecelerating: %d, isTracking: %d"
```
