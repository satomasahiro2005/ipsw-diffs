## TouchRemote

> `/System/Library/PrivateFrameworks/TouchRemote.framework/TouchRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28a14` | `0x289e8` | **`-0x2c`** |

### Other Changes

```text
Functions:
~ ___52-[TROperationQueue addOperations:waitUntilFinished:]_block_invoke : 292 -> 288
~ __StringFromAccountServices : 324 -> 320
~ ___60-[TRDeviceSetupServer _authenticateWithAction:replyHandler:]_block_invoke : 588 -> 584
~ ___47-[TRNearbyDeviceAdvertiser _handleInvalidation]_block_invoke.33 : 324 -> 320
~ _TRGetNetworkConfigurationForIPv4 : 564 -> 560
~ -[TRDeviceSetupAuthenticateAction _initWithAccountType:accountID:accountPassword:accountTypesWithSharedCredentials:attemptCount:requestMessage:failureMessage:] : 932 -> 928
~ -[TRDeviceSetupAuthenticateAction accountTypesWithSharedCredentials] : 444 -> 440
~ -[TRSetupConfigurationResponse _stringFromAccountServices:] : 324 -> 320
~ -[TRAuthenticationOperation execute] : 4988 -> 4984
~ +[TRAccountManager _idmsAccountForAccountWithUsername:altDSID:DSID:] : 1220 -> 1212
```
