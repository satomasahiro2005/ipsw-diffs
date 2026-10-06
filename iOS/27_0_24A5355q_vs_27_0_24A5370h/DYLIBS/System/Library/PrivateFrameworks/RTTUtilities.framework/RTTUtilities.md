## RTTUtilities

> `/System/Library/PrivateFrameworks/RTTUtilities.framework/RTTUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27c34` | `0x296dc` | **`+0x1aa8`** |
| `__TEXT.__oslogstring` | `0x34d2` | `0x37d3` | **`+0x301`** |
| `__TEXT.__eh_frame` | `0x48` | `0x1f8` | **`+0x1b0`** |
| `__TEXT.__cstring` | `0x194b` | `0x1a1d` | **`+0xd2`** |
| `__AUTH_CONST.__const` | `0x558` | `0x620` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0xa70` | `0xb28` | **`+0xb8`** |
| `__AUTH.__objc_data` | `0x198` | `0x248` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x1e18` | `0x1ec8` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x1920` | `0x19c0` | **`+0xa0`** |
| `__TEXT.__const` | `0x1c0` | `0x250` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0x538` | `0x5b8` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x19f0` | `0x1a50` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x30` | `0x8c` | **`+0x5c`** |
| `__AUTH_CONST.__objc_const` | `0x20b8` | `0x2110` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x46` | `0x92` | **`+0x4c`** |
| `__TEXT.__constg_swiftt` | `0x9c` | `0xc8` | **`+0x2c`** |
| `__AUTH.__data` | `0x50` | `0x78` | **`+0x28`** |
| `__DATA_CONST.__const` | `0xf90` | `0xfb8` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `—` | `0x14` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x390` | `0x3a0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x38` | `0x48` | **`+0x10`** |
| `__DATA.__data` | `0x528` | `0x530` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x98` | `0xa0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xcd8` | `0xce0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x8` | `0xc` | **`+0x4`** |

### Other Changes

```diff

-527.0.0.0.0
+530.0.0.0.0

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 795
-  Symbols:   1558
-  CStrings:  597
+  Functions: 837
+  Symbols:   1599
+  CStrings:  611
Symbols:
+ -[RTTSettings _migrateLiveTranscriptionDefaultForUnsupportedDeviceLanguage]
+ -[RTTSettings cachedSupportsEmergencyRTTForContext:]
+ -[RTTSettings cachedSupportsHoldForRTTForContext:]
+ -[RTTSettings cachedSupportsRTTForContext:]
+ -[RTTSettings cachedSupportsTTYForContext:]
+ -[RTTSettings rttLiveTranscriptionsUserDidToggleEnabled]
+ -[RTTSettings setCachedSupportsEmergencyRTT:forContext:]
+ -[RTTSettings setCachedSupportsHoldForRTT:forContext:]
+ -[RTTSettings setCachedSupportsRTT:forContext:]
+ -[RTTSettings setCachedSupportsTTY:forContext:]
+ -[RTTSettings setRTTLiveTranscriptionsEnabled:forContext:userInitiated:]
+ GCC_except_table654
+ GCC_except_table675
+ GCC_except_table691
+ GCC_except_table696
+ GCC_except_table740
+ GCC_except_table743
+ _OBJC_CLASS_$_RTTLiveCaptionsLanguageObjC
+ _OBJC_METACLASS_$_RTTLiveCaptionsLanguageObjC
+ __CLASS_METHODS_RTTLiveCaptionsLanguageObjC
+ __DATA_RTTLiveCaptionsLanguageObjC
+ __INSTANCE_METHODS_RTTLiveCaptionsLanguageObjC
+ __METACLASS_DATA_RTTLiveCaptionsLanguageObjC
+ ___75-[RTTSettings _migrateLiveTranscriptionDefaultForUnsupportedDeviceLanguage]_block_invoke
+ ___block_descriptor_40_e8_32s_e18_v16?0"NSString"8ls32l8
+ ___swift_async_cont_functlets
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ ___swift_closure_destructor.21Tm
+ _swift_getObjectType
+ _swift_release
+ _swift_release_x21
+ _swift_retain_x21
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _symbolic IeAgH_
+ _symbolic IeghH_
+ _symbolic ScA_pSg
+ _symbolic ScPSg
+ _symbolic So8NSStringCIeyBy_
+ _symbolic _____ 12RTTUtilities27RTTLiveCaptionsLanguageObjCC
+ _symbolic _____XMo 12RTTUtilities27RTTLiveCaptionsLanguageObjCC
+ _symbolic ytIeAgHr_
- GCC_except_table644
- GCC_except_table663
- GCC_except_table679
- GCC_except_table684
- GCC_except_table728
- GCC_except_table731
CStrings:
+ "Defaulting RTT live transcription OFF: live captions does not support device language %{public}@ (default %{public}@)"
+ "EmergencyRTT %@ for context %@ with capabilities %@ (cached fallback: %d)"
+ "HoldForRTT %@ for context %@ with capabilities %@ (cached fallback: %d)"
+ "Missing or invalid conversation data for write action"
+ "RTT %@ for context %@ with capabilities %@ (cached fallback: %d)"
+ "RTT LC language migration: device language %{public}@ unsupported but setting already off, nothing to do"
+ "RTT LC language migration: leaving setting unchanged, live captions supports device language %{public}@"
+ "RTT LC language migration: skipping, NonUI build"
+ "RTT LC language migration: skipping, could not resolve languages (device %{public}@, default %{public}@)"
+ "RTT LC language migration: skipping, live transcription feature not enabled"
+ "RTT LC language migration: skipping, user already toggled the setting"
+ "RTTCachedSupportsEmergencyRTTPreference"
+ "RTTCachedSupportsHoldForRTTPreference"
+ "RTTCachedSupportsRTTPreference"
+ "RTTCachedSupportsTTYPreference"
+ "RTTLiveTranscriptionUserDidToggleEnabledPreference"
+ "TTY %@ for context %@ with capabilities %@ (cached fallback: %d)"
+ "v16@?0@\"NSString\"8"
- "EmergencyRTT %@ for context %@ with capabilities %@"
- "HoldForRTT %@ for context %@ with capabilities %@"
- "RTT %@ for context %@ with capabilities %@"
- "TTY %@ for context %@ with capabilities %@"
```
