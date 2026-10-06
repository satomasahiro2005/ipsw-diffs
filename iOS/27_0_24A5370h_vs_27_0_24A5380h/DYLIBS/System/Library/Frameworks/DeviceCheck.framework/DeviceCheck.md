## DeviceCheck

> `/System/Library/Frameworks/DeviceCheck.framework/DeviceCheck`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa6f0` | `0xa4a4` | **`-0x24c`** |
| `__AUTH.__objc_data` | `0x140` | `—` | **`-0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x1e0` | `0x320` | **`+0x140`** |
| `__DATA.__bss` | `0x10` | `—` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0xc0` | `0xd0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x158` | `0x160` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x470` | `0x468` | **`-0x8`** |

### Other Changes

```text
Functions:
~ -[DCAppAttestController isSupported] : 320 -> 308
~ ___66-[DCAppAttestController generateKeyWithTeamIdentifier:completion:]_block_invoke : 952 -> 940
~ ___83-[DCAppAttestController attestKey:teamIdentifier:clientDataHash:completionHandler:]_block_invoke : 1648 -> 1600
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke : 1264 -> 1228
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke_2 : 2164 -> 2128
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke_3 : 356 -> 344
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke.57 : 356 -> 344
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke.67 : 1984 -> 1960
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke_2.68 : 360 -> 348
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke.69 : 360 -> 348
~ ___91-[DCAppAttestController generateAssertion:teamIdentifier:clientDataHash:completionHandler:]_block_invoke : 1484 -> 1448
~ ___71-[DCAppAttestController sign:withKey:teamIdentifier:completionHandler:]_block_invoke : 884 -> 860
~ ___80-[DCAppAttestController getPropertiesForKeyId:teamIdentifier:completionHandler:]_block_invoke : 752 -> 728
~ ___80-[DCAppAttestController getPropertiesForKeyId:teamIdentifier:completionHandler:]_block_invoke.84 : 1096 -> 1048
~ ___46-[DCAppAttestController isSupportedWithError:]_block_invoke : 328 -> 316
~ -[DCAppAttestController loadAppUUID] : 456 -> 444
~ -[DCAppAttestController rewrapAsDCError:] : 400 -> 388
~ -[DCAppAttestController dispatchCompletionHandler:ontoQueue:] : 552 -> 540
~ -[DCAnalytics sendPayload:forEvent:withError:] : 504 -> 492
~ -[DCAnalytics sendPerformanceForCategory:eventType:] : 2640 -> 2604
~ -[DCAppAttestDeviceService isSupported] : 276 -> 264
~ -[DCAppAttestDeviceService attestKey:clientDataHash:options:completionHandler:] : 756 -> 732
~ -[DCAppAttestDeviceService hasEntitlement] : 736 -> 724
~ ___40+[DCXPCUtil sharedSerialProcessingQueue]_block_invoke : 504 -> 480
~ ___39-[DCDevice _isSupportedReturningError:]_block_invoke : 412 -> 400
~ -[DCDevice isSupported] : 320 -> 308
~ -[DCAppAttestWebAuthService isSupported] : 276 -> 264
~ -[DCAppAttestWebAuthService attestKey:clientDataHash:authData:completionHandler:] : 756 -> 732
~ -[DCAppAttestWebAuthService hasEntitlement] : 736 -> 724
```
