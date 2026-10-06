## ModelCatalog

> `/System/Library/PrivateFrameworks/ModelCatalog.framework/ModelCatalog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__const` | `0xc7a58` | `0xac800` | **`-0x1b258`** |
| `__TEXT.__text` | `0x40ef24` | `0x4101b4` | **`+0x1290`** |
| `__DATA.__bss` | `0x4df80` | `0x4ec80` | **`+0xd00`** |
| `__TEXT.__const` | `0x2e25c` | `0x2e99c` | **`+0x740`** |
| `__TEXT.__unwind_info` | `0x10488` | `0x109e0` | **`+0x558`** |
| `__TEXT.__cstring` | `0x48cfe` | `0x490ce` | **`+0x3d0`** |
| `__TEXT.__eh_frame` | `0x2b1dc` | `0x2b58c` | **`+0x3b0`** |
| `__TEXT.__swift5_capture` | `0xfa2c` | `0xfdbc` | **`+0x390`** |
| `__TEXT.__constg_swiftt` | `0xc728` | `0xc8f8` | **`+0x1d0`** |
| `__TEXT.__swift5_fieldmd` | `0xd3dc` | `0xd598` | **`+0x1bc`** |
| `__AUTH.__data` | `0x8540` | `0x86b0` | **`+0x170`** |
| `__DATA.__data` | `0x6e68` | `0x6fd8` | **`+0x170`** |
| `__TEXT.__swift5_reflstr` | `0x64bf` | `0x660f` | **`+0x150`** |
| `__TEXT.__swift5_typeref` | `0x8e3c` | `0x8f38` | **`+0xfc`** |
| `__AUTH_CONST.__objc_const` | `0x5f18` | `0x5f98` | **`+0x80`** |
| `__TEXT.__swift5_proto` | `0x2d64` | `0x2dd0` | **`+0x6c`** |
| `__TEXT.__swift5_assocty` | `0x1ab0` | `0x1af8` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x1858` | `0x1898` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x21f0` | `0x21d0` | **`-0x20`** |
| `__TEXT.__swift5_types` | `0xd70` | `0xd8c` | **`+0x1c`** |
| `__TEXT.__swift_as_cont` | `0x404` | `0x410` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xf48` | `0xf50` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x278` | `0x280` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x31c` | `0x324` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x2d8` | `0x2e0` | **`+0x8`** |

### Other Changes

```diff

-302.1.0.2.0
+302.6.0.1.100

-  Functions: 33008
+  Functions: 33383

-  CStrings:  4718
+  CStrings:  4736
CStrings:
+ "Automated.Autograding.SiriPQA"
+ "AutomationTools.Zap.FMCLI.serve"
+ "ImageGenerationServicesDebiasingMetadata"
+ "InstructFMApiGenericLegacy"
+ "Invalid configuration for com.apple.fm.language.instruct_3b.fm_api_generic_legacy: "
+ "Invalid configuration for com.apple.gm.image_generation_services.debiasing.metadata: "
+ "LLMBundle alignment is wrong type"
+ "LLMBundle phrasebook is wrong type"
+ "VisualGeneration.ImagePlayground.DebiasingMetadata"
+ "WITH EligibilityInfo AS ( SELECT region, languages_json FROM \"AppleIntelligence.Availability\" ORDER BY eventTimestamp DESC LIMIT 1 ) SELECT  json_each.value AS language, NULL AS expirationDate FROM EligibilityInfo, json_each(languages_json) WHERE bm_userDefaults(\"com.apple.spatialphotosrelive\", \"LocallyDisabled\") != true AND ( (bm_deviceInfo(\"deviceType\") == \"iPad\" AND bm_mobileGestalt(\"chipID\") >= 33027) OR (bm_deviceInfo(\"deviceType\") == \"iPhone\" AND bm_mobileGestalt(\"chipID\") >= 33025) OR ( (bm_deviceInfo(\"deviceType\") == \"macDesktop\" OR bm_deviceInfo(\"deviceType\") == \"macPortable\") AND bm_osEligibility(\"copernicium\", false) == true ) )"
+ "accessibility.magnifier.reduceSensitiveTopics"
+ "alignmentVariant"
+ "com.apple.cloudos.service.recitation_agent.v1"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_legacy"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_legacy.generic"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_legacy.generic_sparse"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_legacy?variant=generic_sparse"
+ "com.apple.gm.image_generation_services.debiasing.metadata"
+ "com.apple.gm.image_generation_services.debiasing.metadata.generic"
+ "phrasebookVariant"
+ "public_display_version"
+ "translation.liveTranslation.personalTranslator"
+ "translation.liveTranslation.phoneFaceTime"
- "Invalid configuration for com.apple.fm.language.instruct_3b.video_caption: "
- "WITH EligibilityInfo AS ( SELECT region, languages_json FROM \"AppleIntelligence.Availability\" ORDER BY eventTimestamp DESC LIMIT 1 ) SELECT  json_each.value AS language, NULL AS expirationDate FROM EligibilityInfo, json_each(languages_json) WHERE bm_userDefaults(\"com.apple.spatialphotosrelive\", \"LocallyDisabled\") != true AND ( (bm_deviceInfo(\"deviceType\") == \"iPad\" AND bm_mobileGestalt(\"chipID\") >= 33027) OR (bm_deviceInfo(\"deviceType\") == \"iPhone\" AND bm_mobileGestalt(\"chipID\") >= 33025) OR (bm_deviceInfo(\"deviceType\") == \"macDesktop\" OR bm_deviceInfo(\"deviceType\") == \"macPortable\") )"
- "com.apple.fm.language.instruct_3b.video_caption.generic"
- "com.apple.fm.language.instruct_3b.video_caption.generic_sparse"
- "com.apple.fm.language.instruct_3b.video_caption?variant=generic_sparse"
```
