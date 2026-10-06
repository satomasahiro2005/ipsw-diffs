## sirittsd

> `/System/Library/PrivateFrameworks/SiriTTSService.framework/sirittsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59c10` | `0x5ab8c` | **`+0xf7c`** |
| `__TEXT.__eh_frame` | `0x1d30` | `0x1ee8` | **`+0x1b8`** |
| `__TEXT.__auth_stubs` | `0x2e00` | `0x2eb0` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0x1717` | `0x1797` | **`+0x80`** |
| `__DATA.__objc_const` | `0x18b0` | `0x1910` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0xd80` | `0xde0` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x1708` | `0x1760` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x1d98` | `0x1de8` | **`+0x50`** |
| `__DATA.__data` | `0x1b58` | `0x1b98` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x53e` | `0x57e` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xe78` | `0xeb8` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x219d` | `0x21cd` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x688` | `0x6ac` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x8d8` | `0x8f8` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x590` | `0x5a8` | **`+0x18`** |
| `__TEXT.__const` | `0x1210` | `0x1220` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xa90` | `0xaa0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x4e8` | `0x4f0` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xb52` | `0xb5a` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.103.2.0.0
+3600.113.1.0.0

+  - /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices

-  Functions: 1092
-  Symbols:   1122
-  CStrings:  568
+  Functions: 1107
+  Symbols:   1137
+  CStrings:  575
Symbols:
+ _$s14SiriTTSService11BaseRequestC13onBehalfOfPIDSivgTj
+ _$s14SiriTTSService11BaseRequestC13onBehalfOfPIDSivsTj
+ _$s14SiriTTSService13ReaderArticleV13preferredRateSfSgvg
+ _$s14SiriTTSService19OspreyBuiltInConfigCACycfC
+ _$s14SiriTTSService20OspreyChainedConfigsC7configsACSayAA0C15ConfigProviding_pG_tcfC
+ _$s14SiriTTSService22InlineStreamingStorageC10findSignal3forAA0cdG0CSgAA27SynthesizingRequestProtocol_p_tFTj
+ _$s14SiriTTSService24FMAcousticsResolveActionC4poolAcA10ObjectPoolC_tcfC
+ _$s14SiriTTSService24FMAcousticsResolveActionCAA10ActionableAAWP
+ _$s14SiriTTSService24FMAcousticsResolveActionCMa
+ _$s14SiriTTSService9PCCConfigO21allowedAppIdentifiersShySSGvgZ
+ _$sScM6sharedScMvgZ
+ _$sScMMa
+ _$sScMScAsWP
+ _$sSo17OS_dispatch_queueC14SiriTTSServiceE25platformSynthesisPrioritys5Int32VvgZ
+ _$sSo17OS_dispatch_queueC8DispatchE4mainABvgZ
+ _$sSo17OS_dispatch_queueC8DispatchE4sync7executexxyKXE_tKlF
+ _OBJC_CLASS_$_RBSProcessHandle
+ _OBJC_CLASS_$_RBSProcessIdentifier
+ _swift_getObjCClassFromMetadata
+ _voucher_get_current_persona_originator_info
- _$s14SiriTTSService19OspreyBuiltInConfigCACycfc
- _$s14SiriTTSService20OspreyChainedConfigsC7configsACSayAA0C15ConfigProviding_pG_tcfc
- _$s14SiriTTSService22InlineStreamingStorageC10findSignal12matchingTextAA0cdG0CSgSS_tFTj
- _$sSo17OS_dispatch_queueC14SiriTTSServiceE20appSynthesisPriority7requests5Int32VSgAC27SynthesizingRequestProtocol_AC04BaseL0CXc_tFZ
- _$sSo17OS_dispatch_queueC14SiriTTSServiceE25platformSynthesisPrioritys5Int32VSgvgZ
CStrings:
+ "Client %{public}s is not allowed to use PCC"
+ "handleForIdentifier:error:"
+ "headWasReset"
+ "identifierWithPid:"
+ "isApplication"
+ "lastBaselineElapsed"
+ "lastUpdateSystemTime"
```
