## NewsToday

> `/System/Library/PrivateFrameworks/NewsToday.framework/NewsToday`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x46098` | `0x45c74` | **`-0x424`** |
| `__TEXT.__gcc_except_tab` | `0xa6c` | `0xa24` | **`-0x48`** |
| `__TEXT.__cstring` | `0x9025` | `0x8ff5` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x1888` | `0x1860` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x3dc8` | `0x3da0` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1e20` | `0x1e00` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x652c` | `0x651c` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x790` | `0x798` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0xdf80` | `0xdf78` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xa88` | `0xa80` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x5cc` | `0x5c8` | **`-0x4`** |

### Other Changes

```diff

-5934.3.0.0.0
+5960.0.0.0.0

-  Functions: 2015
-  Symbols:   3268
-  CStrings:  825
+  Functions: 2011
+  Symbols:   3263
+  CStrings:  823
Symbols:
+ -[NTTodayResultsSource _fetchTodayModuleDescriptorsWithContentRequest:qualityOfService:completion:]
+ GCC_except_table16
+ ___block_descriptor_56_e8_32s40bs48bs_e108_v40?0"NTTodayResults"8"NSDictionary"16"NSObject<NTTodayResultOperationFetchInfoProviding>"24"NSError"32ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48bs56bs_e45_v32?0"NSArray"8"<NFCopying>"16"NSError"24ls32l8s48l8s56l8s40l8
+ ___block_descriptor_72_e8_32s40s48r56r64r_e74_v40?0"<FCNewsAppConfiguration>"8"NSDictionary"16"NSData"24"NSError"32ls32l8r48l8r56l8r64l8s40l8
+ _objc_retain_x10
- -[NTTodayModuleDescriptorsOperation requireRefreshedAppConfig]
- -[NTTodayModuleDescriptorsOperation setRequireRefreshedAppConfig:]
- -[NTTodayResultsSource _fetchTodayModuleDescriptorsWithContentRequest:requireRefreshedAppConfig:qualityOfService:completion:]
- GCC_except_table18
- _FCUserSegmentationEnableWidgetConfigSharedPreferenceKey
- _OBJC_IVAR_$_NTTodayModuleDescriptorsOperation._requireRefreshedAppConfig
- ___68-[NTNewsModuleDescriptorsOperation _continueOperationWithTodayData:]_block_invoke_4
- ___block_descriptor_56_e8_32s40r48r_e46_v24?0"<FCNewsAppConfiguration>"8"NSError"16lr40l8r48l8s32l8
- ___block_descriptor_64_e8_32s40s48bs56bs_e108_v40?0"NTTodayResults"8"NSDictionary"16"NSObject<NTTodayResultOperationFetchInfoProviding>"24"NSError"32ls32l8s40l8s48l8s56l8
- ___block_descriptor_72_e8_32s40s48s56bs64bs_e45_v32?0"NSArray"8"<NFCopying>"16"NSError"24ls32l8s56l8s64l8s40l8s48l8
- ___block_descriptor_80_e8_32s40s48s56r64r72r_e74_v40?0"<FCNewsAppConfiguration>"8"NSDictionary"16"NSData"24"NSError"32ls32l8r56l8r64l8r72l8s40l8s48l8
CStrings:
- "marker"
- "v24@?0@\"<FCNewsAppConfiguration>\"8@\"NSError\"16"
```
