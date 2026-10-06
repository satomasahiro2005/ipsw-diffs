## TranslationDaemon

> `/System/Library/PrivateFrameworks/TranslationDaemon.framework/TranslationDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a9e60` | `0x1a6b80` | **`-0x32e0`** |
| `__AUTH.__objc_data` | `0xa260` | `0xa1c0` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x1040` | `0x10e0` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x400` | `0x388` | **`-0x78`** |
| `__AUTH_CONST.__auth_got` | `0xd68` | `0xcf8` | **`-0x70`** |
| `__DATA_CONST.__const` | `0x43c8` | `0x4420` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x1a2a8` | `0x1a2d8` | **`+0x30`** |
| `__DATA.__data` | `0xcd8` | `0xcb8` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xed8` | `0xeb8` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x360` | `0x342` | **`-0x1e`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b18` | `0x6b30` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x288` | `0x278` | **`-0x10`** |
| `__TEXT.__const` | `0xa8a` | `0xa7a` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xf9a0` | `0xf9a8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x14` | `0x10` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-384.1.0.0.0
+384.3.0.0.0

-  Functions: 10397
-  Symbols:   18729
+  Functions: 10393
+  Symbols:   18731
Symbols:
+ +[_LTDTTSAssetService _bestTTSAssetForLocaleIdentifier:]
+ +[_LTDTTSAssetService hasVoiceForLocaleIdentifier:]
+ __CLASS_METHODS__LTDLLMBasedTranslationStatus
+ __LTDHasTTSVoiceForLocaleIdentifier
+ _swift_release_x23
+ _swift_retain_x23
+ _symbolic ScSyytG
+ _symbolic _____yyt_G ScS8IteratorV
- _swift_willThrowTypedImpl
- _symbolic _____ 16GenerativeModels0aB12AvailabilityV
- _symbolic _____Sg 16GenerativeModels0aB12AvailabilityV0C0O
- _symbolic ______p s5ErrorP
- _symbolic _____y_____G s11_SetStorageC 16GenerativeModels0cD12AvailabilityV0E0O15UnavailableInfoV0F6ReasonO
- _symbolic _____y_____G s23_ContiguousArrayStorageC 16GenerativeModels0dE12AvailabilityV0F0O15UnavailableInfoV0G6ReasonO
CStrings:
+ "LLM translation availability change event"
- "LLM translation availability change event [%s]"
```
