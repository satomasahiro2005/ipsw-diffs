## Cinematic

> `/System/Library/Frameworks/Cinematic.framework/Cinematic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__gcc_except_tab` | `0x26c` | `0x200` | **`-0x6c`** |
| `__TEXT.__text` | `0x13df8` | `0x13e4c` | **`+0x54`** |
| `__AUTH_CONST.__objc_const` | `0x1e20` | `0x1df0` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x6e0` | `0x708` | **`+0x28`** |
| `__TEXT.__cstring` | `0x359` | `0x379` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x4c8` | `0x4d8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xe9c` | `0xe8c` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xb90` | `0xb88` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x98` | `0x94` | **`-0x4`** |

### Other Changes

```diff

-551.0.0.0.0
+556.0.0.0.1

-  Symbols:   965
-  CStrings:  78
+  Symbols:   967
+  CStrings:  79
Symbols:
+ +[CNRenderingSessionAttributes _loadFromAsset:supportPreview:completionHandler:]
+ GCC_except_table32
+ ___65+[CNAssetInfo _loadFromAsset:requireDisparity:completionHandler:]_block_invoke_2
+ ___80+[CNRenderingSessionAttributes _loadFromAsset:supportPreview:completionHandler:]_block_invoke
+ ___block_descriptor_73_e8_32s40bs48r56r_e5_v8?0ls32l8r48l8r56l8s40l8
+ _dispatch_async
+ _objc_retain_x9
- -[CNRenderingSessionAttributes disparityPreview]
- -[CNRenderingSessionAttributes setDisparityPreview:]
- GCC_except_table4
- _OBJC_IVAR_$_CNRenderingSessionAttributes._disparityPreview
- ___64+[CNRenderingSessionAttributes loadFromAsset:completionHandler:]_block_invoke
CStrings:
+ "com.apple.cinematic.loadFromAsset"
```
