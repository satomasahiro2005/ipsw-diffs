## PosterLegibilityKit

> `/System/Library/PrivateFrameworks/PosterLegibilityKit.framework/PosterLegibilityKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x232ac` | `0x236e0` | **`+0x434`** |
| `__TEXT.__gcc_except_tab` | `0x6dc` | `0x720` | **`+0x44`** |
| `__TEXT.__cstring` | `0x12ab` | `0x12ea` | **`+0x3f`** |
| `__DATA_CONST.__const` | `0x968` | `0x990` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x320` | `0x340` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x25d8` | `0x25f0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xbb0` | `0xbc8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x7f8` | `0x808` | **`+0x10`** |
| `__DATA.__bss` | `0x138` | `0x148` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x18d0` | `0x18e0` | **`+0x10`** |
| `__DATA.__data` | `0x600` | `0x608` | **`+0x8`** |

### Other Changes

```diff

-347.102.0.0.0
+350.1.100.0.0

-  Functions: 907
-  Symbols:   1970
-  CStrings:  300
+  Functions: 914
+  Symbols:   1981
+  CStrings:  302
Symbols:
+ +[PLKImageRenderer plk_isImagePoolBacked:]
+ +[PLKImageRenderer plk_poolBackedImageFromImage:]
+ GCC_except_table26
+ ___69-[PLKCachedImageGenerator initWithCache:keyGenerator:imageGenerator:]_block_invoke
+ _____plk_poolReleaseQueue_block_invoke
+ _____plk_releasePoolDataOffMain_block_invoke
+ ___block_descriptor_40_e8_32bs_e20_"UIImage"24?0816ls32l8
+ ___plk_poolReleaseQueue.onceToken
+ ___plk_poolReleaseQueue.queue
+ ___plk_releasePoolDataOffMain
+ _dispatch_async
+ _dispatch_queue_attr_make_with_qos_class
+ _dispatch_queue_create
+ _kPLKImagePoolBackedKey
- GCC_except_table13
- GCC_except_table25
- _CGDataProviderCreateWithCFData
CStrings:
+ "@\"UIImage\"24@?0@8@16"
+ "com.apple.PosterLegibilityKit.poolRelease"
```
