## watchlistd

> `/System/Library/PrivateFrameworks/WatchListKit.framework/Support/watchlistd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29194` | `0x290ec` | **`-0xa8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-950.0.0.0.0
+951.0.0.0.0
Functions:
~ -[WLDPlaybackManager _scanForPendingReports] : 2176 -> 2164
~ ___74-[WLDClientConnection performSportsFavoritesAction:ids:caller:completion:]_block_invoke : 416 -> 412
~ -[WLDPlayActivityReportOperation _protoForURLRequest:] : 1096 -> 1084
~ -[UWLMessageWireEnvelope dictionaryRepresentation] : 1284 -> 1268
~ -[UWLMessageWireEnvelope writeTo:] : 828 -> 812
~ -[UWLMessageWireEnvelope copyWithZone:] : 928 -> 912
~ -[UWLMessageWireEnvelope mergeFrom:] : 836 -> 820
~ +[WLDPlaybackReporter _donateIntentWithPlaybackSummary:andMetadata:] : 1156 -> 1152
~ -[WLDPlaybackManager fetchDecoratedNowPlayingSummaries:] : 1132 -> 1128
~ ___58-[WLDChannelManager vppaConsentedBundleIDsWithCompletion:]_block_invoke_2 : 428 -> 424
~ -[WLDAppVisibilityManager updateAppVisibility] : 664 -> 660
~ ___56-[WLDPushNotificationController _reportBulletinMetrics:]_block_invoke : 608 -> 604
~ ___55-[WLDPushNotificationController _reportMercuryMetrics:]_block_invoke : 568 -> 564
~ -[WLDPushNotificationController _postNotificationWithPayload:] : 4100 -> 4096
~ -[WLDPlaybackDirectPlayObserver _getAppRunningState] : 460 -> 456
~ -[WLDDeviceOfferManager processDeviceOffers] : 1180 -> 1176
~ -[UWLMessageHeaders dictionaryRepresentation] : 744 -> 740
~ -[UWLMessageHeaders writeTo:] : 540 -> 536
~ -[UWLMessageHeaders copyWithZone:] : 660 -> 656
~ -[UWLMessageHeaders mergeFrom:] : 532 -> 528
~ -[WLDPlaybackNowPlayingObserver nowPlayingSummaries] : 704 -> 700
~ -[WLDPlaybackNowPlayingObserver _activePlayerPathsDidChangeNotification:] : 484 -> 476
~ -[WLDPlaybackNowPlayingObserver _isAnyAppPlaying] : 520 -> 516
~ -[WLDPlaybackNowPlayingObserver _forceFetchNowPlayingInfofromActivePlayers] : 248 -> 244
~ -[WLDSportsLiveActivityPushHandler handleGameStartNotification:completion:] : 776 -> 772
```
