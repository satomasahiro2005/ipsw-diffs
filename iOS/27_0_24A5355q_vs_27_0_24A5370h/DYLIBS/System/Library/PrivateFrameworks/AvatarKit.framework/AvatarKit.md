## AvatarKit

> `/System/Library/PrivateFrameworks/AvatarKit.framework/AvatarKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7792c` | `0x779d0` | **`+0xa4`** |
| `__TEXT.__cstring` | `0x1deff` | `0x1df4b` | **`+0x4c`** |
| `__AUTH_CONST.__cfstring` | `0x24980` | `0x249a0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x27d0` | `0x27f0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d58` | `0x3d70` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0xdd48` | `0xdd38` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x54b4` | `0x54bc` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1bc8` | `0x1bd0` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x2ec1` | `0x2ec0` | **`-0x1`** |

### Other Changes

```diff

-364.0.0.0.0
+366.0.0.0.0

-  Functions: 2525
-  Symbols:   4662
-  CStrings:  5156
+  Functions: 2530
+  Symbols:   4666
+  CStrings:  5159
Symbols:
+ -[AVTAvatar _detachAvatarNodeFromRenderer:world:parentNode:]
+ -[AVTAvatar _installAvatarNodeInRenderer:world:parentNode:]
+ -[AVTAvatar detachFromRenderer:world:parentNode:]
+ -[AVTAvatar installInRenderer:world:parentNode:]
+ -[AVTView _disconnectRendererFromAvatar:]
+ -[VFXWorld(AVTExtensionMRR) avt_removeAllUniqueIdentifiers]
+ GCC_except_table147
+ GCC_except_table187
+ GCC_except_table193
+ GCC_except_table83
+ ___59-[VFXWorld(AVTExtensionMRR) avt_removeAllUniqueIdentifiers]_block_invoke
+ ___60-[AVTRecordView exportMovieToURL:options:completionHandler:]_block_invoke_2
+ ___block_descriptor_140_e16_48s56s64s72s80s88s96s104s112bs_e5_v8?0ls48l8s56l8s64l8s72l8s80l8s88l8s112l8s96l8s104l8
+ ___block_descriptor_40_e24_v28?0f8"NSError"12^B20l
- -[AVTAvatar didAddToScene:]
- -[AVTAvatar willRemoveFromWorld:]
- -[AVTView _disconnectRendererFromAvatar:avatarNode:]
- -[VFXCamera(AVTExtension) avt_setSimdProjectionTransform:]
- -[VFXCamera(AVTExtension) avt_simdProjectionTransform]
- GCC_except_table145
- GCC_except_table185
- GCC_except_table191
- GCC_except_table82
- ___block_descriptor_148_e16_48s56s64s72s80s88s96s104s112s120bs_e5_v8?0ls48l8s56l8s64l8s72l8s80l8s88l8s96l8s120l8s104l8s112l8
CStrings:
+ "!8"
+ "Error: [Record view] Video export: failed to render movie with error %@"
+ "Unsupported CAAnimation subclass (%@)"
+ "physicsWorld"
+ "v28@?0f8@\"NSError\"12^B20"
- "!9"
- "Error: [Record view] Video export: failed to rendere movie with error %@"
```
