## CarPlayWallpaper

> `/Applications/CarPlayWallpaper.app/CarPlayWallpaper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8f34` | `0x906c` | **`+0x138`** |
| `__TEXT.__objc_methname` | `0x1ed2` | `0x1f12` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1180` | `0x11c0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x42c` | `0x45c` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x7a8` | `0x7b8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xa04` | `0xa0c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x308` | `0x310` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-574.2.0.0.0
+577.2.0.0.0

-  Functions: 249
+  Functions: 250

-  CStrings:  477
+  CStrings:  480
CStrings:
+ "Wallpaper appearance changed -> style: %{public}@"
+ "_updateWallpaperImageRegeneratingCacheOnMiss:"
+ "resolveWallpaper:options:"
```
