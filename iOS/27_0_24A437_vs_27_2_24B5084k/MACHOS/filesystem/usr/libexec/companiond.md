## companiond

> `/usr/libexec/companiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8c578` | `0x8c09c` | **`-0x4dc`** |
| `__TEXT.__objc_stubs` | `0x43e0` | `0x4460` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x6155` | `0x61a5` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x2d70` | `0x2d40` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x2560` | `0x2538` | **`-0x28`** |
| `__DATA.__objc_const` | `0x7548` | `0x7568` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1540` | `0x1560` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x1b80` | `0x1ba0` | **`+0x20`** |
| `__TEXT.__const` | `0x20b6` | `0x20d6` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1ab0` | `0x1ad0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x16c8` | `0x16b0` | **`-0x18`** |
| `__TEXT.__eh_frame` | `0x4ed0` | `0x4eb8` | **`-0x18`** |
| `__TEXT.__objc_methtype` | `0x1588` | `0x159b` | **`+0x13`** |
| `__DATA_CONST.__auth_ptr` | `0x558` | `0x560` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xd08` | `0xd00` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x410` | `0x414` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-524.0.56.0.0
+524.10.88.0.0

-  Functions: 2296
-  Symbols:   1273
-  CStrings:  1950
+  Functions: 2295
+  Symbols:   1270
+  CStrings:  1956
Symbols:
+ _$s12FindMyLocate12ClientTargetVMa
+ _$s12FindMyLocate12ClientTargetVMn
+ _$s12FindMyLocate13RequestOriginV_12clientTargetAcA06ClientE0O_AA0hG0VSgtcfC
+ _$s14CoreUtilsSwift15CUEventReporterP20eventMonitorCanceled2idys6UInt64V_tFTq
+ _$s14CoreUtilsSwift15CUEventReporterPAAE20eventMonitorCanceled2idys6UInt64V_tF
+ _$s17CompanionServices32CPSResponderUseCaseConfigurationV09responderF009requesterF0ACSgAA012CPSRequesterdeF0V_tFZ
+ _$s18AppIntentsServices0bC0O15localDispatcher11clientLabel6source11environment7optionsAA0A17IntentDispatching_pSS_So24LNTranscriptActionSourceVAA0aK11Environment_pAC14OptionsBuilderVy_AC0eQ0VGdtFZ
+ _OBJC_CLASS_$_CUXPCSubscriber
- _$s12FindMyLocate13RequestOriginVyAcA06ClientE0OcfC
- _$s17CompanionServices32CPSRequesterUseCaseConfigurationV0dE0OSHAAMc
- _$s17CompanionServices32CPSResponderUseCaseConfigurationV8useCasesSDyAA012CPSRequesterdeF0V0dE0OACGvgZ
- _$s18AppIntentsServices0bC0O14InterfaceIdiomO23defaultForCurrentDeviceAESgvgZ
- _$s18AppIntentsServices0bC0O14InterfaceIdiomOMn
- _$s18AppIntentsServices0bC0O14PayloadPrivacyO7defaultyA2EmFWC
- _$s18AppIntentsServices0bC0O14PayloadPrivacyOMa
- _$s18AppIntentsServices0bC0O15localDispatcher11clientLabel6source11environment7optionsAA0A17IntentDispatching_pSS_So24LNTranscriptActionSourceVAA0aK11Environment_pAC0E7OptionsVtFZ
- _$s18AppIntentsServices0bC0O17DispatcherOptionsV14interfaceIdiom14payloadPrivacyAeC09InterfaceG0OSg_AC07PayloadI0OtcfC
- _$s18AppIntentsServices0bC0O17DispatcherOptionsVMa
- _$sSH13_rawHashValue4seedS2i_tFTj
CStrings:
+ "@\"CUXPCSubscriber\""
+ "_xpcSubscriber"
+ "initWithStreamName:dispatchQueue:mock:"
+ "setEventHandler:"
+ "start"
+ "stop"
```
