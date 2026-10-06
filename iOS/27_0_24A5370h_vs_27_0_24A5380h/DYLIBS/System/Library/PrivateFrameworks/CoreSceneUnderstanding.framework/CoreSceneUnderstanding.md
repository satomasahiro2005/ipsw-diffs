## CoreSceneUnderstanding

> `/System/Library/PrivateFrameworks/CoreSceneUnderstanding.framework/CoreSceneUnderstanding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc3d84` | `0xc2e8c` | **`-0xef8`** |
| `__AUTH_CONST.__cfstring` | `0x37c0` | `0x3660` | **`-0x160`** |
| `__TEXT.__cstring` | `0x9658` | `0x9508` | **`-0x150`** |
| `__TEXT.__gcc_except_tab` | `0xefd4` | `0xeea0` | **`-0x134`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x270` | `0x240` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x4d0` | `0x4e8` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x380` | `0x368` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x396c` | `0x3984` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1be8` | `0x1bf8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4558` | `0x4548` | **`-0x10`** |

### Other Changes

```diff

-95.0.0.0.0
+97.0.0.0.0

-  CStrings:  1067
+  CStrings:  1056
CStrings:
+ "CSUSystemSearchTextEncoderRevision_v7_0_Tier0 (MD7) has been removed. Migrate to MADTextEncoder in the EmbeddingCore framework."
+ "SafetyNetLight_v1.3.0_83cm9h9a9m_4436_safetynet_quant"
+ "scenenet_v5_custom_classifiers/SafetyNetLight/SafetyNetLight_v1.3.0"
- "ImageCaptioning-mica_v3.0.0_ya2ywy3nyz-40222"
- "ImageCaptioning-mica_v3.0.0_ya2ywy3nyz-40222.reverse_vocab"
- "ImageCaptioning-mica_v3.0.0_ya2ywy3nyz-40222_bridge_stage2_quantized"
- "ImageCaptioning-mica_v3.0.0_ya2ywy3nyz-40222_decoder_stage2_quantized"
- "ImageCaptioningMD4_s3xsc4vvsa-34701"
- "ImageCaptioningMD5_jf7fjab8py-1414"
- "ImageCaptioningMD7_iyz2icc7y5-1200"
- "SafetyNetLight_v1.2.0_2h7cckqvsc_6496_safetynet_quant"
- "SystemSearch/v7.0.0/"
- "VideoCaptioning_v7.0.0_vua87vwft9-44550"
- "bridge_input"
- "scenenet_v5_custom_classifiers/SafetyNetLight/SafetyNetLight_v1.2.0"
- "spm_omnie_md7_v02_100k_mmap"
- "token_md7_6bit"
```
