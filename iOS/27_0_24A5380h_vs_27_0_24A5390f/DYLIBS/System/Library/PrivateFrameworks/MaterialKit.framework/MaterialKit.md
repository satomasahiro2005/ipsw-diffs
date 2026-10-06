## MaterialKit

> `/System/Library/PrivateFrameworks/MaterialKit.framework/MaterialKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x370` | `—` | **`-0x370`** |
| `__DATA_DIRTY.__objc_data` | `0x280` | `0x5f0` | **`+0x370`** |
| `__TEXT.__text` | `0xe580` | `0xe578` | **`-0x8`** |

### Other Changes

```diff

-223.0.0.0.0
+224.0.0.0.0

-  Symbols:   1024
+  Symbols:   1026
Symbols:
+ __UIClamp
+ __UILerp
Functions:
~ -[MTMaterialView setWeighting:] : 216 -> 224
~ ___40-[MTMaterialView _setupAlphaTransformer]_block_invoke.77 : 48 -> 32
```
