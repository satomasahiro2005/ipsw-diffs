## DoubleAgent

> `/System/Library/PrivateFrameworks/DoubleAgent.framework/DoubleAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d14` | `0x3d70` | **`+0x5c`** |
| `__AUTH_CONST.__auth_got` | `0x168` | `0x160` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x128` | `0x120` | **`-0x8`** |

### Other Changes

```diff

-  Symbols:   180
+  Symbols:   179
Symbols:
- _objc_release_x28
Functions:
~ -[AppleDoubleParser lookupXattrNamed:reply:] : 464 -> 476
~ -[AppleDoubleParser listXattrs:] : 616 -> 624
~ -[AppleDoubleParser allocateXattrNamed:sized:how:reply:] : 2040 -> 2048
~ -[AppleDoubleParser removeXattrNamed:reply:] : 1748 -> 1768
~ -[AppleDoubleParser swapFileHeader] : 100 -> 120
~ -[AppleDoubleParser swapAttrHeader:] : 268 -> 272
~ -[AppleDoubleParser parseFileHeader:] : 372 -> 376
~ -[AppleDoubleParser parseFinderInfoAndResourceFork:] : 692 -> 704
~ -[AppleDoubleParser parseAttrHeader:] : 616 -> 620
```
