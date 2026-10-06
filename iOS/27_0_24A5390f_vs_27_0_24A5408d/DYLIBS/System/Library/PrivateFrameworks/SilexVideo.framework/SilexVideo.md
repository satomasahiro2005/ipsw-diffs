## SilexVideo

> `/System/Library/PrivateFrameworks/SilexVideo.framework/SilexVideo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11148` | `0x11554` | **`+0x40c`** |
| `__TEXT.__gcc_except_tab` | `0x47c` | `0x444` | **`-0x38`** |
| `__TEXT.__objc_methlist` | `0x2180` | `0x21b0` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x16e0` | `0x1708` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x678` | `0x688` | **`+0x10`** |

### Other Changes

```diff

-5926.0.0.0.0
+5934.2.0.0.0

-  Functions: 603
-  Symbols:   1368
+  Functions: 607
+  Symbols:   1373
Symbols:
+ -[SVVideoPlayerViewController dismissFullScreenVideoPlayer]
+ -[SVVideoPlayerViewController embedPlayerViewController]
+ -[SVVideoPlayerViewController makePlayerViewController]
+ -[SVVideoPlayerViewController rebuildPlayerViewController]
+ GCC_except_table17
+ GCC_except_table5
+ GCC_except_table65
+ ___55-[SVVideoPlayerViewController makePlayerViewController]_block_invoke
- GCC_except_table14
- GCC_except_table61
- ___49-[SVVideoPlayerViewController initWithAudioMode:]_block_invoke
```
