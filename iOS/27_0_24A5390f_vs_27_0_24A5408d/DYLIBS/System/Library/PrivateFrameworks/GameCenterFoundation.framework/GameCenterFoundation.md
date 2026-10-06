## GameCenterFoundation

> `/System/Library/PrivateFrameworks/GameCenterFoundation.framework/GameCenterFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x172850` | `0x172ee8` | **`+0x698`** |
| `__TEXT.__oslogstring` | `0xde1b` | `0xdebb` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x6ce8` | `0x6d08` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x121dc` | `0x121fc` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8560` | `0x8578` | **`+0x18`** |
| `__DATA.__bss` | `0x82d0` | `0x82e0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x10f8` | `0x1108` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x67c8` | `0x67d8` | **`+0x10`** |

### Other Changes

```diff

-821.0.20.0.0
+821.0.25.0.0

-  Functions: 11219
-  Symbols:   12313
-  CStrings:  4202
+  Functions: 11225
+  Symbols:   12320
+  CStrings:  4204
Symbols:
+ +[GKLocalPlayer _gkPromotedLocalPlayerInternalFromInternal:]
+ -[GKLocalPlayer setInternal:]
+ GCC_except_table38
+ GCC_except_table53
+ GCC_except_table67
+ _GKCanonicalImageCacheRoot.once
+ _GKCanonicalImageCacheRoot.sCanonicalRoot
+ _GKPathInsideImageCache
+ _NSURLCanonicalPathKey
+ _NSURLIsSymbolicLinkKey
+ ___GKCanonicalImageCacheRoot_block_invoke
- GCC_except_table51
- GCC_except_table65
- GCC_except_table88
- GCC_except_table97
CStrings:
+ "GKLocalPlayer.setInternal: promoting %@ to GKLocalPlayerInternal. Stack trace:%@"
+ "Image cache root %@ is not under home %@; cannot validate cache paths"
+ "Refusing out-of-cache image path for subdirectory: %@, filename: %@"
- "Illegal file cache path for subdirectory: %@, filename: %@"
```
