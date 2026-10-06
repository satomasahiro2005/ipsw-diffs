## com.apple.photos.ImageConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/XPCServices/com.apple.photos.ImageConversionService.xpc/com.apple.photos.ImageConversionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x263f` | `0x2694` | **`+0x55`** |
| `__DATA_CONST.__const` | `0x970` | `0x940` | **`-0x30`** |
| `__TEXT.__text` | `0x1a338` | `0x1a35c` | **`+0x24`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  - /usr/lib/swift/libswiftCoreFoundation.dylib
-  - /usr/lib/swift/libswiftDispatch.dylib
-  - /usr/lib/swift/libswiftObjectiveC.dylib
-  - /usr/lib/swift/libswiftXPC.dylib
-  - /usr/lib/swift/libswift_Builtin_float.dylib

-  Symbols:   361
-  CStrings:  1527
+  Symbols:   355
+  CStrings:  1528
Symbols:
- __swift_FORCE_LOAD_$_swiftCoreFoundation
- __swift_FORCE_LOAD_$_swiftDispatch
- __swift_FORCE_LOAD_$_swiftFoundation
- __swift_FORCE_LOAD_$_swiftObjectiveC
- __swift_FORCE_LOAD_$_swiftXPC
- __swift_FORCE_LOAD_$_swift_Builtin_float
Functions:
~ sub_100005d38 -> sub_100005bd8 : 656 -> 652
~ sub_10000652c -> sub_1000063c8 : 380 -> 376
~ sub_1000066a8 -> sub_100006540 : 380 -> 376
~ sub_100007d54 -> sub_100007be8 : 364 -> 360
~ sub_1000092c0 -> sub_100009150 : 392 -> 388
~ sub_1000098f0 -> sub_10000977c : 280 -> 276
~ sub_10000b0b0 -> sub_10000af38 : 768 -> 764
~ sub_10000b5b8 -> sub_10000b43c : 1288 -> 1284
~ sub_10000c9c0 -> sub_10000c840 : 424 -> 420
~ sub_1000115f0 -> sub_10001146c : 1692 -> 1688
~ sub_10001507c -> sub_100014ef4 : 716 -> 712
~ sub_1000163fc -> sub_100016270 : 1008 -> 1004
~ sub_100016dd8 -> sub_100016c48 : 1028 -> 1132
~ sub_1000173e8 -> sub_1000172c0 : 836 -> 832
~ sub_100018e84 -> sub_100018d58 : 908 -> 900
~ sub_10001a22c -> sub_10001a0f8 : 600 -> 596
~ sub_10001a484 -> sub_10001a34c : 1016 -> 1012
CStrings:
+ "Image source contains no decodable images, cannot perform passthrough conversion: %@"
```
