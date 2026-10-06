## ProductKit

> `/System/Library/PrivateFrameworks/ProductKit.framework/ProductKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6cae0` | `0x6d30c` | **`+0x82c`** |
| `__TEXT.__oslogstring` | `0x1d03` | `0x1df3` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x1598` | `0x1678` | **`+0xe0`** |
| `__TEXT.__swift5_reflstr` | `0x1da9` | `0x1e09` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x2618` | `0x266c` | **`+0x54`** |
| `__DATA.__data` | `0x18c0` | `0x1908` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x4ea0` | `0x4e60` | **`-0x40`** |
| `__TEXT.__const` | `0x63ac` | `0x63ec` | **`+0x40`** |
| `__AUTH.__objc_data` | `0x8b0` | `0x8e8` | **`+0x38`** |
| `__TEXT.__cstring` | `0x23e4` | `0x23c4` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x1d08` | `0x1cf0` | **`-0x18`** |
| `__TEXT.__swift5_capture` | `0x35c` | `0x34c` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x838` | `0x840` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x18e4` | `0x18ec` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x18c2` | `0x18c8` | **`+0x6`** |

### Other Changes

```diff

-152.100.1.0.0
+155.100.1.2.3

-  Functions: 2236
-  Symbols:   1218
-  CStrings:  632
+  Functions: 2235
+  Symbols:   1219
+  CStrings:  635
Symbols:
+ -[PKMediaPlayerView handleBoundaryTimeObserverForMediaItem:currentTime:]
+ _CMTimeCopyDescription
+ _symbolic SdSg
- -[PKMediaPlayerView handleBoundaryTimeObserverForMediaItem:]
- _notify_register_dispatch
CStrings:
+ "%s mediaItem: %@, current time %@"
+ "-[PKMediaPlayerView handleBoundaryTimeObserverForMediaItem:currentTime:]"
+ "Seeking to time: %@"
+ "Skipping sceneTime update: non-finite time for %s"
+ "Skipping video plane size update: invalid original size (%f, %f)"
+ "Skipping video plane size update: non-finite size (%f, %f)"
- "-[PKMediaPlayerView handleBoundaryTimeObserverForMediaItem:]"
- "Seeking to time"
- "com.apple.ProductKit.updateVideoPlaneSize"
```
