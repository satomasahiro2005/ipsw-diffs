## ACCFeatureAudioProductService

> `/System/Library/PrivateFrameworks/CoreAccessoriesFeatures.framework/XPCServices/ACCFeatureAudioProductService.xpc/ACCFeatureAudioProductService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22a4` | `0x2280` | **`-0x24`** |
| `__DATA_CONST.__cfstring` | `0xd40` | `0xd60` | **`+0x20`** |
| `__TEXT.__cstring` | `0xaf5` | `0xb0d` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x700` | `0x710` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1

-  Symbols:   437
-  CStrings:  252
+  Symbols:   439
+  CStrings:  253
Symbols:
+ _ACCUserDefaultsKey_PretendWirelessCTAMatch
+ _kCFACCUserDefaultsKey_PretendWirelessCTAMatch
Functions:
~ -[ACCFeatureAudioProductService processAudioProductCerts:forModel:firstConnectionAfterPair:connection:endpoint:completionHandler:] : 3264 -> 3268
~ ___init_logging_modules_block_invoke : 608 -> 588
~ ___init_logging_signpost_modules_block_invoke : 608 -> 588
CStrings:
+ "PretendWirelessCTAMatch"
```
