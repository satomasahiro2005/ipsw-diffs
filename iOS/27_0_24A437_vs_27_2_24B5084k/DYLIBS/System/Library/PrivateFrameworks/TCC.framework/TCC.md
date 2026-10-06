## TCC

> `/System/Library/PrivateFrameworks/TCC.framework/TCC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15c74` | `0x16694` | **`+0xa20`** |
| `__TEXT.__cstring` | `0x3389` | `0x3547` | **`+0x1be`** |
| `__TEXT.__oslogstring` | `0x1665` | `0x1796` | **`+0x131`** |
| `__DATA_CONST.__const` | `0x1870` | `0x1920` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x1720` | `0x17a0` | **`+0x80`** |
| `__DATA.__data` | `0x958` | `0x970` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x618` | `0x630` | **`+0x18`** |

### Other Changes

```diff

-913.0.1.0.0
+918.0.0.0.0

-  Functions: 598
-  Symbols:   962
-  CStrings:  611
+  Functions: 614
+  Symbols:   974
+  CStrings:  631
Symbols:
+ _OUTLINED_FUNCTION_12
+ _TCCAccessCopyAuthorizationsFromBundleId
+ _TCCCopyIconIdentifierForService
+ ___TCCAccessCopyAuthorizationsFromBundleId_block_invoke
+ ___TCCAccessCopyAuthorizationsFromBundleId_block_invoke_2
+ ___TCCCopyIconIdentifierForService_block_invoke
+ ___TCCCopyIconIdentifierForService_block_invoke_2
+ _kTCCServiceAccessoryWorker
+ _kTCCServiceAccessoryWorkerGPU
+ _kTCCServiceMotionSensors
+ _tcc_authorization_record_get_eligible_for_reprompt
+ _tcc_authorization_record_set_eligible_for_reprompt
CStrings:
+ "%{public}s Requesting icon identifier for %s"
+ "%{public}s: both source and destination bundle identifiers are required"
+ "%{public}s: failed to convert bundle identifiers"
+ "%{public}s: identifier for %{public}s return NULL"
+ "Eligible For Reprompt, "
+ "TCCAccessCopyAuthorizations"
+ "TCCAccessCopyAuthorizationsFromBundleId"
+ "TCCAccessCopyAuthorizationsFromBundleId() IPC"
+ "TCCAccessCopyAuthorizationsFromBundleId_block_invoke_2"
+ "TCCCopyIconIdentifierForService"
+ "TCCCopyIconIdentifierForService() Sync IPC"
+ "TCCCopyIconIdentifierForService_block_invoke"
+ "TCCCopyIconIdentifierForService_block_invoke_2"
+ "TCCD_MSG_MESSAGE_ELIGIBLE_FOR_REPROMPT"
+ "destination_bundle_id"
+ "iconIdentifier"
+ "kTCCServiceAccessoryWorker"
+ "kTCCServiceAccessoryWorkerGPU"
+ "kTCCServiceMotionSensors"
+ "source_bundle_id"
```
