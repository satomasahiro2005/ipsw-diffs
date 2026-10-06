## AXMediaUtilities

> `/System/Library/PrivateFrameworks/AXMediaUtilities.framework/AXMediaUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd4428` | `0xd43d8` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0xcc40` | `0xcc20` | **`-0x20`** |
| `__TEXT.__cstring` | `0xa686` | `0xa679` | **`-0xd`** |
| `__AUTH_CONST.__auth_got` | `0xef8` | `0xf00` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x6220` | `0x6228` | **`+0x8`** |

### Other Changes

```diff

-182.0.0.0.0
+183.0.0.0.0

+  - /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration

-  Symbols:   8743
-  CStrings:  2499
+  Symbols:   8744
+  CStrings:  2498
Symbols:
+ _SCDynamicStoreCopyComputerName
Functions:
~ +[ImageTools create420YCbCr8BufferFromPlanar8Buffer:withWidth:andWithHeight:andWithBytesPerRow:toLumaBuffer:withBytesPerRowLuma:andToChromaBuffer:withBytesPerRowChroma:] : 980 -> 976
~ +[ImageTools create420YCbCr8BufferFromRGB8Buffer:withWidth:andWithHeight:andWithBytesPerRow:andAlphaFirst:toLumaBuffer:withBytesPerRowLuma:andToChromaBuffer:withBytesPerRowChroma:] : 900 -> 896
~ +[ImageTools createRGB8BufferFrom420Y8PlanarBuffer:withBytesPerRowY:andFrom420Cb8Buffer:withBytesPerRowCb:andFrom420Cr8Buffer:withBytesPerRowCr:andWithWidth:andWithHeight:andAlphaFirst:toRGB8Buffer:withBytesPerRowDst:] : 708 -> 668
~ +[ImageTools createRGB8BufferFrom420Y8BiPlanarBuffer:withBytesPerRowLuma:andFrom420CbCr8Buffer:withBytesPerRowChroma:andWithWidth:andWithHeight:andAlphaFirst:toRGB8Buffer:withBytesPerRowDst:] : 688 -> 652
~ -[AXMHapticComponent transitionToState:completion:] : 988 -> 1000
~ -[AXMDeviceInfo computerName] : 116 -> 140
~ sub_1caeef834 -> sub_1ceede874 : 768 -> 740
~ sub_1caef0938 -> sub_1ceedf95c : 416 -> 412
CStrings:
- "ComputerName"
```
