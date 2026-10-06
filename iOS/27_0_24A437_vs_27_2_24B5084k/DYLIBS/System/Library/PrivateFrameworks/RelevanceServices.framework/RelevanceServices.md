## RelevanceServices

> `/System/Library/PrivateFrameworks/RelevanceServices.framework/RelevanceServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdd1c` | `0xf7d4` | **`+0x1ab8`** |
| `__TEXT.__const` | `0xa24` | `0xb10` | **`+0xec`** |
| `__AUTH_CONST.__auth_got` | `0x590` | `0x670` | **`+0xe0`** |
| `__AUTH.__data` | `0x180` | `0x250` | **`+0xd0`** |
| `__TEXT.__eh_frame` | `0x120` | `0x1e0` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x2e2` | `0x37e` | **`+0x9c`** |
| `__AUTH_CONST.__objc_const` | `0x680` | `0x710` | **`+0x90`** |
| `__DATA.__bss` | `0xa40` | `0xad0` | **`+0x90`** |
| `__DATA.__data` | `0x390` | `0x418` | **`+0x88`** |
| `__TEXT.__constg_swiftt` | `0x2ec` | `0x364` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x498` | `0x510` | **`+0x78`** |
| `__DATA_CONST.__got` | `0x188` | `0x1e8` | **`+0x60`** |
| `__TEXT.__cstring` | `0x853` | `0x7f8` | **`-0x5b`** |
| `__AUTH.__objc_data` | `0x3b0` | `0x400` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x6e8` | `0x730` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x18f` | `0x1d3` | **`+0x44`** |
| `__TEXT.__swift5_reflstr` | `0x350` | `0x390` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x320` | `0x348` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x20` | `0x40` | **`+0x20`** |
| `__DATA.__common` | `0x78` | `0x98` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x60` | `0x78` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x78` | `0x88` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x8` | `0x18` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x110` | `0x118` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x54` | `0x58` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x38` | `0x3c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x8` | `0xc` | **`+0x4`** |

### Other Changes

```diff

-217.11.0.0.0
+242.1.0.0.0
+  - /System/Library/Frameworks/Combine.framework/Combine

+  - /System/Library/Frameworks/ManagedSettings.framework/ManagedSettings

+  - /System/Library/PrivateFrameworks/EligibilityQuorum.framework/EligibilityQuorum

+  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry

-  Functions: 444
-  Symbols:   319
+  Functions: 472
+  Symbols:   349
Symbols:
+ _MobileGestalt_get_exclaveCapability
+ _OBJC_CLASS_$_NSUUID
+ _RSAudioIntelligenceCapabilityUUID
+ _RSExclaveCapability
+ _RSExclaveCapability._exclaveCapability
+ _RSExclaveCapability.onceToken
+ __DATA__TtC17RelevanceServices31ManagedSettingsEligibilityInput
+ __IVARS__TtC17RelevanceServices31ManagedSettingsEligibilityInput
+ __METACLASS_DATA__TtC17RelevanceServices31ManagedSettingsEligibilityInput
+ ___RSExclaveCapability_block_invoke
+ ___swift__destructor
+ _associated conformance 17RelevanceServices31ManagedSettingsEligibilityInputC0E6Quorum0eF0AA6StreamAdEP_Sci
+ _objc_alloc
+ _swift_deletedMethodError
+ _swift_release_x23
+ _swift_release_x9
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic $s17EligibilityQuorum0A5InputP
+ _symbolic SbSg
+ _symbolic ScSy_____G 17EligibilityQuorum0A6ResultO
+ _symbolic _____ 17RelevanceServices31ManagedSettingsEligibilityInputC
+ _symbolic _____Sg 7Combine14AnyCancellableC
+ _symbolic _____SgXw 17RelevanceServices31ManagedSettingsEligibilityInputC
+ _symbolic _____y_____G s11_SetStorageC 15ManagedSettings0D9GroupNameO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15ManagedSettings0E9GroupNameO
+ _symbolic _____y______G ScS12ContinuationV 17EligibilityQuorum0B6ResultO
+ _symbolic _____y_______G ScS12ContinuationV11YieldResultO 17EligibilityQuorum0dC0O
+ _symbolic _____y_______G ScS12ContinuationV15BufferingPolicyO 17EligibilityQuorum0D6ResultO
CStrings:
+ "704c505e-d459-42a9-b3b1-81b4cfa5911d"
+ "Managed settings: denySiri=%s, denySiriAI=%s, shouldDeny: %{bool}d"
- "com.apple.RelevancePlatform.MindPalaceActiveStateDidChange"
- "com.apple.RelevancePlatform.MindPalaceGlobalEnabledDidChange"
```
