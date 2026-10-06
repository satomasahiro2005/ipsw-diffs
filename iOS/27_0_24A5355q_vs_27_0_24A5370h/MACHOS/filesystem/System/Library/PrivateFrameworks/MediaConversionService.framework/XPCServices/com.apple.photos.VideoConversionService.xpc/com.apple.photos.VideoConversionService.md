## com.apple.photos.VideoConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/XPCServices/com.apple.photos.VideoConversionService.xpc/com.apple.photos.VideoConversionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x2f03` | `0x2f58` | **`+0x55`** |
| `__TEXT.__text` | `0x21a4c` | `0x21a24` | **`-0x28`** |
| `__DATA_CONST.__cfstring` | `0x2740` | `0x2720` | **`-0x20`** |
| `__TEXT.__cstring` | `0x34f6` | `0x34e4` | **`-0x12`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0
Functions:
~ sub_10000589c : 656 -> 652
~ sub_100006090 -> sub_10000608c : 380 -> 376
~ sub_10000620c -> sub_100006204 : 380 -> 376
~ sub_1000078b8 -> sub_1000078ac : 364 -> 360
~ sub_100008f0c -> sub_100008efc : 392 -> 388
~ sub_10000953c -> sub_100009528 : 280 -> 276
~ sub_10000acfc -> sub_10000ace4 : 768 -> 764
~ sub_10000b204 -> sub_10000b1e8 : 1288 -> 1284
~ sub_10000c60c -> sub_10000c5ec : 424 -> 420
~ sub_1000111cc -> sub_1000111a8 : 1692 -> 1688
~ sub_100013814 -> sub_1000137ec : 1028 -> 1132
~ sub_100013e24 -> sub_100013e64 : 836 -> 832
~ sub_1000153dc -> sub_100015418 : 1372 -> 1380
~ sub_100019438 -> sub_10001947c : 1036 -> 968
~ sub_100019ab8 : 1392 -> 1388
~ sub_10001a488 -> sub_10001a484 : 2060 -> 2052
~ sub_10001db30 -> sub_10001db24 : 660 -> 656
~ sub_10001de40 -> sub_10001de30 : 1364 -> 1360
~ sub_10001e938 -> sub_10001e924 : 804 -> 800
~ sub_1000203f4 -> sub_1000203dc : 908 -> 900
~ sub_10002179c -> sub_10002177c : 600 -> 596
~ sub_1000219f4 -> sub_1000219d0 : 1016 -> 1012
CStrings:
+ "Image source contains no decodable images, cannot perform passthrough conversion: %@"
- "Export was paused"
```
