## DeviceCheckInternal

> `/System/Library/PrivateFrameworks/DeviceCheckInternal.framework/DeviceCheckInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15a18` | `0x15f70` | **`+0x558`** |
| `__TEXT.__cstring` | `0xd06` | `0xd12` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x428` | `0x420` | **`-0x8`** |

### Other Changes

```diff

-151.0.0.0.0
+153.0.0.0.0

-  Functions: 371
-  Symbols:   1170
+  Functions: 372
+  Symbols:   1171
Symbols:
+ _CTParseLeafSPKI
Functions:
~ -[DCUAFDeviceCheckAsset initWithFilePath:] : 356 -> 368
~ ___23+[DCTaskCreator create]_block_invoke : 1012 -> 1048
~ ___23+[DCTaskCreator create]_block_invoke.24 : 556 -> 580
~ -[DCUAFAssetManager subscribeWithCompletion:] : 824 -> 836
~ ___45-[DCUAFAssetManager subscribeWithCompletion:]_block_invoke : 504 -> 516
~ -[DCUAFAssetManager subscribed] : 868 -> 888
~ ___47-[DCUAFAssetManager unsubscribeWithCompletion:]_block_invoke : 708 -> 732
~ ___41-[DCUAFAssetManager fetchWithCompletion:]_block_invoke : 1440 -> 1488
~ -[DCBAASigner signatureForData:completion:] : 728 -> 752
~ ___43-[DCBAASigner signatureForData:completion:]_block_invoke : 1264 -> 1300
~ -[DCBAASigner signaturesForData:completion:] : 696 -> 720
~ ___44-[DCBAASigner signaturesForData:completion:]_block_invoke : 1904 -> 1952
~ ___44-[DCBAASigner signaturesForData:completion:]_block_invoke.6 : 836 -> 872
~ -[DCBAASigner _signatureForData:withReferenceKey:error:] : 772 -> 796
~ -[DCBAASigner _attestationWithCertificates:error:] : 1180 -> 1216
~ -[DCEncryptionKeyAsset fetchEncryptionKey] : 1140 -> 1188
~ +[DCCryptoUtilities identityCertificateOptions] : 748 -> 760
~ -[DCCryptoProxyImpl fetchOpaqueBlobWithContext:completion:] : 416 -> 428
~ -[DCCryptoProxyImpl baaSignatureForData:completion:] : 284 -> 296
~ -[DCCryptoProxyImpl baaSignaturesForData:completion:] : 284 -> 296
~ ___37-[DCCryptoProxyImpl _fetchPublicKey:]_block_invoke : 880 -> 916
~ ___36-[DCCryptoProxyImpl fetchAssetInfo:]_block_invoke : 512 -> 536
~ -[NSData(Signing) dc_compressedData:] : 728 -> 764
~ -[DCBGSTaskController registerForTask:] : 588 -> 600
~ ___39-[DCBGSTaskController registerForTask:]_block_invoke : 508 -> 520
~ ___39-[DCBGSTaskController registerForTask:]_block_invoke.9 : 308 -> 320
~ -[DCBGSTaskController fetchTaskForTaskIdentifier:] : 404 -> 400
~ -[DCBGSTaskController updateTaskWithIdentifier:withRefreshInterval:] : 1848 -> 1900
~ -[DCBGSTaskController observeValueForKeyPath:ofObject:change:context:] : 560 -> 572
~ -[DCBGSTaskController handleTask:shouldExit:] : 660 -> 676
~ -[DCCertificateGenerator generateCertificateChainWithCompletion:] : 508 -> 520
~ ___65-[DCCertificateGenerator generateCertificateChainWithCompletion:]_block_invoke : 740 -> 776
~ ___65-[DCCertificateGenerator generateCertificateChainWithCompletion:]_block_invoke.6 : 524 -> 548
~ -[DCCertificateGenerator createPEMCertificateChainFrom:completion:] : 2916 -> 2988
~ -[DCCertificateGenerator parseDERCertificatesFromChain:] : 732 -> 756
~ -[DCCertificateGenerator encryptData:serverSyncedDate:error:] : 2716 -> 2824
~ _hex : 124 -> 132
~ _find_digest : 128 -> 140
~ _validateSignatureRSA : 640 -> 636
~ _validateSignatureEC : 600 -> 596
~ _compressECPublicKey : 412 -> 408
~ _decompressECPublicKey : 428 -> 424
~ _CMSParseImplicitCertificateSet : 708 -> 756
+ _CTParseLeafSPKI
~ _CTVerifyHostname : 164 -> 180
~ _CTCompareGeneralNameToHostname : 572 -> 564
~ _CTEvaluateKeyTransparency : 464 -> 472
~ _CTGetICDPFederationType : 288 -> 316
~ _CTEvaluateICDPFederation : 216 -> 236
~ _X509ChainParseCertificateSet : 392 -> 408
~ _der_get_number : 96 -> 100
~ _encode_list_add_number : 464 -> 460
CStrings:
+ "devicecheck_configurations.plist"
- "configurations.plist"
```
