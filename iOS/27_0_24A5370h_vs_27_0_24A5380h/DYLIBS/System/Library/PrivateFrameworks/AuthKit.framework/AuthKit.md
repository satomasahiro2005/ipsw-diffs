## AuthKit

> `/System/Library/PrivateFrameworks/AuthKit.framework/AuthKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19f4d0` | `0x1a1494` | **`+0x1fc4`** |
| `__TEXT.__oslogstring` | `0x158a1` | `0x15c80` | **`+0x3df`** |
| `__AUTH.__objc_data` | `0x34d0` | `0x3890` | **`+0x3c0`** |
| `__DATA_DIRTY.__objc_data` | `0x1950` | `0x1590` | **`-0x3c0`** |
| `__TEXT.__gcc_except_tab` | `0x65c4` | `0x6694` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x13f20` | `0x13fa0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x12f02` | `0x12f76` | **`+0x74`** |
| `__TEXT.__objc_methlist` | `0x1049c` | `0x104fc` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x4830` | `0x4870` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x78a8` | `0x78d8` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x2e488` | `0x2e4b0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x8178` | `0x81a0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xbc0` | `0xbc8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-552.0.0.0.0
+554.0.0.0.0

-  Functions: 6091
-  Symbols:   12279
-  CStrings:  4613
+  Functions: 6103
+  Symbols:   12289
+  CStrings:  4635
Symbols:
+ -[AKAccountRecoveryStepLocalAuthentication _isPushStyleResponse:]
+ -[AKAnisetteProvisioningController fetchSignedDeviceInfoHeadersWithCompletion:]
+ -[AKAppleIDPasskeyController configureRemoteInterface:]
+ -[AKAppleIDPasskeyController requestPasskeyChallengeWithContext:completion:]
+ -[AKAppleIDPasskeyController submitPasskeyCredentialWithContext:credential:completion:]
+ -[AKDevice hardwareModel]
+ ___76-[AKAppleIDPasskeyController requestPasskeyChallengeWithContext:completion:]_block_invoke
+ ___79-[AKAnisetteProvisioningController fetchSignedDeviceInfoHeadersWithCompletion:]_block_invoke
+ ___79-[AKAnisetteProvisioningController fetchSignedDeviceInfoHeadersWithCompletion:]_block_invoke_2
+ ___87-[AKAppleIDPasskeyController submitPasskeyCredentialWithContext:credential:completion:]_block_invoke
+ ___block_descriptor_56_e8_32bs_e62_v24?0"AKAppleIDPasskeyCredentialRequestContext"8"NSError"16ls32l8
- +[AKDevice _hardwareModel]
CStrings:
+ "AppleID passkey challenge request failed with error: %@"
+ "AppleID passkey credential submission failed with error: %@"
+ "AppleIDPasskey/requestPasskeyChallenge"
+ "AppleIDPasskey/submitPasskeyCredential"
+ "AppleIDPasskeyRequestChallenge"
+ "AppleIDPasskeySubmitCredential"
+ "BEGIN [%lld]: AppleIDPasskeyRequestChallenge  enableTelemetry=YES "
+ "BEGIN [%lld]: AppleIDPasskeySubmitCredential  enableTelemetry=YES "
+ "Completed AppleID passkey challenge request successfully"
+ "Completed AppleID passkey credential submission successfully"
+ "CustodianInstructionNTOMacOS"
+ "END [%lld] %fs:AppleIDPasskeyRequestChallenge  Error=%{public,signpost.telemetry:number2,name=Error}d "
+ "END [%lld] %fs:AppleIDPasskeySubmitCredential  Error=%{public,signpost.telemetry:number2,name=Error}d "
+ "FetchSignedDeviceInfo: Remote Anisette service returned an error: %@"
+ "FetchSignedDeviceInfo: Remote Anisette service successfully signed data."
+ "Local authentication: using push-style URL %@"
+ "MLBSerialNumber"
+ "URL matches Chromazone internal host, treating as third-party"
+ "authkit/signed-device-info"
+ "push"
+ "v24@?0@\"AKAppleIDPasskeyCredentialRequestContext\"8@\"NSError\"16"
+ "xa"
```
