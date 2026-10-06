## AXImageExplorerServer

> `/System/Library/AccessibilityBundles/AXImageExplorerServer.axuiservice/AXImageExplorerServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x548b0` | `0x56e38` | **`+0x2588`** |
| `__DATA.__data` | `0x1e20` | `0x1fc0` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x1419` | `0x1509` | **`+0xf0`** |
| `__TEXT.__auth_stubs` | `0x2a40` | `0x2b00` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x11f0` | `0x1160` | **`-0x90`** |
| `__TEXT.__cstring` | `0x128b` | `0x12fb` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x1528` | `0x1588` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x6c12` | `0x6c60` | **`+0x4e`** |
| `__TEXT.__unwind_info` | `0x1200` | `0x1240` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x8d0` | `0x904` | **`+0x34`** |
| `__TEXT.__swift5_fieldmd` | `0x5d4` | `0x608` | **`+0x34`** |
| `__DATA_CONST.__got` | `0x9d8` | `0x9f8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x6a7` | `0x6c7` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x2494` | `0x2484` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x7e0` | `0x7e8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x78` | `0x7c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3245.7.1.0.0
+3245.8.2.0.0

-  Functions: 1331
-  Symbols:   261
-  CStrings:  478
+  Functions: 1339
+  Symbols:   265
+  CStrings:  483
Symbols:
+ _AVAudioSessionCategoryRecord
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_retain_x26
- _swift_cvw_enumFn_getEnumTag
CStrings:
+ "%s rate limited. retryAfterDate=%s"
+ "AFM_RATE_LIMITED_RESPONSE"
+ "AFM_RATE_LIMITED_RESPONSE_TIME"
+ "AFM_RATE_LIMITED_RESPONSE_TOMORROW_TIME"
+ "Already asking about image; a prior request still holds the image."
+ "Already generating image description; a prior request still holds the image."
+ "[AXImageExplorerAudioInputManager] A prior session is still listening; no new session was started."
- "Already asking about image."
- "Already generating image description."
```
