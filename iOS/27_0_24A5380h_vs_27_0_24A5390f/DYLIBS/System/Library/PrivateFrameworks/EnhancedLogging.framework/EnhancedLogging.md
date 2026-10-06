## EnhancedLogging

> `/System/Library/PrivateFrameworks/EnhancedLogging.framework/EnhancedLogging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3dda4` | `0x3f9dc` | **`+0x1c38`** |
| `__TEXT.__eh_frame` | `0x1378` | `0x1510` | **`+0x198`** |
| `__DATA.__bss` | `0x6500` | `0x6680` | **`+0x180`** |
| `__TEXT.__cstring` | `0xccb` | `0xd5b` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0x5320` | `0x5388` | **`+0x68`** |
| `__TEXT.__const` | `0x3c94` | `0x3cf4` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x11a0` | `0x1200` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x1278` | `0x1234` | **`-0x44`** |
| `__AUTH_CONST.__objc_const` | `0x16c0` | `0x1688` | **`-0x38`** |
| `__DATA.__data` | `0xc50` | `0xc80` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0xa7a` | `0xaaa` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x1146` | `0x1170` | **`+0x2a`** |
| `__TEXT.__swift5_reflstr` | `0xb38` | `0xb58` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x950` | `0x968` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x258` | `0x270` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x288` | `0x2a0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xcc8` | `0xcb8` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x328` | `0x334` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x6e0` | `0x6e8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x864` | `0x85c` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x70` | `0x6c` | **`-0x4`** |

### Other Changes

```diff

-240.0.0.502.1
+251.0.0.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 2072
-  Symbols:   902
-  CStrings:  151
+  Functions: 2091
+  Symbols:   907
+  CStrings:  156
Symbols:
+ -[ELProcessingConfiguration compressionMode]
+ -[ELProcessingConfiguration initWithCompressionMode:encryptionConfiguration:]
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_IVAR_$_ELProcessingConfiguration._compressionMode
+ ___stack_chk_fail
+ ___stack_chk_guard
+ ___swift_closure_destructor.206Tm
+ _associated conformance 15EnhancedLogging11CompressionOSHAASQ
+ _associated conformance 15EnhancedLogging20ProcessingDescriptorV10CodingKeysOSHAASQ
+ _associated conformance 15EnhancedLogging20ProcessingDescriptorV10CodingKeysOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 15EnhancedLogging20ProcessingDescriptorV10CodingKeysOs0E3KeyAAs28CustomDebugStringConvertible
+ _swift_bridgeObjectRetain_n
+ _symbolic SDySSSay_____GG 15EnhancedLogging17UploadConsentItemV
+ _symbolic SDySS_____G 10Foundation3URLV
+ _symbolic SS_So8NSObjectCt
+ _symbolic _____ 15EnhancedLogging11CompressionO
+ _symbolic _____ 15EnhancedLogging20ProcessingDescriptorV10CodingKeysO
+ _symbolic _____Sg 15EnhancedLogging11CompressionO
+ _symbolic _____ySSSay_____GG s18_DictionaryStorageC 10Foundation3URLV
+ _symbolic _____ySSSo8NSObjectCG s18_DictionaryStorageC
+ _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
+ _symbolic _____ySS_____G s18_DictionaryStorageC 10Foundation3URLV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 15EnhancedLogging20ProcessingDescriptorV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 15EnhancedLogging20ProcessingDescriptorV10CodingKeysO
- -[ELProcessingConfiguration destination]
- -[ELProcessingConfiguration initWithDestination:packaging:encryptionConfiguration:]
- -[ELProcessingConfiguration packaging]
- _OBJC_IVAR_$_ELProcessingConfiguration._destination
- _OBJC_IVAR_$_ELProcessingConfiguration._packaging
- ___swift_closure_destructor.168Tm
- ___swift_memcpy128_8
- _associated conformance 15EnhancedLogging12LaunchSchemeOSHAASQ
- _associated conformance 15EnhancedLogging20ProcessingDescriptorV10CodingKeys33_45DE914E470735B513B3A45B0D08BF09LLOSHAASQ
- _associated conformance 15EnhancedLogging20ProcessingDescriptorV10CodingKeys33_45DE914E470735B513B3A45B0D08BF09LLOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 15EnhancedLogging20ProcessingDescriptorV10CodingKeys33_45DE914E470735B513B3A45B0D08BF09LLOs0E3KeyAAs28CustomDebugStringConvertible
- _symbolic SDySSSDySS_____GGIgg_ s5Int64V
- _symbolic SDySSSaySDySSypGGGIgg_
- _symbolic SDySSSay_____GG 10Foundation3URLV
- _symbolic SDySSSay_____GGSg 15EnhancedLogging17UploadConsentItemV
- _symbolic So7NSArrayCm
- _symbolic _____ 15EnhancedLogging12LaunchSchemeO
- _symbolic _____ 15EnhancedLogging20ProcessingDescriptorV10CodingKeys33_45DE914E470735B513B3A45B0D08BF09LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 15EnhancedLogging20ProcessingDescriptorV10CodingKeys33_45DE914E470735B513B3A45B0D08BF09LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 15EnhancedLogging20ProcessingDescriptorV10CodingKeys33_45DE914E470735B513B3A45B0D08BF09LLO
CStrings:
+ "On reconnect, found no active session, so clearing %s"
+ "Session %s replaced with %s"
+ "caseID"
+ "com.apple.EnhancedLogging.RemotelyInitiated"
+ "com.apple.TimberLorry.SessionGenerated"
+ "compressionMode"
+ "flat-directories"
+ "parent-directory"
- "%s(%ld)"
- "Failed to set launch scheme %@"
- "setLaunchScheme(_:)"
```
