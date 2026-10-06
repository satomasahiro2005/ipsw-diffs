## SoftwareUpdateCoreSupport

> `/System/Library/PrivateFrameworks/SoftwareUpdateCoreSupport.framework/SoftwareUpdateCoreSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x83ba` | `0x7a0a` | **`-0x9b0`** |
| `__TEXT.__text` | `0x33ce8` | `0x33378` | **`-0x970`** |
| `__TEXT.__oslogstring` | `0x5248` | `0x5082` | **`-0x1c6`** |
| `__AUTH_CONST.__cfstring` | `0x8360` | `0x82e0` | **`-0x80`** |
| `__AUTH_CONST.__auth_got` | `0x3a0` | `0x3a8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1378` | `0x1380` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc70` | `0xc78` | **`+0x8`** |

### Other Changes

```diff

-2718.0.18.0.0
+2718.40.13.0.0

-  Functions: 1269
-  Symbols:   2226
-  CStrings:  1311
+  Functions: 1288
+  Symbols:   2230
+  CStrings:  1301
Symbols:
+ _OUTLINED_FUNCTION_6
+ _OUTLINED_FUNCTION_7
+ __os_log_debug_impl
+ _kSUCoreControllerSerialNumberKey
CStrings:
+ " Device(DeviceClass:%@|MarketingProductName:%@|ProductType:%@|HWModelStr:%@|BoardID:%@|HWTarget:%@)"
+ "serialNumber"
- "\n[>>>\n               targetedSystemVolume: %@\n        deviceSupportsMobileGestalt: %@\n         deviceSupportsCoreServices: %@\n deviceSupportsAppleInternalVariant: %@\n       deviceSupportsRestoreVersion: %@\n     deviceSupportsSFRSystemVersion: %@\n    deviceSupportsSFRRestoreVersion: %@\n      deviceSupportsMultiVolumeBoot: %@\n  deviceSupportsSplatRestoreVersion: %@\n   deviceSupportsSplatSystemVersion: %@\n                       buildVersion: %@\n                     productVersion: %@\n                      hwModelString: %@\n                        deviceClass: %@\n               marketingProductName: %@\n                        productType: %@\n                        releaseType: %@\n                      deviceBoardID: %@\n                           hwTarget: %@\n                         isInternal: %@\n           isBootedOSSecureInternal: %@\n                     restoreVersion: %@\n                      hasEmbeddedOS: %@\n                        hasBridgeOS: %@\n                 bridgeBuildVersion: %@\n               bridgeRestoreVersion: %@\n                   isBridgeInternal: %@\n                             hasSFR: %@\n                  sfrProductVersion: %@\n                    sfrBuildVersion: %@\n                  sfrRestoreVersion: %@\n                     sfrReleaseType: %@\n                      hasRecoveryOS: %@\n           recoveryOSProductVersion: %@\n             recoveryOSBuildVersion: %@\n           recoveryOSRestoreVersion: %@\n              recoveryOSReleaseType: %@\n              factoryRestoreVersion: %@\n     preservedFactoryRestoreVersion: %@\n                           hasSplat: %@\n        hasSplatOnlyUpdateInstalled: %@\n                splatRestoreVersion: %@\n                splatProductVersion: %@\n           splatProductVersionExtra: %@\n                  splatBuildVersion: %@\n                   splatReleaseType: %@\n                hasEligibleRollback: %@\n        splatRollbackRestoreVersion: %@\n        splatRollbackProductVersion: %@\n   splatRollbackProductVersionExtra: %@\n          splatRollbackBuildVersion: %@\n           splatRollbackReleaseType: %@\n                 hasSemiSplatActive: %@\n        splatCryptex1RestoreVersion: %@\n        splatCryptex1ProductVersion: %@\n   splatCryptex1ProductVersionExtra: %@\n          splatCryptex1BuildVersion: %@\n  splatCryptex1BuildVersionOverride: %@\n           splatCryptex1ReleaseType: %@\n<<<]"
- " Device(DeviceClass:%@|MarketingProductName:%@|ProductType:%@|HWModelStr:%@)"
- "FSM(%@) failed to create extended state dispatch queue"
- "[DIAG] DISPATCH: created dispatch queue domain(%{public}@)"
- "[DIAG_ERROR] ERROR: unable to create dispatch queue domain(%{public}@)"
- "[EVENT_REPORTER] DISPATCH | created dispatch queue domain(%{public}@.%{public}@)"
- "[EVENT_REPORTER] INIT"
- "[FSM] DISPATCH: created extended state dispatch queue domain(%{public}@.%{public}@.%{public}@)"
- "[SIMULATE] DISPATCH: created simulate dispatch queue domain(%@.%@)"
- "[SPLUNK_HISTORY] DISPATCH | created dispatch queue domain(%{public}@.%{public}@)"
- "[SPLUNK_HISTORY] INIT"
- "unable to create dispatch queue domain(%@.%@)"
```
