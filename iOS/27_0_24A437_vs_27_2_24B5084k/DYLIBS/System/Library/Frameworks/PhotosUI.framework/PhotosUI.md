## PhotosUI

> `/System/Library/Frameworks/PhotosUI.framework/PhotosUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x432a0` | `0x43358` | **`+0xb8`** |
| `__TEXT.__eh_frame` | `0x73c` | `0x70c` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x6fb8` | `0x6fc8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2160` | `0x2170` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3ec4` | `0x3ed4` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa40` | `0xa38` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x620` | `0x628` | **`+0x8`** |

### Other Changes

```diff

-912.0.235.0.0
+916.40.110.0.0

-  Functions: 3007
-  Symbols:   2945
+  Functions: 3008
+  Symbols:   2946
Symbols:
+ -[_PHPickerSuggestionGroup sortsAssetsByCaptureDate]
+ GCC_except_table866
+ GCC_except_table876
+ GCC_except_table879
+ GCC_except_table881
+ GCC_except_table960
- GCC_except_table865
- GCC_except_table875
- GCC_except_table878
- GCC_except_table880
- GCC_except_table959
```
