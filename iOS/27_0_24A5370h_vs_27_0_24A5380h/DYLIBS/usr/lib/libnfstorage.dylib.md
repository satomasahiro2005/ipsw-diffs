## libnfstorage.dylib

> `/usr/lib/libnfstorage.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7cec` | `0x8390` | **`+0x6a4`** |
| `__AUTH.__objc_data` | `0x230` | `0xf0` | **`-0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x1e0` | `0x320` | **`+0x140`** |
| `__TEXT.__cstring` | `0xd4d` | `0xdfe` | **`+0xb1`** |
| `__DATA_CONST.__const` | `0x208` | `0x230` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0x198` | `0x1b0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x268` | `0x278` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4b0` | `0x4b8` | **`+0x8`** |

### Other Changes

```diff

-370.37.0.0.0
+370.38.2.0.0

-  Functions: 60
+  Functions: 62

-  CStrings:  109
+  CStrings:  111
CStrings:
+ "-[NFStorageControllerDeveloperPresentment fetchReportsWithBundleID:teamID:error:]"
+ "-[NFStorageControllerDeveloperPresentment fetchReportsWithBundleID:teamID:error:]_block_invoke"
```
