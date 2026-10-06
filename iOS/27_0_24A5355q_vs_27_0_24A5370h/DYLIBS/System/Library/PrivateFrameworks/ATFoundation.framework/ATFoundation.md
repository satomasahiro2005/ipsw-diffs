## ATFoundation

> `/System/Library/PrivateFrameworks/ATFoundation.framework/ATFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x2b22` | `0x2bc7` | **`+0xa5`** |
| `__TEXT.__text` | `0x20e90` | `0x20f24` | **`+0x94`** |
| `__AUTH_CONST.__objc_const` | `0x3840` | `0x3860` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1238` | `0x1240` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x274` | `0x278` | **`+0x4`** |
| `__TEXT.__cstring` | `0x1074` | `0x1075` | **`+0x1`** |

### Other Changes

```diff

-4026.100.55.0.0
+4026.100.68.0.0

-  Symbols:   1449
-  CStrings:  335
+  Symbols:   1450
+  CStrings:  337
Symbols:
+ _OBJC_IVAR_$_ATConcreteMessageLink._lastSentMessageDescription
Functions:
~ -[ATSessionProxyConnection start] : 372 -> 368
~ ___31-[ATStatusMonitor addObserver:]_block_invoke : 400 -> 396
~ ___46-[ATStatusMonitor setDataClasses:forObserver:]_block_invoke : 432 -> 428
~ ___32-[ATStatusMonitor updateStatus:]_block_invoke : 332 -> 328
~ ___32-[ATStatusMonitor updateAssets:]_block_invoke : 572 -> 568
~ ___48-[ATStatusMonitor updateStatusWithValue:forKey:]_block_invoke : 276 -> 272
~ ___52-[ATStatusMonitor updateStatusValuesWithDictionary:]_block_invoke : 272 -> 268
~ -[ATSessionServerListener fetchSessionsWithTypeIdentifier:completion:] : 468 -> 464
~ -[ATSessionServerListener cancelSessionWithIdentifier:completion:] : 476 -> 472
~ -[ATSessionServerListener fetchActiveSessionCountForSessionTypeIdentifier:completion:] : 564 -> 560
~ -[ATSessionServerListener _dumpDebugInformation] : 572 -> 568
~ -[ATSocket notifySocketDidClose] : 352 -> 348
~ -[ATSocket notifyHasDataAvailable:length:] : 372 -> 368
~ -[ATMovingAverage average] : 68 -> 76
~ -[ATAssetLinkController enqueueAssets:] : 648 -> 644
~ ___39-[ATAssetLinkController enqueueAssets:]_block_invoke : 1220 -> 1216
~ -[ATAssetLinkController enqueueAssets:progress:completion:] : 324 -> 320
~ ___69-[ATAssetLinkController enqueueAssetForStoreDownload:withCompletion:]_block_invoke : 996 -> 988
~ ___41-[ATAssetLinkController prioritizeAsset:]_block_invoke : 968 -> 964
~ ___85-[ATAssetLinkController prioritizeAssetWithStoreForLibraryIdentifier:withCompletion:]_block_invoke : 556 -> 552
~ ___102-[ATAssetLinkController cancelAllAssetsMatchingPredicate:excludeActiveDownloads:withError:completion:]_block_invoke_2 : 424 -> 420
~ ___59-[ATAssetLinkController filteredAssetsToDownloadForAssets:]_block_invoke : 284 -> 280
~ ___50-[ATAssetLinkController installCompleteForAssets:]_block_invoke : 676 -> 668
~ ___60-[ATAssetLinkController assetLink:didOpenWithPendingAssets:]_block_invoke : 260 -> 256
~ ___65-[ATAssetLinkController assetLink:didCloseWithOutstandingAssets:]_block_invoke : 856 -> 844
~ ___93-[ATAssetLinkController assetLink:didFinishAsset:error:retryable:cancelPendingAssetsInBatch:]_block_invoke : 1876 -> 1872
~ ___67-[ATAssetLinkController _performSelectorOnObservers:object:object:]_block_invoke : 280 -> 276
~ -[ATAssetLinkController _cancelAssets:withError:completion:] : 1548 -> 1540
~ -[ATAssetLinkController _canEnqueueAsset:] : 292 -> 288
~ -[ATAssetLinkController _handleEnqueue:onLink:withPriority:] : 808 -> 800
~ -[ATAssetLinkController _assetsDidChange] : 1144 -> 1140
~ -[ATAssetLinkController _prioritizeAsset:onLinkClass:] : 876 -> 872
~ -[ATAssetLinkController _updateCountsForFinishedTrackAssetTypes:] : 1020 -> 1012
~ -[ATDownloadProgressManager assetLinkController:didEnqueueAsset:] : 600 -> 592
~ -[ATDownloadProgressManager assetLinkController:didUpdateAsset:] : 624 -> 616
~ -[ATDownloadProgressManager assetLinkController:didProcessFinishedAsset:] : 692 -> 684
~ -[ATDownloadProgressManager assetLinkController:didChangeDownloadStateForAssets:] : 1056 -> 1044
~ -[ATDownloadProgressManager assetLinkController:willCancelActiveDownloadsOfMediaTypes:] : 576 -> 568
~ -[ATServiceProxyConnection fetchMessageLinksWithCompletion:] : 616 -> 612
~ ___29-[ATConcreteMessageLink open]_block_invoke : 860 -> 856
~ ___30-[ATConcreteMessageLink close]_block_invoke : 2152 -> 2132
~ ___30-[ATConcreteMessageLink close]_block_invoke.24 : 1172 -> 1160
~ -[ATConcreteMessageLink setInitialized:] : 396 -> 392
~ -[ATConcreteMessageLink _processIncomingDataResponse:] : 1020 -> 1224
~ -[ATConcreteMessageLink _checkMessageTimeouts] : 2416 -> 2536
~ -[ATConcreteMessageLink _sendMessage:error:] : 764 -> 828
~ -[ATConcreteMessageLink .cxx_destruct] : 524 -> 544
~ -[ATConcreteService run] : 544 -> 540
~ ___25-[ATConcreteService stop]_block_invoke : 272 -> 268
~ ___28-[ATConcreteAssetLink close]_block_invoke_2.12 : 520 -> 516
~ -[ATConcreteAssetLink enqueueAssets:force:] : 772 -> 768
~ ___36-[ATConcreteAssetLink cancelAssets:]_block_invoke : 508 -> 500
CStrings:
+ "%{public}@ Calling completion block for timed out message id %lld"
+ "%{public}@ Checking for message timeouts. last activity %{public}@ (%.2fs ago), idleTimeoutExceptionCount = %d"
+ "%{public}@ Failed to obtain valid stream writer for data message - ignoring"
+ "%{public}@ Timing out sent request %{public}@ (last activity %.2fs ago)"
+ "%{public}@ Timing out stream reader %{public}@ (last activity %.2fs ago)"
+ "%{public}@ idle timeout expired - sending ping. last sent message: %{public}@"
- "%{public}@ Calling completion block for timed out messgage if %lld"
- "%{public}@ Checking for message timeouts. _lastActivityTime=%f (%fs ago), idleTimeoutExceptionCount = %d"
- "%{public}@ Timing out sent request %{public}@ (last activity %fs ago"
- "%{public}@ Timing out stream reader %{public}@ (last activity %fs ago"
```
