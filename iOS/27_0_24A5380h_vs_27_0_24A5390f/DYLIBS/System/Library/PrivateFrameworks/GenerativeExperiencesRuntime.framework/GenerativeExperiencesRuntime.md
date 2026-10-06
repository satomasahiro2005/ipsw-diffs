## GenerativeExperiencesRuntime

> `/System/Library/PrivateFrameworks/GenerativeExperiencesRuntime.framework/GenerativeExperiencesRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe7014` | `0xeab80` | **`+0x3b6c`** |
| `__TEXT.__eh_frame` | `0x90ec` | `0x941c` | **`+0x330`** |
| `__TEXT.__oslogstring` | `0x8760` | `0x89a0` | **`+0x240`** |
| `__AUTH_CONST.__objc_const` | `0x3150` | `0x3248` | **`+0xf8`** |
| `__AUTH.__data` | `0x430` | `0x508` | **`+0xd8`** |
| `__TEXT.__const` | `0x5a7c` | `0x5b4c` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x33a0` | `0x3468` | **`+0xc8`** |
| `__DATA.__bss` | `0x2770` | `0x27f0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1e65` | `0x1ed5` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x1ea8` | `0x1f14` | **`+0x6c`** |
| `__AUTH_CONST.__const` | `0x8428` | `0x8488` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0xffd` | `0x104d` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x6fc` | `0x73c` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x32d0` | `0x3298` | **`-0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x1428` | `0x145c` | **`+0x34`** |
| `__AUTH_CONST.__auth_got` | `0x2780` | `0x27b0` | **`+0x30`** |
| `__DATA.__data` | `0xad8` | `0xb08` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x286c` | `0x2898` | **`+0x2c`** |
| `__DATA.__common` | `0x78` | `0xa0` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x276c` | `0x2794` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x334` | `0x350` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x354` | `0x368` | **`+0x14`** |
| `__TEXT.__objc_methlist` | `0x95c` | `0x94c` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1d0` | `0x1d8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x300` | `0x304` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x21c` | `0x220` | **`+0x4`** |

### Other Changes

```diff

-287.0.6.0.0
+291.1.0.5.0

+  - /System/Library/PrivateFrameworks/DeviceConfiguration.framework/DeviceConfiguration

-  Functions: 5122
-  Symbols:   282
-  CStrings:  647
+  Functions: 5187
+  Symbols:   283
+  CStrings:  656
Symbols:
+ _swift_task_isCancelledWithFlags
CStrings:
+ "AvailabilityDeviceConfiguration.restrictedUseCases()"
+ "Device Configuration fetch failed: %{public}@"
+ "Device Configuration unavailable; preserving previous MDM restrictions"
+ "EnhancedSiriVisibility: migration cleared stale hasAppEverBeenInstalled (non-EU, bit set but app not installed) to allow reinstall."
+ "Failed to subscribe to Device Configuration changes: %@"
+ "ForceVisualIntelligenceDisallowed"
+ "GenerativeAppsVisibility: Request to install %{public}s accepted."
+ "Received DeviceConfiguration change for %{public}s"
+ "Skipping availability report: base availability not yet cached this boot."
+ "WARNING: forcing allowVisualIntelligence=false"
+ "[End] checking Device Configuration"
+ "[Start] checking Device Configuration"
+ "allowVisualIntelligence"
+ "com.apple.externalproviderservice-xpc"
+ "com.apple.generativeexperiences.deviceConfiguration.modelCatalogChanged"
+ "updatePQAIndexingReadiness: PQA CSF push failed: %{public}@"
+ "updatePQAIndexingReadiness: PQA CSF push succeeded"
+ "updatePQAIndexingReadiness: single-flight task already running, skipping"
- "GenerativeAppsVisibility: Request to install %{public}s succeeded."
- "XPC: %{public}s called with TCC service: %{public}s"
- "XPC: %{public}s called with TCC service: %{public}s, app bundle ID: %{public}s"
- "com.apple.externalproviderservice"
- "tccAuthorizedBundleIdentifiers(service:reply:)"
- "tccForceAuthorize(service:for:)"
- "tccForceReset(service:for:)"
- "updatePQAIndexingReadiness: CSF push failed: %{public}@"
- "updatePQAIndexingReadiness: CSF push succeeded"
```
