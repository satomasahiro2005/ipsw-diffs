## MomentsUIService

> `/Applications/MomentsUIService.app/MomentsUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29089c` | `0x291504` | **`+0xc68`** |
| `__TEXT.__oslogstring` | `0xd6e3` | `0xda03` | **`+0x320`** |
| `__DATA_CONST.__cfstring` | `0x1fc0` | `0x2140` | **`+0x180`** |
| `__TEXT.__objc_methname` | `0x12565` | `0x126b5` | **`+0x150`** |
| `__TEXT.__cstring` | `0xa048` | `0xa158` | **`+0x110`** |
| `__DATA.__objc_const` | `0xc960` | `0xca00` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x9400` | `0x9480` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x104f0` | `0x10568` | **`+0x78`** |
| `__TEXT.__objc_methtype` | `0x3d39` | `0x3d79` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x4064` | `0x4094` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x3668` | `0x3690` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x204` | `0x22c` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x76f0` | `0x7718` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0xd4` | `0xe8` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x1b98` | `0x1ba8` | **`+0x10`** |
| `__TEXT.__const` | `0xb3b4` | `0xb3c4` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-502.0.5.0.0
+502.0.8.0.0

-  Functions: 11030
-  Symbols:   26528
-  CStrings:  4968
+  Functions: 11037
+  Symbols:   26551
+  CStrings:  5003
Symbols:
+ -[MOConfigurationManagerBase initWithDefaultsManager:enableTrialClient:eligibilityProvider:]
+ -[MOConfigurationManagerBase isActionSuggestionsEligible]
+ -[MOConfigurationManagerBase isAutomaticPSSDonationEnabled]
+ -[MOConfigurationManagerBase refreshActionSuggestionsSnapshot]
+ GCC_except_table24
+ GCC_except_table3
+ OBJC_IVAR_$_MOConfigurationManagerBase._asFetchInFlight
+ OBJC_IVAR_$_MOConfigurationManagerBase._cachedActionSuggestionsEligible
+ OBJC_IVAR_$_MOConfigurationManagerBase._cachedExtendedRetentionFeatureEnabled
+ OBJC_IVAR_$_MOConfigurationManagerBase._cachedExtendedRetentionInternalEnabled
+ OBJC_IVAR_$_MOConfigurationManagerBase._cachedExtendedRetentionManualEnable
+ OBJC_IVAR_$_MOConfigurationManagerBase._eligibilityProvider
+ __62-[MOConfigurationManagerBase refreshActionSuggestionsSnapshot]_block_invoke
+ ___62-[MOConfigurationManagerBase refreshActionSuggestionsSnapshot]_block_invoke
+ ___62-[MOConfigurationManagerBase refreshActionSuggestionsSnapshot]_block_invoke_2
+ ___block_descriptor_48_e8_32s40r_e5_v8?0ls32l8r40l8
+ ___block_descriptor_48_e8_32s40s_e20_v24?0q8"NSError"16ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_88_e8_32s40r48r56r64r72r80r_e5_v8?0ls32l8r40l8r48l8r56l8r64l8r72l8r80l8
+ ___kCFBooleanFalse
+ ___kCFBooleanTrue
+ _objc_msgSend$fDefaultsManager
+ _objc_msgSend$fetchFeatureStatusWithCompletion:
+ _objc_msgSend$initWithDefaultsManager:enableTrialClient:eligibilityProvider:
+ _objc_msgSend$isActionSuggestionsEligible
+ _objc_msgSend$refreshActionSuggestionsSnapshot
- OBJC_IVAR_$_MOConfigurationManagerBase._cachedMFeatureEnabled
- ___block_descriptor_56_e8_32s40r48r_e5_v8?0ls32l8r40l8r48l8
- _objc_msgSend$initWithDefaultsManager:enableTrialClient:
CStrings:
+ "@\"<MOActionSuggestionEligibilityProviding>\""
+ "@36@0:8@16B24@28"
+ "AS eligibility fetch already in-flight; skipping duplicate request"
+ "AS eligibility indeterminate (%@); holding last verdict"
+ "AS eligibility resolved from snapshot: %@ (age %.0fs)"
+ "AS eligibility snapshot updated: disabled (immediate)"
+ "AS eligibility snapshot updated: enabled"
+ "AS eligibility: no persisted snapshot yet -> ineligible (fail closed)"
+ "AS eligibility: snapshot stale (age %.0fs > %.0fs) -> ineligible"
+ "Automatic PSS donation override present: %@"
+ "Configuration cache FROZEN for refresh: ActionSuggestionsEligible=%@, InternalEnabled=%@, expires at %@"
+ "Default (28d)"
+ "Extended (84d)"
+ "ExtendedRetentionFeatureEnabled"
+ "ExtendedRetentionInternalEnabled"
+ "ExtendedRetentionManualEnable"
+ "PSSActionSuggestionsLastKnownEligible"
+ "PSSActionSuggestionsSnapshotDate"
+ "PSSCascadeDonationEnabled"
+ "Retention profile for this refresh: %@ [FeatureEnabled=%d, InternalEnabled=%d, Manual=%d, ActionSuggestionsEligible=%d, isInternalBuild=%d, GLP=%d]"
+ "Threshold profile: useExtendedProfile=%d (FeatureEnabled=%d, InternalEnabled=%d, Manual=%d, ActionSuggestionsEligible=%d, isInternalBuild=%d) for key: %@"
+ "Using CACHED useExtendedProfile=%d for key: %@ (expires in %.0fs)"
+ "_asFetchInFlight"
+ "_cachedActionSuggestionsEligible"
+ "_cachedExtendedRetentionFeatureEnabled"
+ "_cachedExtendedRetentionInternalEnabled"
+ "_cachedExtendedRetentionManualEnable"
+ "_eligibilityProvider"
+ "eligible"
+ "fetchFeatureStatusWithCompletion:"
+ "force-off"
+ "force-on"
+ "ineligible"
+ "initWithDefaultsManager:enableTrialClient:eligibilityProvider:"
+ "isActionSuggestionsEligible"
+ "isAutomaticPSSDonationEnabled"
+ "notDetermined"
+ "refreshActionSuggestionsSnapshot"
+ "v24@?0q8@\"NSError\"16"
- "Configuration cache FROZEN for refresh: MFeatureEnabled=%@, expires at %@"
- "MFeatureEnabled"
- "Using CACHED MFeatureEnabled=%d for key: %@ (expires in %.0fs)"
- "_cachedMFeatureEnabled"
```
