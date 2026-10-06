## CoreIMS

> `/System/Library/PrivateFrameworks/CoreIMS.framework/CoreIMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x50594` | `0x506d4` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x41c4` | `0x41f9` | **`+0x35`** |
| `__TEXT.__const` | `0x4ea0` | `0x4ec0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x50a8` | `0x50c8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x47f4` | `0x480c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2250` | `0x2258` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1170` | `0x1178` | **`+0x8`** |

### Other Changes

```diff

-124.0.4.0.0
+124.40.1.0.0

-  Functions: 1627
-  Symbols:   3076
+  Functions: 1628
+  Symbols:   3078
Symbols:
+ +[IMSRuntimeMaskRenderer minimumControlPointsForInterpolation:]
+ __OBJC_$_CLASS_METHODS_IMSRuntimeMaskRenderer
CStrings:
+ "[Mask] Mask Data is invalid, return full mask: interpolation %ld requires >= %lu control points (left %lu, right %lu)"
- "[Mask] Mask Data is invalid, return full mask: left %d, right %d"
```
