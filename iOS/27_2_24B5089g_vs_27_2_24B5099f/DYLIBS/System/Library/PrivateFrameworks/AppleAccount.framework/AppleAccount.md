## AppleAccount

> `/System/Library/PrivateFrameworks/AppleAccount.framework/AppleAccount`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1aa0e4` | `0x1aa5ec` | **`+0x508`** |
| `__TEXT.__oslogstring` | `0x13aad` | `0x13bdd` | **`+0x130`** |
| `__AUTH_CONST.__const` | `0xd3a0` | `0xd460` | **`+0xc0`** |
| `__DATA.__bss` | `0x176d0` | `0x17650` | **`-0x80`** |
| `__TEXT.__const` | `0x10db0` | `0x10d60` | **`-0x50`** |
| `__AUTH_CONST.__objc_const` | `0x26c18` | `0x26bd8` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0x77a0` | `0x77d8` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x2654` | `0x262c` | **`-0x28`** |
| `__TEXT.__constg_swiftt` | `0x2a74` | `0x2a50` | **`-0x24`** |
| `__DATA.__data` | `0x281c` | `0x27fc` | **`-0x20`** |
| `__TEXT.__cstring` | `0x11532` | `0x11552` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x3a66` | `0x3a46` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x5260` | `0x5278` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x3d8` | `0x3f0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1508` | `0x1500` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1168` | `0x1160` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0xb5a4` | `0xb59c` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xbf4` | `0xbf0` | **`-0x4`** |
| `__TEXT.__swift5_proto` | `0xc74` | `0xc70` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x350` | `0x34c` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-1069.125.4.0.0
+1069.125.7.0.0

-  Functions: 9163
-  Symbols:   10033
-  CStrings:  3750
+  Functions: 9170
+  Symbols:   10029
+  CStrings:  3758
Symbols:
+ +[AALoginAccountRequest urlBagKey]
+ +[AARegisterRequest urlBagKey]
+ +[AAUpdateProvisioningRequest urlBagKey]
+ -[AADeviceList _deviceListRequestForURL:]
+ -[AARequest initWithURLConfig:]
+ -[AARequest urlConfig]
+ GCC_except_table121
+ _OBJC_CLASS_$_AKURLCachePolicyContext
+ _OBJC_IVAR_$_AARequest._urlConfig
+ _associated conformance 12AppleAccount31ProximityCustodianRecoveryErrorO10Foundation13CustomNSErrorAAs0F0
+ _associated conformance 12AppleAccount31ProximityCustodianRecoveryErrorO23SessionFailedCodingKeys33_655F54776971284348CFD24E395A41ABLLOSHAASQ
+ _associated conformance 12AppleAccount31ProximityCustodianRecoveryErrorO23SessionFailedCodingKeys33_655F54776971284348CFD24E395A41ABLLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 12AppleAccount31ProximityCustodianRecoveryErrorO23SessionFailedCodingKeys33_655F54776971284348CFD24E395A41ABLLOs0I3KeyAAs28CustomDebugStringConvertible
+ _symbolic _____ 12AppleAccount31ProximityCustodianRecoveryErrorO23SessionFailedCodingKeys33_655F54776971284348CFD24E395A41ABLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12AppleAccount31ProximityCustodianRecoveryErrorO23SessionFailedCodingKeys33_655F54776971284348CFD24E395A41ABLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12AppleAccount31ProximityCustodianRecoveryErrorO23SessionFailedCodingKeys33_655F54776971284348CFD24E395A41ABLLO
- -[AALoginAccountRequest urlString]
- -[AARegisterRequest urlString]
- -[AAURLConfiguration(Deprecated) fetchAccountSettingsURL]
- -[AAURLConfiguration(Deprecated) loginAccountURL]
- -[AAURLConfiguration(Deprecated) signInURL]
- -[AAUpdateProvisioningRequest urlString]
- GCC_except_table119
- _OBJC_IVAR_$_AALoginAccountRequest._urlConfig
- _OBJC_IVAR_$_AAUpdateProvisioningRequest._urlConfig
- _associated conformance 12AppleAccount31ProximityCustodianRecoveryErrorO17GenericCodingKeys33_655F54776971284348CFD24E395A41ABLLOSHAASQ
- _associated conformance 12AppleAccount31ProximityCustodianRecoveryErrorO17GenericCodingKeys33_655F54776971284348CFD24E395A41ABLLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 12AppleAccount31ProximityCustodianRecoveryErrorO17GenericCodingKeys33_655F54776971284348CFD24E395A41ABLLOs0H3KeyAAs28CustomDebugStringConvertible
- _associated conformance 12AppleAccount31ProximityCustodianRecoveryErrorO17UnknownCodingKeys33_655F54776971284348CFD24E395A41ABLLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 12AppleAccount31ProximityCustodianRecoveryErrorO17UnknownCodingKeys33_655F54776971284348CFD24E395A41ABLLOs0H3KeyAAs28CustomDebugStringConvertible
- _symbolic _____ 12AppleAccount31ProximityCustodianRecoveryErrorO17GenericCodingKeys33_655F54776971284348CFD24E395A41ABLLO
- _symbolic _____ 12AppleAccount31ProximityCustodianRecoveryErrorO17UnknownCodingKeys33_655F54776971284348CFD24E395A41ABLLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 12AppleAccount31ProximityCustodianRecoveryErrorO17GenericCodingKeys33_655F54776971284348CFD24E395A41ABLLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 12AppleAccount31ProximityCustodianRecoveryErrorO17UnknownCodingKeys33_655F54776971284348CFD24E395A41ABLLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 12AppleAccount31ProximityCustodianRecoveryErrorO17GenericCodingKeys33_655F54776971284348CFD24E395A41ABLLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 12AppleAccount31ProximityCustodianRecoveryErrorO17UnknownCodingKeys33_655F54776971284348CFD24E395A41ABLLO
CStrings:
+ "AASignInFlowController: Sign in - server backoff suppressed the login request"
+ "Avatar optimized for upload"
+ "Fetched identity from remote service"
+ "Received identity change notification for unregistered account: %{private,mask.hash}@"
+ "Starting observation with initial update if different from known identity"
+ "Starting observation with no initial update"
+ "generic"
+ "navigatedBack"
+ "userCancelled"
- "Received identity change notification for unregistered account: %@"
```
