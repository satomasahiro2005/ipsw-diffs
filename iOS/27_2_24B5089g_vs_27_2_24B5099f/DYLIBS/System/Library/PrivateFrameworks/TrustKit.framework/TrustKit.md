## TrustKit

> `/System/Library/PrivateFrameworks/TrustKit.framework/TrustKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x2158` | `0x2830` | **`+0x6d8`** |
| `__AUTH.__data` | `0x610` | `—` | **`-0x610`** |
| `__DATA.__bss` | `0xb600` | `0xb980` | **`+0x380`** |
| `__AUTH.__objc_data` | `0x358` | `—` | **`-0x358`** |
| `__DATA_DIRTY.__objc_data` | `0xd68` | `0x10c0` | **`+0x358`** |
| `__AUTH_CONST.__const` | `0x5cd0` | `0x5f88` | **`+0x2b8`** |
| `__TEXT.__text` | `0x5ff54` | `0x601f0` | **`+0x29c`** |
| `__TEXT.__const` | `0x88a8` | `0x8ae0` | **`+0x238`** |
| `__TEXT.__eh_frame` | `0x3f80` | `0x3d88` | **`-0x1f8`** |
| `__DATA.__data` | `0x1280` | `0x10d8` | **`-0x1a8`** |
| `__AUTH_CONST.__objc_const` | `0x2260` | `0x2160` | **`-0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x3738` | `0x3818` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x184` | `0x1d8` | **`+0x54`** |
| `__TEXT.__unwind_info` | `0x1f80` | `0x1f30` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0x2720` | `0x26dc` | **`-0x44`** |
| `__TEXT.__swift5_reflstr` | `0x2323` | `0x2353` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x1874` | `0x18a0` | **`+0x2c`** |
| `__TEXT.__swift_as_entry` | `0xe4` | `0xb8` | **`-0x2c`** |
| `__TEXT.__swift_as_ret` | `0x13c` | `0x110` | **`-0x2c`** |
| `__AUTH_CONST.__auth_got` | `0xa48` | `0xa28` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x64c` | `0x668` | **`+0x1c`** |
| `__TEXT.__swift_as_cont` | `0x310` | `0x2f4` | **`-0x1c`** |
| `__TEXT.__swift5_assocty` | `0x2f8` | `0x310` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x64` | `0x78` | **`+0x14`** |
| `__TEXT.__cstring` | `0x27a4` | `0x27b4` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x148` | `0x140` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x2a8` | `0x2b0` | **`+0x8`** |

### Other Changes

```diff

-104.0.0.0.0
+106.0.0.0.0

