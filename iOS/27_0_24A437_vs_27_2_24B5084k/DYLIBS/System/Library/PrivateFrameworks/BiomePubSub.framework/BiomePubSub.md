## BiomePubSub

> `/System/Library/PrivateFrameworks/BiomePubSub.framework/BiomePubSub`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x405ec` | `0x406b0` | **`+0xc4`** |
| `__DATA_CONST.__objc_selrefs` | `0x16c8` | `0x16d0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x588c` | `0x5894` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1320` | `0x1318` | **`-0x8`** |

### Other Changes

```diff

-250.0.0.3.0
+255.0.2.0.0

-  Functions: 2348
-  Symbols:   4519
+  Functions: 2349
+  Symbols:   4520
Symbols:
+ -[BMBookmarkablePublisher validateBookmarkValue:]
+ -[BPSBuffer validateBookmarkValue:]
+ -[BPSCollect validateBookmarkValue:]
+ -[BPSFlatMap validateBookmarkValue:]
+ -[BPSMerge validateBookmarkValue:]
+ -[BPSMergeMany validateBookmarkValue:]
+ -[BPSMulticast validateBookmarkValue:]
+ -[BPSOrderedMerge validateBookmarkValue:]
+ -[BPSPassThroughSubject validateBookmarkValue:]
+ -[BPSSequence validateBookmarkValue:]
+ -[BPSWindower validateBookmarkValue:]
- -[BPSBuffer validateBookmark:]
- -[BPSCollect validateBookmark:]
- -[BPSFlatMap validateBookmark:]
- -[BPSMerge validateBookmark:]
- -[BPSMergeMany validateBookmark:]
- -[BPSMulticast validateBookmark:]
- -[BPSOrderedMerge validateBookmark:]
- -[BPSPassThroughSubject validateBookmark:]
- -[BPSSequence validateBookmark:]
- -[BPSWindower validateBookmark:]
Functions:
~ -[BMBookmarkablePublisher validateBookmark:] : 8 -> 196
- -[BPSOrderedMerge validateBookmark:]
+ -[BPSOrderedMerge validateBookmarkValue:]
+ -[BMBookmarkablePublisher validateBookmarkValue:]
```
