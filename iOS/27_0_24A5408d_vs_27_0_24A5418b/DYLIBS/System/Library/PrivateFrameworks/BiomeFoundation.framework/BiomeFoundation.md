## BiomeFoundation

> `/System/Library/PrivateFrameworks/BiomeFoundation.framework/BiomeFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34808` | `0x3485c` | **`+0x54`** |
| `__DATA_CONST.__objc_selrefs` | `0x18b8` | `0x18c0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2a5c` | `0x2a64` | **`+0x8`** |

### Other Changes

```diff

-250.0.0.1.0
+250.0.0.3.0

-  Functions: 1228
-  Symbols:   2199
+  Functions: 1229
+  Symbols:   2200
Symbols:
+ +[BMVanillaContainer biomeDirectoryURLForContainerPath:]
Functions:
~ -[BMResourceContainerManager _standardDataVaultContainerForResource:] : 140 -> 144
~ +[BMVanillaContainer containerForPersonaIdentifier:error:] : 684 -> 656
+ +[BMVanillaContainer biomeDirectoryURLForContainerPath:]
```
