## siriinferenced

> `/System/Library/PrivateFrameworks/SiriInference.framework/Support/siriinferenced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11a98` | `0x11ee8` | **`+0x450`** |
| `__TEXT.__oslogstring` | `0xddf` | `0xe4f` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x800` | `0x850` | **`+0x50`** |
| `__TEXT.__cstring` | `0x4ec` | `0x49c` | **`-0x50`** |
| `__DATA.__data` | `0x8a8` | `0x878` | **`-0x30`** |
| `__TEXT.__auth_stubs` | `0x1280` | `0x12b0` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x948` | `0x960` | **`+0x18`** |
| `__TEXT.__const` | `0x480` | `0x490` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x248` | `0x240` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.28.10.1.2
+3600.34.6.0.0

-  - /System/Library/Frameworks/SiriInferenceLearning.framework/SiriInferenceLearning

+  - /System/Library/PrivateFrameworks/SiriInferenceLearning.framework/SiriInferenceLearning

-  Functions: 408
-  Symbols:   437
-  CStrings:  246
+  Functions: 419
+  Symbols:   439
+  CStrings:  247
Symbols:
+ _$s13SiriInference26SystemUserDefaultsProviderCACycfc
+ _$s13SiriInference26SystemUserDefaultsProviderCMa
+ _$s13SiriInference29UserEngagementSignalPublisherV20userDefaultsProviderAcA06SystemchI0C_tcfC
+ _$s13SiriInference29UserEngagementSignalPublisherV5startyyF
+ _$s13SiriInference29UserEngagementSignalPublisherVMa
- _$s11SiriSignals16SignalRepositoryC7prewarm23matchingCachingStrategyyShyAA0cgH6OptionOG_tFTj
- _$s11SiriSignals27SignalCachingStrategyOptionO21perSystemNotificationyACSS_tcACmFWC
- _$s13SiriInference11XPCActivityV38registerUserEngagementSignalCollectionyyFZ
CStrings:
+ "UserEngagementSignalCollection"
+ "UserEngagementSignalCollection Exiting due to DAS expiration"
+ "distnoted XPC event is unhandled"
- "com.apple.LaunchServices.applicationRegistered"
- "com.apple.LaunchServices.applicationUnregistered"
```
