## ExclavesInferenceProvider

> `/System/Library/ExtensionKit/Extensions/ExclavesInferenceProvider.appex/ExclavesInferenceProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17748` | `0x1a07c` | **`+0x2934`** |
| `__TEXT.__eh_frame` | `0x14a0` | `0x1868` | **`+0x3c8`** |
| `__TEXT.__cstring` | `0x8a8` | `0xb48` | **`+0x2a0`** |
| `__TEXT.__swift5_reflstr` | `0x628` | `0x879` | **`+0x251`** |
| `__DATA_CONST.__const` | `0x16d8` | `0x1808` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0x8d0` | `0x9f8` | **`+0x128`** |
| `__TEXT.__oslogstring` | `0x484` | `0x564` | **`+0xe0`** |
| `__TEXT.__swift5_fieldmd` | `0x764` | `0x830` | **`+0xcc`** |
| `__TEXT.__auth_stubs` | `0xde0` | `0xe90` | **`+0xb0`** |
| `__TEXT.__const` | `0x17a0` | `0x1830` | **`+0x90`** |
| `__DATA_CONST.__auth_got` | `0x6f0` | `0x750` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `—` | `0x40` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0xa0` | `0xdc` | **`+0x3c`** |
| `__TEXT.__constg_swiftt` | `0x8c8` | `0x8f8` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x6f1` | `0x71d` | **`+0x2c`** |
| `__DATA.__data` | `0xc50` | `0xc78` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x318` | `0x338` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x258` | `0x278` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x2a3` | `0x2c3` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0xa4` | `0xc4` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x70` | `0x88` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x74` | `0x88` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0xa0` | `0xb0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-703.0.33.0.0
+714.40.81.502.1

-  Functions: 763
-  Symbols:   126
-  CStrings:  146
+  Functions: 840
+  Symbols:   129
+  CStrings:  164
Symbols:
+ _OBJC_CLASS_$_NSFileManager
+ _objc_msgSend
+ _objc_release_x22
+ _swift_release_x25
- _swift_retain_x22
CStrings:
+ "/AppleInternal/usr/local/libexec/exclavetestrelayd"
+ "ExclavesInferenceProvider executing usedSinceLastHysteresisCheck: %s"
+ "Invalid key value while decoding result type for moveAssetToDynamicMode"
+ "Invalid key value while decoding result type for usedSinceLastHysteresisCheck"
+ "com.apple.modelmanager.ExclavesInferenceProvider.downcall"
+ "com.apple.modelmanager.exclaves.test.internal"
+ "com.apple.placeholder.imagemodel.base_exclave"
+ "com.apple.placeholder.imagemodel.image_encoder_exclave"
+ "com.apple.placeholder.imagemodel.tokenizer_exclave"
+ "com.apple.unknown3"
+ "com.apple.unknown4.base"
+ "com.apple.unknown5.tokenizer"
+ "com.apple.unknown6.encoder"
+ "defaultManager"
+ "fileExistsAtPath:"
+ "moveAssetToDynamicMode failed: "
+ "moveAssetToDynamicMode: no client, cannot make asset reclaimable"
+ "usedSinceLastHysteresisCheck: no client, reporting not-used"
```