-  Functions: 2602
-  Symbols:   1118
-  CStrings:  279
+  Functions: 2608
+  Symbols:   1130
+  CStrings:  278
Symbols:
+ ___swift_closure_destructor.62Tm
+ ___swift_closure_destructor.70Tm
+ ___swift_memcpy24_8
+ ___swift_memcpy4_4
+ ___swift_memcpy680_8
+ _associated conformance 8TrustKit21ConfigurationsAssetV2V26MessagesSenderLookUpConfigV10CodingKeys33_7A7BA87BE16A79718325C692447849A1LLOSHAASQ
+ _associated conformance 8TrustKit21ConfigurationsAssetV2V26MessagesSenderLookUpConfigV10CodingKeys33_7A7BA87BE16A79718325C692447849A1LLOs0K3KeyAAs23CustomStringConvertible
+ _associated conformance 8TrustKit21ConfigurationsAssetV2V26MessagesSenderLookUpConfigV10CodingKeys33_7A7BA87BE16A79718325C692447849A1LLOs0K3KeyAAs28CustomDebugStringConvertible
+ _get_enum_tag_for_layout_string 8TrustKit21ConfigurationsAssetV2V26MessagesSenderLookUpConfigVSg
+ _get_enum_tag_for_layout_string 8TrustKit21ConfigurationsAssetV2V31MessagesSignatureAnalysisConfigVSg
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_release_n
+ _swift_retain_x1
+ _swift_retain_x8
+ _symbolic Iegh_Sg
+ _symbolic ScCySb______pG s5ErrorP
+ _symbolic ScCy___________pG 8TrustKit20TKDecisioningServiceC23TKSpamDecisioningOutputV s5ErrorP
+ _symbolic ScTyyt_____GSg s5NeverO
+ _symbolic _____ 8TrustKit12TimeoutState33_E5C5414E166CEE00B09EA4CCF2CC3327LLV
+ _symbolic _____ 8TrustKit21ConfigurationsAssetV2V26MessagesSenderLookUpConfigV
+ _symbolic _____ 8TrustKit21ConfigurationsAssetV2V26MessagesSenderLookUpConfigV10CodingKeys33_7A7BA87BE16A79718325C692447849A1LLO
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ s6UInt32V
+ _symbolic _____Sg 8TrustKit21ConfigurationsAssetV2V26MessagesSenderLookUpConfigV
+ _symbolic _____Sg 8TrustKit21ConfigurationsAssetV2V31MessagesSignatureAnalysisConfigV
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 8TrustKit12TimeoutState33_E5C5414E166CEE00B09EA4CCF2CC3327LLV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8TrustKit21ConfigurationsAssetV2V26MessagesSenderLookUpConfigV10CodingKeys33_7A7BA87BE16A79718325C692447849A1LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8TrustKit21ConfigurationsAssetV2V26MessagesSenderLookUpConfigV10CodingKeys33_7A7BA87BE16A79718325C692447849A1LLO
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 8TrustKit12TimeoutState33_E5C5414E166CEE00B09EA4CCF2CC3327LLV So16os_unfair_lock_sV
+ _type_layout_string 8TrustKit12TimeoutState33_E5C5414E166CEE00B09EA4CCF2CC3327LLV
+ _type_layout_string 8TrustKit21ConfigurationsAssetV2V26MessagesSenderLookUpConfigV
+ _type_layout_string So16os_unfair_lock_sV
- __DATA__TtC8TrustKitP33_E5C5414E166CEE00B09EA4CCF2CC33278Executor
- __IVARS__TtC8TrustKitP33_E5C5414E166CEE00B09EA4CCF2CC33273Ref
- __IVARS__TtC8TrustKitP33_E5C5414E166CEE00B09EA4CCF2CC33278Executor
- __METACLASS_DATA__TtC8TrustKitP33_E5C5414E166CEE00B09EA4CCF2CC33278Executor
- ___swift_closure_destructor.65Tm
- ___swift_memcpy328_8
- ___swift_memcpy664_8
- _swift_retain_x24
- _swift_retain_x25
- _swift_retain_x27
- _symbolic B0
- _symbolic ScCyx______pG s5ErrorP
- _symbolic ScgySb______pG s5ErrorP
- _symbolic Scgy___________pG 8TrustKit20TKDecisioningServiceC23TKSpamDecisioningOutputV s5ErrorP
- _symbolic Scgyyt______pG s5ErrorP
- _symbolic _____ 8TrustKit3Ref33_E5C5414E166CEE00B09EA4CCF2CC3327LLC
- _symbolic _____ 8TrustKit8Executor33_E5C5414E166CEE00B09EA4CCF2CC3327LLC
- _symbolic _____yScTyyt_____GG 8TrustKit3Ref33_E5C5414E166CEE00B09EA4CCF2CC3327LLC s5NeverO
- _symbolic _____yScTyyt______pGG 8TrustKit3Ref33_E5C5414E166CEE00B09EA4CCF2CC3327LLC s5ErrorP
- _symbolic xSg
- _symbolic x______pIeghHrzo_ s5ErrorP
CStrings:
+ "performWithTimeout(of:timerDidFinish:_:)"
- "Operation timed out."
- "withTimeout(isolation:_:_:)"
```
