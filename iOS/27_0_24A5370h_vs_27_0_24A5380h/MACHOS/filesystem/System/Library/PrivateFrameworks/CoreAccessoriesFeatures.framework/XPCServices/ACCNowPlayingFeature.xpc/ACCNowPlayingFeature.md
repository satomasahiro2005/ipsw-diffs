## ACCNowPlayingFeature

> `/System/Library/PrivateFrameworks/CoreAccessoriesFeatures.framework/XPCServices/ACCNowPlayingFeature.xpc/ACCNowPlayingFeature`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0xc60` | `0xc80` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x2b3f` | `0x2b5b` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x258` | `0x268` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1000` | `0x1010` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xab0` | `0xab8` | **`+0x8`** |
| `__TEXT.__cstring` | `0x120b` | `0x1213` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x438` | `0x440` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Functions: 434
-  Symbols:   1303
-  CStrings:  903
+  Functions: 435
+  Symbols:   1304
+  CStrings:  905
Symbols:
+ -[ACCNowPlayingFeature setMockXPCListenerEndpoint:]
+ GCC_except_table76
+ GCC_except_table81
- GCC_except_table75
- GCC_except_table80
Functions:
+ -[ACCNowPlayingFeature setMockXPCListenerEndpoint:]
~ -[ACCNowPlayingFeature _nowPlayingArtworkDidChange] : 656 -> 636
~ -[ACCStatInfoAccumulator init] : 96 -> 104
CStrings:
+ "Unnamed"
+ "setMockXPCListenerEndpoint:"
```
