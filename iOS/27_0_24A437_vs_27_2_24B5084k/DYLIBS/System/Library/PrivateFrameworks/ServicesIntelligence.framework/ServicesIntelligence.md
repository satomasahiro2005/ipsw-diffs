## ServicesIntelligence

> `/System/Library/PrivateFrameworks/ServicesIntelligence.framework/ServicesIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21c0d0` | `0x222478` | **`+0x63a8`** |
| `__TEXT.__unwind_info` | `0x9ec8` | `0xa498` | **`+0x5d0`** |
| `__TEXT.__eh_frame` | `0x1bab4` | `0x1bd68` | **`+0x2b4`** |
| `__TEXT.__oslogstring` | `0xa2b0` | `0xa43f` | **`+0x18f`** |
| `__TEXT.__const` | `0x21dec` | `0x21f48` | **`+0x15c`** |
| `__TEXT.__cstring` | `0x4e53` | `0x4d23` | **`-0x130`** |
| `__AUTH_CONST.__const` | `0x12938` | `0x12a58` | **`+0x120`** |
| `__DATA.__bss` | `0x2eca8` | `0x2ed80` | **`+0xd8`** |
| `__TEXT.__swift5_typeref` | `0x5ac5` | `0x5b53` | **`+0x8e`** |
| `__TEXT.__swift_as_cont` | `0x1ac8` | `0x1b28` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x4a4` | `0x4f8` | **`+0x54`** |
| `__AUTH_CONST.__auth_got` | `0x1400` | `0x13b0` | **`-0x50`** |
| `__DATA.__data` | `0x4750` | `0x4790` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x2b70` | `0x2b40` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x3df4` | `0x3e23` | **`+0x2f`** |
| `__TEXT.__swift5_fieldmd` | `0x6b78` | `0x6ba0` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0xca0` | `0xcc8` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x4ea0` | `0x4ebc` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x678` | `0x684` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1b48` | `0x1b50` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x7ec` | `0x7f0` | **`+0x4`** |

### Other Changes

```diff

-1.77.0.0.0
+1.78.0.0.0

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Functions: 10917
-  Symbols:   2842
-  CStrings:  1194
+  Functions: 10945
+  Symbols:   2841
+  CStrings:  1185
Symbols:
+ ___swift_closure_destructor.42Tm
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftCoreMIDI_$_ServicesIntelligence
+ _associated conformance 20ServicesIntelligence14SystemDatabaseV11WorkflowKeyVSHAASQ
+ _swift_release_x3
+ _symbolic SS_Sit
+ _symbolic _____ 20ServicesIntelligence14SystemDatabaseV11WorkflowKeyV
+ _symbolic _____ySDySSSiGG 20ServicesIntelligence20EnhancedMetricsEventV
+ _symbolic _____ySS_SitG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s11_SetStorageC 20ServicesIntelligence14SystemDatabaseV11WorkflowKeyV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 20ServicesIntelligence14SystemDatabaseV11WorkflowKeyV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 20ServicesIntelligence20UseCaseConfigurationV
+ _symbolic _____y_____ySDySSSiGGG 20ServicesIntelligence17LogMetricsRequestV AA08EnhancedD5EventV
+ _symbolic _____y_____ySDySSSiGGG s23_ContiguousArrayStorageC 20ServicesIntelligence20EnhancedMetricsEventV
+ _type_layout_string 20ServicesIntelligence14SystemDatabaseV11WorkflowKeyV
- __MergedGlobals
- ___isPlatformVersionAtLeast
- __availability_version_check
- __initializeAvailabilityCheck
- _compatibilityInitializeAvailabilityCheck
- _dispatch_once_f
- _dlsym
- _fclose
- _fopen
- _fread
- _fseek
- _ftell
- _initializeAvailabilityCheck
- _malloc
- _rewind
- _sscanf
CStrings:
+ "[ServicesIntelligenceProvider][repairMissingWorkflows] Could not read stored workflows: %{public}@"
+ "[ServicesIntelligenceProvider][repairMissingWorkflows] Repaired %{public}ld of %{public}ld use case(s), failed: %{public}s"
+ "[ServicesIntelligenceProvider][repairMissingWorkflows] Repaired %{public}ld use case(s)"
+ "[ServicesIntelligenceProvider][repairMissingWorkflows] Repairing %{public}ld workflow(s) in %{public}ld use case(s) at version %{public}ld: %{public}s"
+ "[SystemDatabase][storeUseCaseConfigurations] All workflows failed for use case %s"
+ "affectedUseCases"
+ "configurationWorkflowRepair"
+ "missingWorkflows"
- "%d.%d.%d"
- "/System/Library/CoreServices/SystemVersion.plist"
- "CFDataCreateWithBytesNoCopy"
- "CFDictionaryGetValue"
- "CFGetTypeID"
- "CFPropertyListCreateFromXMLData"
- "CFPropertyListCreateWithData"
- "CFRelease"
- "CFStringCreateWithCStringNoCopy"
- "CFStringGetCString"
- "CFStringGetTypeID"
- "ProductVersion"
- "[SystemDatabase][deleteUseCaseConfiguration] Deleted use case: %s, count: %lld"
- "[SystemDatabase][storeUseCaseConfigurations] All workflows failed for use case %s — use case removed"
- "https://amd-infra.itunes.apple.com/infra/ondevice/v2/podium/config"
- "kCFAllocatorNull"
- "r"
```
