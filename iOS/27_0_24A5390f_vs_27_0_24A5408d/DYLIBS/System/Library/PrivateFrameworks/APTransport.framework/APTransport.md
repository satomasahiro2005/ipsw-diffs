## APTransport

> `/System/Library/PrivateFrameworks/APTransport.framework/APTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb5c2c` | `0xb68a0` | **`+0xc74`** |
| `__TEXT.__const` | `0x418` | `0x664` | **`+0x24c`** |
| `__TEXT.__cstring` | `0x3089c` | `0x30a92` | **`+0x1f6`** |
| `__DATA_CONST.__const` | `0x3db8` | `0x3e08` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2d20` | `0x2d60` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x2db8` | `0x2dd8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x9fc` | `0xa1c` | **`+0x20`** |
| `__DATA.__bss` | `0x128` | `0x130` | **`+0x8`** |

### Other Changes

```diff

-980.71.1.0.0
+980.75.1.0.0

-  Functions: 5352
-  Symbols:   4390
-  CStrings:  4563
+  Functions: 5368
+  Symbols:   4407
+  CStrings:  4574
Symbols:
+ GCC_except_table26
+ GCC_except_table31
+ GCC_except_table34
+ GCC_except_table43
+ GCC_except_table61
+ GCC_except_table62
+ GCC_except_table67
+ _APBrowserDeregisterDiscoveryQueryObserver
+ _APBrowserRegisterDiscoveryQueryObserver
+ _APTNANEndpointGetV5PairingStatus
+ ___APBrowserDeregisterDiscoveryQueryObserver_block_invoke
+ ___APBrowserDeregisterDiscoveryQueryObserver_block_invoke_2
+ ___block_descriptor_56_e8_32b_e15_v24?0r^v8r^v16ls32l8
+ ___block_descriptor_60_e15_v24?0r^v8r^v16l
+ ___browser_addPredicateObserver_block_invoke
+ ___browser_dispatchPredicateObserverNotification_block_invoke
+ ___browser_notifyDeviceObservers_block_invoke
+ ___browser_notifyPredicateObservers_block_invoke
+ ___browser_registerPredicateObserver_block_invoke
+ _browser_addPredicateObserver.sNextTokenCount
+ _browser_copyNANEndpointForDeviceIDInternal
+ _browser_dispatchPredicateObserverNotification
+ _browser_getDevicePredicate
- GCC_except_table57
- GCC_except_table58
- GCC_except_table60
- GCC_except_table63
- _OUTLINED_FUNCTION_61
- ___browser_notifyDiscoveryObservers_block_invoke
CStrings:
+ "980.75.1"
+ "APTNANDataSessionGetV5PairingStatus"
+ "H"
+ "HomePod"
+ "NANDS [%{ptr}] Infra 6GHz steer failed"
+ "NANDS [%{ptr}] Infra 6GHz steer found no candidates"
+ "NANDS [%{ptr}] Infra relay required"
+ "OSStatus _APTNANDataSessionTranslateKnownActivationError(APTNANDataSessionRef, OSStatus)"
+ "OSStatus _APTNANDataSessionTranslateKnownActivationPairingError(APTNANDataSessionRef, APTNANPairingDelegate *, OSStatus)"
+ "Predicate [ All: %{flags}, Any: %{flags} ] matched for device: %@ %{flags}"
+ "[%@:%@] %s device - name: %'@ model: %@ flags: %#ll{flags} relationship: %d systemPairingID: %@ serviceAvailable: %s\n"
+ "_APTNANDataSessionTranslateKnownActivationPairingError"
+ "browser_addPredicateObserver"
+ "browser_removePredicateObserver"
+ "void browser_notifyPredicateObservers(APBrowserRef, CFNumberRef)_block_invoke"
- "980.71.1"
- "OSStatus _APTNANDataSessionHandleUnifiedPairingIfNecessary(APTNANDataSessionRef, CUNANDataSession *, APTNANPairingDelegate *, OSStatus)"
- "[%@:%@] %s device - name: %'@ model: %@ flags: %llx relationship: %d systemPairingID: %@ serviceAvailable: %s\n"
- "fakeInfraRelayFailed"
```
