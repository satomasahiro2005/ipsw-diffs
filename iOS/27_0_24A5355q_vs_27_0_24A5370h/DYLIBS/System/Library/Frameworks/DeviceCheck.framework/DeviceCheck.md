## DeviceCheck

> `/System/Library/Frameworks/DeviceCheck.framework/DeviceCheck`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa470` | `0xa6f0` | **`+0x280`** |
| `__TEXT.__gcc_except_tab` | `0x468` | `0x470` | **`+0x8`** |

### Other Changes

```diff

-151.0.0.0.0
+153.0.0.0.0
Functions:
~ -[DCAppAttestController isSupported] : 308 -> 320
~ ___66-[DCAppAttestController generateKeyWithTeamIdentifier:completion:]_block_invoke : 940 -> 952
~ ___83-[DCAppAttestController attestKey:teamIdentifier:clientDataHash:completionHandler:]_block_invoke : 1600 -> 1648
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke : 1228 -> 1264
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke_2 : 2100 -> 2164
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke_3 : 344 -> 356
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke.57 : 344 -> 356
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke.67 : 1936 -> 1984
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke_2.68 : 348 -> 360
~ ___99-[DCAppAttestController attestKey:keyAttributes:clientDataHash:authData:options:completionHandler:]_block_invoke.69 : 348 -> 360
~ ___91-[DCAppAttestController generateAssertion:teamIdentifier:clientDataHash:completionHandler:]_block_invoke : 1448 -> 1484
~ ___71-[DCAppAttestController sign:withKey:teamIdentifier:completionHandler:]_block_invoke : 860 -> 884
~ ___80-[DCAppAttestController getPropertiesForKeyId:teamIdentifier:completionHandler:]_block_invoke : 728 -> 752
~ ___80-[DCAppAttestController getPropertiesForKeyId:teamIdentifier:completionHandler:]_block_invoke.84 : 1048 -> 1096
~ ___46-[DCAppAttestController isSupportedWithError:]_block_invoke : 316 -> 328
~ -[DCAppAttestController loadAppUUID] : 444 -> 456
~ -[DCAppAttestController rewrapAsDCError:] : 388 -> 400
~ -[DCAppAttestController dispatchCompletionHandler:ontoQueue:] : 540 -> 552
~ -[DCAnalytics sendPayload:forEvent:withError:] : 492 -> 504
~ -[DCAnalytics sendPerformanceForCategory:eventType:] : 2604 -> 2640
~ -[DCAppAttestDeviceService isSupported] : 264 -> 276
~ -[DCAppAttestDeviceService attestKey:clientDataHash:options:completionHandler:] : 732 -> 756
~ -[DCAppAttestDeviceService hasEntitlement] : 724 -> 736
~ ___40+[DCXPCUtil sharedSerialProcessingQueue]_block_invoke : 480 -> 504
~ ___39-[DCDevice _isSupportedReturningError:]_block_invoke : 400 -> 412
~ -[DCDevice isSupported] : 308 -> 320
~ -[DCAppAttestWebAuthService isSupported] : 264 -> 276
~ -[DCAppAttestWebAuthService attestKey:clientDataHash:authData:completionHandler:] : 732 -> 756
~ -[DCAppAttestWebAuthService hasEntitlement] : 724 -> 736
```
