## ModelCatalogRuntime

> `/System/Library/PrivateFrameworks/ModelCatalogRuntime.framework/ModelCatalogRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83d60` | `0x89e64` | **`+0x6104`** |
| `__AUTH_CONST.__const` | `0x4590` | `0x4cf0` | **`+0x760`** |
| `__DATA.__bss` | `0x1a10` | `0x1f90` | **`+0x580`** |
| `__TEXT.__cstring` | `0x14fb` | `0x191b` | **`+0x420`** |
| `__TEXT.__const` | `0x30a8` | `0x3458` | **`+0x3b0`** |
| `__TEXT.__oslogstring` | `0x432a` | `0x458a` | **`+0x260`** |
| `__TEXT.__unwind_info` | `0x1cb8` | `0x1e70` | **`+0x1b8`** |
| `__TEXT.__swift5_capture` | `0x1414` | `0x15c4` | **`+0x1b0`** |
| `__TEXT.__swift5_typeref` | `0x1a26` | `0x1bb6` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x4464` | `0x4574` | **`+0x110`** |
| `__TEXT.__swift5_fieldmd` | `0xbcc` | `0xcc8` | **`+0xfc`** |
| `__DATA.__data` | `0x768` | `0x830` | **`+0xc8`** |
| `__TEXT.__constg_swiftt` | `0x1244` | `0x1300` | **`+0xbc`** |
| `__TEXT.__swift5_reflstr` | `0xa23` | `0xad3` | **`+0xb0`** |
| `__AUTH_CONST.__auth_got` | `0x1490` | `0x14e0` | **`+0x50`** |
| `__DATA_DIRTY.__common` | `0x398` | `0x3d8` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x17c` | `0x1ac` | **`+0x30`** |
| `__DATA.__common` | `0x18` | `0x40` | **`+0x28`** |
| `__TEXT.__swift5_assocty` | `0x1d8` | `0x1f0` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x110` | `0x124` | **`+0x14`** |
| `__TEXT.__swift5_protos` | `0x4c` | `0x50` | **`+0x4`** |

### Other Changes

```diff

-302.1.0.2.0
+302.6.0.1.100

-  Functions: 3176
-  Symbols:   248
-  CStrings:  342
+  Functions: 3315
+  Symbols:   252
+  CStrings:  372
Symbols:
+ __CFXPCCreateCFObjectFromXPCObject
+ _notify_post
+ _os_eligibility_get_domain_answer
+ _swift_retain_x9
CStrings:
+ "Failed to post asset set updated notification for %s: %u"
+ "NOT_YET_AVAILABLE"
+ "OSEligibilityProbe: domain %{public}s answer=%{public}s countryPolicy=[%{public}s] isChina=%{bool}d"
+ "OSEligibilityProbe: domain %{public}s returned no context dictionary"
+ "OSEligibilityProbe: query for domain %{public}s failed with status %d"
+ "OSEligibilityProbe: querying domain %{public}s"
+ "OS_ELIGIBILITY_CONTEXT_COUNTRY_POLICY"
+ "bm_deviceInfo('deviceType')"
+ "bm_deviceInfo('isInternalBuild')"
+ "bm_featureFlagValue('"
+ "bm_gmBypass('adm')"
+ "bm_gmBypass('afm')"
+ "bm_isBuddyComplete()"
+ "bm_isSeedBuild()"
+ "bm_mobileGestalt('chipID')"
+ "bm_mobileGestalt('deviceSupportsGenerativeModelSystems')"
+ "bm_mobileGestalt('deviceSupportsHandwritingSynthesisModel')"
+ "bm_mobileGestalt('hardwarePlatform')"
+ "bm_mobileGestalt('isSimulator')"
+ "bm_osEligibility"
+ "bm_osEligibility received unknown domain: %{public}s"
+ "bm_osEligibility('copernicium', false)"
+ "bm_osEligibility(domain: %{public}s, allowChinaCountryPolicy: %{bool}d) -> answer: %{public}s, countryPolicy: [%{public}s], isChina: %{bool}d, result: %{bool}d"
+ "bm_userDefaults('com.apple.MobileSMS', 'IncludeSmartRepliesKey')"
+ "bm_userDefaults('com.apple.ModelCatalog.SpotlightKnowledge', 'AEMPreviousEmbeddingModelVersion')"
+ "bm_userDefaults('com.apple.spatialphotosrelive', 'LocallyDisabled')"
+ "com.apple.modelcatalog.agent.launchevents"
+ "com.apple.modelcatalog.asset-set-updated."
+ "com.apple.os-eligibility-domain.change.copernicium"
+ "copernicium"
+ "evaluationInputs"
- "com.apple.modelcatalog.launchevents.registration"
```
