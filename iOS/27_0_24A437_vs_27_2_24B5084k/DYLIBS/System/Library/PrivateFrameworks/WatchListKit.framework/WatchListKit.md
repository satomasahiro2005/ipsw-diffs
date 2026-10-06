## WatchListKit

> `/System/Library/PrivateFrameworks/WatchListKit.framework/WatchListKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66ba0` | `0x68394` | **`+0x17f4`** |
| `__DATA_CONST.__const` | `0x27a0` | `0x29a8` | **`+0x208`** |
| `__TEXT.__cstring` | `0x7dfa` | `0x7f44` | **`+0x14a`** |
| `__DATA_CONST.__objc_selrefs` | `0x3a20` | `0x3aa0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x6492` | `0x6506` | **`+0x74`** |
| `__AUTH_CONST.__objc_const` | `0x11ce8` | `0x11d50` | **`+0x68`** |
| `__AUTH_CONST.__cfstring` | `0xa6c0` | `0xa720` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x7174` | `0x71d4` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1e00` | `0x1e58` | **`+0x58`** |
| `__DATA.__objc_ivar` | `0xa4c` | `0xa54` | **`+0x8`** |

### Other Changes

```diff

-952.0.1.0.0
+952.10.6.0.0

-  Functions: 2784
-  Symbols:   5616
-  CStrings:  1927
+  Functions: 2812
+  Symbols:   5649
+  CStrings:  1943
Symbols:
+ +[NSURL(WLKAdditions) _wlk_URLWithServerConfig:fullPath:endpoint:queryParameters:suppressParameterEncoding:ignoreUserLocation:]
+ +[NSURL(WLKAdditions) wlk_URLWithServerConfig:endpoint:baseURLString:queryParameters:suppressParameterEncoding:ignoreUserLocation:]
+ +[WLKConfigurationRequest _configURLStringWithCompletion:]
+ -[WLKSystemPreferencesStore alwaysShowProfileSelection]
+ -[WLKSystemPreferencesStore setAlwaysShowProfileSelection:]
+ -[WLKSystemPreferencesStore setSignLanguageEnabled:]
+ -[WLKSystemPreferencesStore signLanguageEnabled]
+ -[WLKURLRequestProperties URLRequestWithConfiguration:baseURLString:]
+ GCC_except_table44
+ _OBJC_IVAR_$_WLKSystemPreferencesStore._preferencesCache
+ _OBJC_IVAR_$_WLKSystemPreferencesStore._preferencesCacheLock
+ ___51-[WLKUTSNetworkRequestOperation prepareURLRequest:]_block_invoke_2
+ ___55+[WLKURLBagUtilities isFullTVAppEnabledWithCompletion:]_block_invoke_2
+ ___58+[WLKConfigurationRequest _configURLStringWithCompletion:]_block_invoke
+ ___58+[WLKConfigurationRequest _configURLStringWithCompletion:]_block_invoke_2
+ ___58+[WLKConfigurationRequest _configURLStringWithCompletion:]_block_invoke_3
+ ___58+[WLKConfigurationRequest _configURLStringWithCompletion:]_block_invoke_4
+ ___61+[WLKSettingsCloudUtilities _cloudSyncEnabledWithCompletion:]_block_invoke_2
+ ___61+[WLKSettingsCloudUtilities _cloudSyncEnabledWithCompletion:]_block_invoke_3
+ ___61+[WLKSettingsCloudUtilities _cloudSyncEnabledWithCompletion:]_block_invoke_4
+ ___WLKFetchBaseURLWithCompletion_block_invoke_2
+ ___WLKFetchNowPlayingEnabledReturningError_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e27_v24?0"NSURL"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32bs_e30_v24?0"NSNumber"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32bs_e30_v24?0"NSString"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32bs_e38_v32?0"NSURL"8"NSURL"16"NSNumber"24ls32l8
+ ___block_descriptor_48_e8_32bs_e37_v32?0"NSURL"8"NSURL"16"NSError"24ls32l8
+ ___block_descriptor_48_e8_32s40bs_e18_v16?0"NSString"8ls40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e30_v24?0"NSNumber"8"NSError"16ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e30_v24?0"NSString"8"NSError"16ls48l8s32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e8_v16?0Q8ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48bs_e30_v24?0"NSNumber"8"NSError"16ls48l8s32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e22_v16?0"NSURLRequest"8ls32l8s40l8s56l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls56l8s32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48bs_e30_v24?0"NSString"8"NSError"16ls48l8s32l8s40l8
- GCC_except_table36
- GCC_except_table41
CStrings:
+ "%@: tricycle enabled but base URL could not be resolved from the V3 bag"
+ "-[WLKURLRequestProperties URLRequestWithConfiguration:baseURLString:]"
+ "AlwaysShowProfileSelection"
+ "NSURL-WLKAdditions: Failed to fetch baseURL"
+ "SignLanguageEnabled"
+ "sp_personal"
+ "sparkle_related_v2"
+ "sparkle_v2"
+ "tricycle"
+ "v16@?0@\"NSString\"8"
+ "v16@?0@\"NSURLRequest\"8"
+ "v16@?0Q8"
+ "v24@?0@\"NSNumber\"8@\"NSError\"16"
+ "v24@?0@\"NSString\"8@\"NSError\"16"
+ "v24@?0@\"NSURL\"8@\"NSError\"16"
+ "v32@?0@\"NSURL\"8@\"NSURL\"16@\"NSError\"24"
+ "v32@?0@\"NSURL\"8@\"NSURL\"16@\"NSNumber\"24"
- "-[WLKURLRequestProperties URLRequestWithConfiguration:]"
```
