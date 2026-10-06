## StickersUI

> `/System/Library/PrivateFrameworks/StickersUI.framework/StickersUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63db4` | `0x66980` | **`+0x2bcc`** |
| `__DATA.__bss` | `0x2090` | `0x2240` | **`+0x1b0`** |
| `__AUTH_CONST.__const` | `0x2590` | `0x26d0` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x21f8` | `0x22f0` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0x125d` | `0x131d` | **`+0xc0`** |
| `__AUTH.__data` | `0xd30` | `0xdd0` | **`+0xa0`** |
| `__TEXT.__const` | `0x1f74` | `0x2004` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0xea0` | `0xf2e` | **`+0x8e`** |
| `__TEXT.__swift5_capture` | `0x6c8` | `0x754` | **`+0x8c`** |
| `__TEXT.__unwind_info` | `0x12a8` | `0x1320` | **`+0x78`** |
| `__TEXT.__constg_swiftt` | `0x1a14` | `0x1a80` | **`+0x6c`** |
| `__AUTH_CONST.__auth_got` | `0x10c8` | `0x1118` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xbc8` | `0xc18` | **`+0x50`** |
| `__TEXT.__cstring` | `0xbc9` | `0xc09` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0xc6c` | `0xca0` | **`+0x34`** |
| `__DATA_DIRTY.__objc_data` | `0x2c0` | `0x2f0` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xe81` | `0xeb1` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x140` | `0x160` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x270` | `0x290` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x8f0` | `0x910` | **`+0x20`** |
| `__DATA.__data` | `0xa98` | `0xab0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x568` | `0x580` | **`+0x18`** |
| `__AUTH.__objc_data` | `0x1a38` | `0x1a48` | **`+0x10`** |
| `__DATA.__common` | `0x130` | `0x140` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x10c` | `0x118` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xa8` | `0xb0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xc4` | `0xcc` | **`+0x8`** |

### Other Changes

```diff

-405.100.1.0.0
+406.100.1.0.0

-  Functions: 1830
-  Symbols:   898
-  CStrings:  182
+  Functions: 1874
+  Symbols:   927
+  CStrings:  188
Symbols:
+ -[STKMSStickerView applySticker:withDisplayThumbnail:]
+ _CGImageGetBytesPerRow
+ _CGImageGetHeight
+ _NSSelectorFromString
+ _OBJC_CLASS_$_NSCache
+ _STKMSStickerViewLog.log
+ _STKMSStickerViewLog.onceToken
+ __DATA__TtC10StickersUI31StickerStillPlaceholderProvider
+ __IVARS__TtC10StickersUI31StickerStillPlaceholderProvider
+ __METACLASS_DATA__TtC10StickersUI31StickerStillPlaceholderProvider
+ __NSConcreteGlobalBlock
+ ___STKMSStickerViewLog_block_invoke
+ ___block_descriptor_32_e5_v8?0l
+ ___block_literal_global
+ ___swift_closure_destructor.205Tm
+ ___swift_closure_destructor.36Tm
+ ___swift_closure_destructor.91Tm
+ __os_log_error_impl
+ _dispatch_once
+ _kCGImageSourceCreateThumbnailWithTransform
+ _kCGImageSourceShouldCacheImmediately
+ _os_log_create
+ _swift_retain_x23
+ _swift_retain_x28
+ _symbolic So6NSUUIDC
+ _symbolic So7NSCacheCySo6NSUUIDCSo7UIImageCG
+ _symbolic So7UIImageCSgIegg_
+ _symbolic _____ 10StickersUI31StickerStillPlaceholderProviderC
+ _symbolic _____SgXw 10StickersUI31StickerStillPlaceholderProviderC
+ _symbolic _____SgXwz_Xx 10StickersUI31StickerStillPlaceholderProviderC
+ _symbolic ______ypt So11CFStringRefa
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC So11CFStringRefa
+ _symbolic _____y_____ypG s18_DictionaryStorageC So11CFStringRefa
- ___swift_closure_destructor.201Tm
- ___swift_closure_destructor.26Tm
- ___swift_closure_destructor.32Tm
- ___swift_closure_destructor.87Tm
CStrings:
+ "Failed to create image source for sticker still placeholder"
+ "Failed to create thumbnail for sticker still placeholder"
+ "applySticker:withDisplayThumbnail: MSSticker has no set_thumbnail:"
+ "placeholder-provider"
+ "set_thumbnail:"
+ "v8@?0"
```
