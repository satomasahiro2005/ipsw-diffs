## APTransport

> `/System/Library/PrivateFrameworks/APTransport.framework/APTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3004f` | `0x3089c` | **`+0x84d`** |
| `__TEXT.__text` | `0xb5504` | `0xb5c2c` | **`+0x728`** |
| `__DATA_CONST.__const` | `0x3d60` | `0x3db8` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0x65c0` | `0x6600` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x9d8` | `0x9fc` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0x2dd8` | `0x2db8` | **`-0x20`** |
| `__DATA.__bss` | `0x138` | `0x128` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b90` | `0x1ba0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2d10` | `0x2d20` | **`+0x10`** |

### Other Changes

```diff

-980.67.2.0.0
+980.71.1.0.0

-  Functions: 5342
-  Symbols:   4384
-  CStrings:  4543
+  Functions: 5352
+  Symbols:   4390
+  CStrings:  4563
Symbols:
+ GCC_except_table36
+ _APTNANDataSessionAutoPairWithCompletion
+ _NSSelectorFromString
+ __APTNANDataSessionCreateSession
+ ___36-[APBonjourCacheManager _invalidate]_block_invoke
+ ___APTNANDataSessionAutoPairWithCompletion_block_invoke
+ ___APTNANDataSessionAutoPairWithCompletion_block_invoke_2
+ ____APTNANDataSessionActivateAndWait_block_invoke
+ ____APTNANDataSessionCreateSession_block_invoke
+ ____APTNANDataSessionSetupSessionHandlers_block_invoke
+ ____APTNANDataSessionSetupSessionHandlers_block_invoke_2
+ ____APTNANDataSessionSetupSessionHandlers_block_invoke_3
+ ____APTNANDataSessionSetupSessionHandlers_block_invoke_4
+ ____APTNANDataSessionSetupSessionHandlers_block_invoke_5
+ ___block_descriptor_40_e8_32r_e8_v12?0i8lr32l8
+ ___block_descriptor_56_e8_32o40b_e17_v16?0"NSError"8ls40l8s32l8
+ ___block_descriptor_64_e8_32o40o48b_e17_v16?0"NSError"8ls32l8s48l8s40l8
+ ___block_descriptor_72_e8_32o40b_e5_v8?0ls40l8s32l8
+ ___block_descriptor_97_e8_32o40r48r56r64r_e21_v16?0^{__CFNumber=}8lr40l8r48l8s32l8r56l8r64l8
+ _kAPTTerminusMonitorDeviceInfoKey_IsRoutedViaPrimaryAssist
- __APTNANDataSessionCreatePINFromSharedSecret
- __APTNANDataSessionGenerateDiversifiedPIN
- __APTNANDataSessionGetDispatchQueue.sAPTNANDataSessionDispatchQueue
- __APTNANDataSessionGetDispatchQueue.sAPTNANDataSessionDispatchQueueOnce
- ___APTNANDataSessionRetainActivation_block_invoke_2
- ___APTNANDataSessionRetainActivation_block_invoke_3
- ___APTNANDataSessionRetainActivation_block_invoke_4
- ___APTNANDataSessionRetainActivation_block_invoke_5
- ___APTNANDataSessionRetainActivation_block_invoke_6
- ___APTNANDataSessionRetainActivation_block_invoke_7
- ____APTNANDataSessionGetDispatchQueue_block_invoke
- ___block_descriptor_72_e8_32o40o48r_e17_v16?0"NSError"8ls32l8r48l8s40l8
- ___block_descriptor_88_e8_32o40o48o56r_e5_v8?0lr56l8s32l8s40l8s48l8
- ___block_descriptor_89_e8_32o40r48r56r_e21_v16?0^{__CFNumber=}8lr40l8r48l8s32l8r56l8
CStrings:
+ "-[APBonjourCacheManager _ensureKnownNetworkProfileMonitoringStarted]"
+ "980.71.1"
+ "APTNANDataSession.%{ptr}.dataSession"
+ "APTNANDataSessionAutoPairWithCompletion"
+ "Boolean APTransportDeviceIsReachable(APTransportDeviceRef, APTransportDeviceAddressType, CFDictionaryRef _Nullable, Boolean * _Nullable, APTransportDeviceUnavailableReason * _Nullable)"
+ "Boolean APTransportDeviceWaitForReachability(APTransportDeviceRef, APTransportDeviceAddressType, int64_t, dispatch_semaphore_t _Nullable, CFDictionaryRef _Nullable, APTransportDeviceUnavailableReason * _Nullable)"
+ "Boolean APTransportDeviceWaitForReachability(APTransportDeviceRef, APTransportDeviceAddressType, int64_t, dispatch_semaphore_t _Nullable, CFDictionaryRef _Nullable, APTransportDeviceUnavailableReason * _Nullable)_block_invoke"
+ "Boolean transportDevice_isNANRecommended(APTransportDeviceRef, OSStatus *, APTransportDeviceUnavailableReason *)"
+ "CFStringRef _APTNANDataSessionCreatePINFromSharedSecret(APTNANDataSessionRef, CUNANDataSession *, OSStatus *)"
+ "Ignoring known network profile monitoring on VirtualMachine"
+ "IsRoutedViaPrimaryAssist"
+ "NANDS [%{ptr}] AutoPair %s%?{end}: %@"
+ "NANDS [%{ptr}] AutoPair not supported for SecureNAN"
+ "NANDS [%{ptr}] AutoPair session invalidated"
+ "NANDS [%{ptr}] Peer is not AutoPairable"
+ "NANDS [%{ptr}] Starting AutoPair with %'@"
+ "OSStatus APTNANDataSessionAutoPairWithCompletion(APTNANDataSessionRef, APTNANDataSessionAutoPairCompletion)"
+ "OSStatus APTNANDataSessionAutoPairWithCompletion(APTNANDataSessionRef, APTNANDataSessionAutoPairCompletion)_block_invoke"
+ "OSStatus APTNANDataSessionAutoPairWithCompletion(APTNANDataSessionRef, APTNANDataSessionAutoPairCompletion)_block_invoke_2"
+ "OSStatus _APTNANDataSessionActivateAndWait(APTNANDataSessionRef, CUNANDataSession *, dispatch_semaphore_t, APTNANDataSessionSetActivationErrorBlock)_block_invoke"
+ "OSStatus _APTNANDataSessionCreateAndConfigureUnifiedPairingDelegateIfNecessary(APTNANDataSessionRef, CUNANDataSession *, APTNANPairingDelegate **)"
+ "OSStatus _APTNANDataSessionCreateSession(APTNANDataSessionRef, CUNANDataSession **)"
+ "OSStatus _APTNANDataSessionCreateSession(APTNANDataSessionRef, CUNANDataSession **)_block_invoke"
+ "OSStatus _APTNANDataSessionGenerateDiversifiedPIN(APTNANDataSessionRef, CUNANDataSession *, CFStringRef *)"
+ "OSStatus _APTNANDataSessionGenerateDiversifiedPIN(APTNANDataSessionRef, CUNANDataSession *, CFStringRef *)_block_invoke"
+ "OSStatus _APTNANDataSessionHandleUnifiedPairingIfNecessary(APTNANDataSessionRef, CUNANDataSession *, APTNANPairingDelegate *, OSStatus)"
+ "OSStatus _APTNANDataSessionSetupSessionHandlers(APTNANDataSessionRef, CUNANDataSession *, dispatch_semaphore_t *, APTNANDataSessionSetActivationErrorBlock)"
+ "OSStatus _APTNANDataSessionSetupSessionHandlers(APTNANDataSessionRef, CUNANDataSession *, dispatch_semaphore_t *, APTNANDataSessionSetActivationErrorBlock)_block_invoke"
+ "OSStatus _APTNANDataSessionSetupSessionHandlers(APTNANDataSessionRef, CUNANDataSession *, dispatch_semaphore_t *, APTNANDataSessionSetActivationErrorBlock)_block_invoke_2"
+ "OSStatus _APTNANDataSessionSetupSessionHandlers(APTNANDataSessionRef, CUNANDataSession *, dispatch_semaphore_t *, APTNANDataSessionSetActivationErrorBlock)_block_invoke_4"
+ "OSStatus _APTNANDataSessionSetupSessionHandlers(APTNANDataSessionRef, CUNANDataSession *, dispatch_semaphore_t *, APTNANDataSessionSetActivationErrorBlock)_block_invoke_5"
+ "_APTNANDataSessionActivateAndWait"
+ "_APTNANDataSessionCreateAndConfigureUnifiedPairingDelegateIfNecessary"
+ "_APTNANDataSessionCreateSession"
+ "_APTNANDataSessionHandleUnifiedPairingIfNecessary"
+ "_APTNANDataSessionSetupSessionHandlers"
+ "_APTNANDataSessionSetupSessionHandlers_block_invoke_4"
+ "autoPairWithCompletion:"
+ "nanActivationRetryBackoffMs"
- "980.67.2"
- "APTNANDataSessionRetainActivation_block_invoke_5"
- "Boolean APTransportDeviceIsReachable(APTransportDeviceRef, APTransportDeviceAddressType, CFDictionaryRef _Nullable, Boolean * _Nullable)"
- "Boolean APTransportDeviceWaitForReachability(APTransportDeviceRef, APTransportDeviceAddressType, int64_t, dispatch_semaphore_t _Nullable, CFDictionaryRef _Nullable)"
- "Boolean APTransportDeviceWaitForReachability(APTransportDeviceRef, APTransportDeviceAddressType, int64_t, dispatch_semaphore_t _Nullable, CFDictionaryRef _Nullable)_block_invoke"
- "Boolean transportDevice_isNANRecommended(APTransportDeviceRef, OSStatus *)"
- "CFStringRef _APTNANDataSessionCreatePINFromSharedSecret(APTNANDataSessionRef, OSStatus *)"
- "OSStatus APTNANDataSessionRetainActivation(APTNANDataSessionRef)_block_invoke"
- "OSStatus APTNANDataSessionRetainActivation(APTNANDataSessionRef)_block_invoke_2"
- "OSStatus APTNANDataSessionRetainActivation(APTNANDataSessionRef)_block_invoke_3"
- "OSStatus APTNANDataSessionRetainActivation(APTNANDataSessionRef)_block_invoke_5"
- "OSStatus APTNANDataSessionRetainActivation(APTNANDataSessionRef)_block_invoke_6"
- "OSStatus APTNANDataSessionRetainActivation(APTNANDataSessionRef)_block_invoke_7"
- "OSStatus _APTNANDataSessionGenerateDiversifiedPIN(APTNANDataSessionRef, CFStringRef *)"
- "OSStatus _APTNANDataSessionGenerateDiversifiedPIN(APTNANDataSessionRef, CFStringRef *)_block_invoke"
- "[%{ptr}] NAN [%{ptr}] not recommended due to signal strength of %f with threshold of %f"
- "_APAdvertiserInfoCompare"
- "com.apple.airplay.APTNANDataSession"
- "nanActivationRetryInitialBackoffMs"
```
