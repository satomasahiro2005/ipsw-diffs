## CMPhoto

> `/System/Library/PrivateFrameworks/CMPhoto.framework/CMPhoto`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e3160` | `0x1e3ab0` | **`+0x950`** |
| `__DATA_DIRTY.__data` | `0xf40` | `0x848` | **`-0x6f8`** |
| `__AUTH.__data` | `0x1b18` | `0x21f0` | **`+0x6d8`** |
| `__AUTH.__objc_data` | `0x340` | `0x3e0` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0xf0` | `0x50` | **`-0xa0`** |
| `__DATA_DIRTY.__bss` | `0x630` | `0x5b8` | **`-0x78`** |
| `__DATA.__bss` | `0x7050` | `0x70c0` | **`+0x70`** |
| `__TEXT.__cstring` | `0x4aa9f` | `0x4aaef` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0xc638` | `0xc680` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x98ab0` | `0x98af0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x38c4` | `0x38f4` | **`+0x30`** |
| `__DATA.__data` | `0xe88` | `0xea8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1d30` | `0x1d40` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xa44` | `0xa54` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x1440` | `0x1450` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2578` | `0x2570` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x210` | `0x214` | **`+0x4`** |

### Other Changes

```diff

-478.0.0.0.0
+483.0.0.0.0

-  Functions: 7591
-  Symbols:   11850
-  CStrings:  13485
+  Functions: 7600
+  Symbols:   11854
+  CStrings:  13487
Symbols:
+ _CMPhotoCacheCopyItemForKey
+ _CMPhotoCreateTIFFContainerFromByteStream
+ _CMPhotoIsDeviceTypeH17
+ _CMPhotoIsDeviceTypeH18
+ _SlimVideoEncoder_EncodeFrameIntoDataInternal
+ ____inMemoryTileProvider_block_invoke
+ ____softwareTransferOverride_block_invoke
+ ___block_descriptor_48_e26_i24?0I8I12r^^{__CFData}16l
+ __decompressBuffer
+ __slimEncodeFrameForFlavor
- _CMPhotoCacheGetItemForKey
- _SwiftDNGToProtobuf
- _SwiftFreeDNGProtobufBuffer
- _SwiftProtobufToDNG
- __compressCallback
- _swift_willThrowTypedImpl
CStrings:
+ "createTIFFContainerFromByteStreamImpl(_:_:_:)"
+ "i24@?0I8I12r^^{__CFData}16"
```
