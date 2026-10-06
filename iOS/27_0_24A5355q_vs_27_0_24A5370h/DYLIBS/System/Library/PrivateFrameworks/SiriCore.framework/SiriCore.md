## SiriCore

> `/System/Library/PrivateFrameworks/SiriCore.framework/SiriCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32f60` | `0x32ed8` | **`-0x88`** |

### Other Changes

```text
Functions:
~ -[SiriCoreNetworkActivityTracing _networkActivityStart:activate:] : 560 -> 556
~ -[SiriCoreNetworkActivity stopWithCompletionReason:andError:] : 596 -> 592
~ -[_SAMetricsSendCompletionsProxy dispatchBlocksWithResult:error:] : 304 -> 300
~ ___55-[SiriCoreSiriBackgroundConnection _didEncounterError:]_block_invoke : 1304 -> 1300
~ -[SiriCoreSiriBackgroundConnection _checkForProgressOnReadingData] : 568 -> 560
~ -[SiriCoreSiriBackgroundConnection _cancelOutstandingBarriers] : 312 -> 308
~ -[SiriCoreSiriBackgroundConnection sendCommands:errorHandler:] : 420 -> 416
~ ___112+[SiriCoreNetworkingAnalytics(SessionConnectionSnapshot) sessionConnectionQualityFromSiriCoreConnectionMetrics:]_block_invoke : 232 -> 228
~ +[SiriCoreNetworkingAnalytics(NetworkConnectionState) endpointsFromArray:] : 364 -> 360
~ +[SiriCoreNetworkingAnalytics(NetworkConnectionState) pathInterfacesFromArray:] : 660 -> 656
~ +[SiriCoreNetworkingAnalytics(NetworkConnectionState) establishmentResolutionFromArray:] : 884 -> 880
~ +[SiriCoreNetworkingAnalytics(NetworkConnectionState) handShakeProtocolFromArray:] : 660 -> 656
~ _SiriCoreSQLiteQueryCreateColumnDefinition : 748 -> 744
~ _SiriCoreSQLiteQueryCreateEscapedAndCommaSeparatedString : 436 -> 432
~ _SiriCoreSQLiteQueryCreateCriterionExpression : 1872 -> 1864
~ -[SiriCoreSiriConnection start] : 2044 -> 2028
~ -[SiriCoreSiriConnection _cancelSynchronously:] : 444 -> 436
~ -[SiriCoreSiriConnection _accessPotentiallyActiveConnections:] : 312 -> 308
~ ___105-[SiriCoreSymptomsReporter reportIssueForType:subType:context:processIdentifier:walkboutStatus:withPcap:]_block_invoke : 312 -> 304
~ -[SiriCoreNetworkManager _pathUpdated:] : 652 -> 644
~ ___68-[SiriCoreNetworkManager _getLinkRecommendationSafe:recommendation:]_block_invoke : 728 -> 724
~ ___56-[SiriCoreNetworkManager _serviceSubscriptionInfoUpdate]_block_invoke_2 : 460 -> 456
~ -[SiriCoreNetworkManager simStatusDidChange:status:] : 316 -> 312
~ -[SiriCoreSQLiteDatabase(Schema) fetchTableWithName:error:] : 868 -> 864
~ -[SiriCoreSQLiteDatabase(Schema) createTable:error:] : 968 -> 960
```
