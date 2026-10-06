## com.apple.iokit.CoreAnalyticsFamily

> `com.apple.iokit.CoreAnalyticsFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x8548` | `0x885c` | **`+0x314`** |

### Other Changes

```text
Functions:
~ sub_fffffff009adfc80 -> sub_fffffff009b6bc10 : 68 -> 72
~ sub_fffffff009adfcd4 -> sub_fffffff009b6bc68 : 104 -> 108
~ __ZN28CoreAnalyticsEventRatePolicy12withWorkloopEP10IOWorkLoop : 168 -> 172
~ __ZN28CoreAnalyticsEventRatePolicy16initWithWorkloopEP10IOWorkLoop : 576 -> 580
~ __ZN28CoreAnalyticsEventRatePolicy24handleNewMeasurementSpanEP18IOTimerEventSource : 60 -> 64
~ sub_fffffff009ae0060 -> sub_fffffff009b6c004 : 208 -> 212
~ __ZN28CoreAnalyticsEventRatePolicy21zeroOutPerEventCountsEv : 508 -> 512
~ __ZN28CoreAnalyticsEventRatePolicy22incrementCountForEventEP8OSString : 444 -> 448
~ __ZN28CoreAnalyticsEventRatePolicy24sendBudgetExceededReportEv : 500 -> 504
~ __ZN28CoreAnalyticsEventRatePolicy14isRateExceededEP8OSString : 116 -> 120
~ __ZNK28CoreAnalyticsEventRatePolicy17createBudgetDictsEP7OSArray : 1132 -> 1136
~ __GLOBAL__sub_I_CoreAnalyticsEventRatePolicy.cpp : 80 -> 84
~ __ZN16CoreAnalyticsHub9MetaClassC1Ev : 72 -> 76
~ sub_fffffff009ae0cd0 -> sub_fffffff009b6cc94 : 52 -> 56
~ sub_fffffff009ae0d04 -> sub_fffffff009b6cccc : 52 -> 56
~ sub_fffffff009ae0d48 -> sub_fffffff009b6cd14 : 68 -> 72
~ sub_fffffff009ae0db4 -> sub_fffffff009b6cd84 : 72 -> 76
~ sub_fffffff009ae0dfc -> sub_fffffff009b6cdd0 : 104 -> 108
~ sub_fffffff009ae0e78 -> sub_fffffff009b6ce50 : 88 -> 92
~ sub_fffffff009ae0ed0 -> sub_fffffff009b6ceac : 88 -> 92
~ __ZN16CoreAnalyticsHub5startEP9IOService : 1432 -> 1436
~ __ZN16CoreAnalyticsHub21sendUpEventAndPayloadEP8OSStringP8OSObject : 1028 -> 1032
~ sub_fffffff009ae18c4 -> sub_fffffff009b6d8ac : 96 -> 100
~ __ZN16CoreAnalyticsHub20handleNagTimerExpiryEP18IOTimerEventSource : 220 -> 224
~ __ZN16CoreAnalyticsHub21handleDemoTimerExpiryEP18IOTimerEventSource : 200 -> 204
~ __ZN16CoreAnalyticsHub32handleUserClientRetryTimerExpiryEP18IOTimerEventSource : 112 -> 116
~ __ZN16CoreAnalyticsHub15createReportersEv : 1392 -> 1396
~ __ZN16CoreAnalyticsHub13publishLegendEv : 288 -> 292
~ _IOCoreAnalyticsSendEvent : 144 -> 148
~ __ZN16CoreAnalyticsHub4stopEP9IOService : 164 -> 168
~ __ZN16CoreAnalyticsHub4freeEv : 380 -> 384
~ sub_fffffff009ae2508 -> sub_fffffff009b6e514 : 176 -> 180
~ __ZN16CoreAnalyticsHub20__newUserClientGatedEP4taskPvjP12OSDictionaryPP12IOUserClient : 272 -> 276
~ sub_fffffff009ae26e8 -> sub_fffffff009b6e6fc : 84 -> 88
~ __ZN16CoreAnalyticsHub18setupNewUserClientEP4taskPvjP12OSDictionaryP12IOUserClient : 252 -> 256
~ __ZN16CoreAnalyticsHub14setClientGatedEP23CoreAnalyticsUserClient : 312 -> 316
~ __ZN16CoreAnalyticsHub5closeEP9IOServicej : 76 -> 80
~ __ZN16CoreAnalyticsHub27incrementEventNameRateLimitEP8OSString : 316 -> 320
~ __ZN16CoreAnalyticsHub24incrementEventNameFailedEP8OSString : 316 -> 320
~ __ZN16CoreAnalyticsHub16serializePayloadEP8OSObjectP11OSSerializePm : 208 -> 212
~ __ZN16CoreAnalyticsHub26incrementEventNameReceivedEP8OSString : 316 -> 320
~ __ZN16CoreAnalyticsHub37incrementEventNameSharedDataQueueFullEP8OSString : 316 -> 320
~ __ZN16CoreAnalyticsHub35incrementEventNameSerializeTooLargeEP8OSString : 316 -> 320
~ __ZN16CoreAnalyticsHub34incrementEventNameSerializeFailureEP8OSString : 316 -> 320
~ __ZN16CoreAnalyticsHub20getIndexForEventNameEP8OSString : 344 -> 348
~ sub_fffffff009ae33ac -> sub_fffffff009b6f3f0 : 144 -> 148
~ __ZN16CoreAnalyticsHub21testDemoNormalMessageEv : 636 -> 640
~ __ZN16CoreAnalyticsHub24testDemoOversizedMessageEv : 556 -> 560
~ _analytics_send_event_lazy : 112 -> 116
~ sub_fffffff009ae395c -> sub_fffffff009b6f9b0 : 80 -> 84
~ sub_fffffff009ae3a8c -> sub_fffffff009b6fae4 : 68 -> 72
~ sub_fffffff009ae3ae0 -> sub_fffffff009b6fb3c : 104 -> 108
~ sub_fffffff009ae3b48 -> sub_fffffff009b6fba8 : 220 -> 224
~ sub_fffffff009ae3c24 -> sub_fffffff009b6fc88 : 120 -> 124
~ __ZN22CoreAnalyticsMessenger13startMessagesEv : 212 -> 216
~ __ZN22CoreAnalyticsMessenger6attachEP9IOService : 208 -> 212
~ __ZN22CoreAnalyticsMessenger6detachEP9IOService : 140 -> 144
~ sub_fffffff009ae3ecc -> sub_fffffff009b6ff40 : 144 -> 148
~ sub_fffffff009ae3f64 -> sub_fffffff009b6ffdc : 80 -> 84
~ sub_fffffff009ae3fd4 -> sub_fffffff009b70050 : 68 -> 72
~ sub_fffffff009ae4028 -> sub_fffffff009b700a8 : 104 -> 108
~ __ZN17CoreAnalyticsPipe10withParamsENS_6ParamsE : 236 -> 240
~ __ZN17CoreAnalyticsPipe14initWithParamsENS_6ParamsE : 376 -> 380
~ sub_fffffff009ae42f4 -> sub_fffffff009b70380 : 400 -> 404
~ __ZN17CoreAnalyticsPipe22enqueueEventAndPayloadEP8OSStringP8OSObject : 300 -> 304
~ __os_log_internal : 648 -> 652
~ __GLOBAL__sub_I_CoreAnalyticsPipe.cpp : 80 -> 84
~ sub_fffffff009ae4904 -> sub_fffffff009b709a0 : 68 -> 72
~ sub_fffffff009ae4958 -> sub_fffffff009b709f8 : 104 -> 108
~ __ZN27CoreAnalyticsTestUserClient4freeEv : 124 -> 128
~ __ZN27CoreAnalyticsTestUserClient5startEP9IOService : 340 -> 344
~ __ZN27CoreAnalyticsTestUserClient4stopEP9IOService : 232 -> 236
~ __ZN27CoreAnalyticsTestUserClient12initWithTaskEP4taskPvjP12OSDictionary : 156 -> 160
~ __ZN27CoreAnalyticsTestUserClient11clientCloseEv : 156 -> 160
~ __ZN27CoreAnalyticsTestUserClient10clientDiedEv : 160 -> 164
~ __ZN27CoreAnalyticsTestUserClient12didTerminateEP9IOServicejPb : 156 -> 160
~ __ZN27CoreAnalyticsTestUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 508 -> 512
~ __GLOBAL__sub_I_CoreAnalyticsTestUserClient.cpp : 80 -> 84
~ sub_fffffff009ae5160 -> sub_fffffff009b71228 : 68 -> 72
~ sub_fffffff009ae51b4 -> sub_fffffff009b71280 : 104 -> 108
~ sub_fffffff009ae5230 -> sub_fffffff009b71300 : 88 -> 92
~ __ZN23CoreAnalyticsUserClient20goto_configureFilterEPS_PvP25IOExternalMethodArguments : 112 -> 116
~ __ZN23CoreAnalyticsUserClient4freeEv : 152 -> 156
~ __ZN23CoreAnalyticsUserClient5startEP9IOService : 344 -> 348
~ __ZN23CoreAnalyticsUserClient4stopEP9IOService : 332 -> 336
~ __ZN23CoreAnalyticsUserClient12initWithTaskEP4taskPvjP12OSDictionary : 244 -> 248
~ __ZN23CoreAnalyticsUserClient16checkEntitlementEP4task : 324 -> 328
~ __ZN23CoreAnalyticsUserClient11clientCloseEv : 200 -> 204
~ __ZN23CoreAnalyticsUserClient10clientDiedEv : 132 -> 136
~ __ZN23CoreAnalyticsUserClient12didTerminateEP9IOServicejPb : 156 -> 160
~ __ZN23CoreAnalyticsUserClient24registerNotificationPortEP8ipc_portjy : 192 -> 196
~ __ZN23CoreAnalyticsUserClient19clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 392 -> 396
~ __ZN23CoreAnalyticsUserClient14sendDataToUserEPhm : 320 -> 324
~ __GLOBAL__sub_I_CoreAnalyticsUserClient.cpp : 80 -> 84
~ __ZN28CoreAnalyticsEventRatePolicy16initWithWorkloopEP10IOWorkLoop.cold.1 : 84 -> 88
~ __ZN28CoreAnalyticsEventRatePolicy16initWithWorkloopEP10IOWorkLoop.cold.2 : 84 -> 88
~ __ZN28CoreAnalyticsEventRatePolicy16initWithWorkloopEP10IOWorkLoop.cold.3 : 84 -> 88
~ __ZN28CoreAnalyticsEventRatePolicy16initWithWorkloopEP10IOWorkLoop.cold.4 : 84 -> 88
~ __ZN28CoreAnalyticsEventRatePolicy16initWithWorkloopEP10IOWorkLoop.cold.5 : 176 -> 180
~ __ZN28CoreAnalyticsEventRatePolicy22incrementCountForEventEP8OSString.cold.2 : 136 -> 140
~ __ZN28CoreAnalyticsEventRatePolicy22incrementCountForEventEP8OSString.cold.1 : 224 -> 228
~ sub_fffffff009ae62bc -> sub_fffffff009b723e0 : 152 -> 156
~ __ZN28CoreAnalyticsEventRatePolicy24sendBudgetExceededReportEv.cold.1 : 64 -> 68
~ __ZN28CoreAnalyticsEventRatePolicy24sendBudgetExceededReportEv.cold.2 : 88 -> 92
~ __ZN28CoreAnalyticsEventRatePolicy24sendBudgetExceededReportEv.cold.3 : 88 -> 92
~ __ZNK28CoreAnalyticsEventRatePolicy17createBudgetDictsEP7OSArray.cold.1 : 52 -> 56
~ __ZNK28CoreAnalyticsEventRatePolicy17createBudgetDictsEP7OSArray.cold.2 : 52 -> 56
~ __ZNK28CoreAnalyticsEventRatePolicy17createBudgetDictsEP7OSArray.cold.3 : 52 -> 56
~ __ZNK28CoreAnalyticsEventRatePolicy17createBudgetDictsEP7OSArray.cold.4 : 88 -> 92
~ __ZNK28CoreAnalyticsEventRatePolicy17createBudgetDictsEP7OSArray.cold.5 : 52 -> 56
~ __ZNK28CoreAnalyticsEventRatePolicy17createBudgetDictsEP7OSArray.cold.6 : 52 -> 56
~ __ZNK28CoreAnalyticsEventRatePolicy17createBudgetDictsEP7OSArray.cold.7 : 52 -> 56
~ __ZNK28CoreAnalyticsEventRatePolicy17createBudgetDictsEP7OSArray.cold.8 : 52 -> 56
~ sub_fffffff009ae6608 -> sub_fffffff009b7275c : 152 -> 156
~ __ZNK28CoreAnalyticsEventRatePolicy17createBudgetDictsEP7OSArray.cold.10 : 88 -> 92
~ __ZN16CoreAnalyticsHub22analyticsSendEventLazyEP8OSStringP8OSObject : 196 -> 200
~ sub_fffffff009ae67bc -> sub_fffffff009b7291c : 124 -> 128
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.1 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.2 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.3 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.4 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.5 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.6 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.7 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.8 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.9 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.10 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.11 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.12 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.13 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.14 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.15 : 80 -> 84
~ __ZN16CoreAnalyticsHub5startEP9IOService.cold.16 : 80 -> 84
~ __ZN16CoreAnalyticsHub21sendUpEventAndPayloadEP8OSStringP8OSObject.cold.1 : 60 -> 64
~ __ZN16CoreAnalyticsHub21sendUpEventAndPayloadEP8OSStringP8OSObject.cold.2 : 88 -> 92
~ __ZN16CoreAnalyticsHub21sendUpEventAndPayloadEP8OSStringP8OSObject.cold.3 : 100 -> 104
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.1 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.2 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.3 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.4 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.5 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.6 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.7 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.8 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.9 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.10 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.11 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.12 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.13 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.14 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.15 : 52 -> 56
~ __ZN16CoreAnalyticsHub15createReportersEv.cold.16 : 52 -> 56
~ _IOCoreAnalyticsSendEvent.cold.1 : 96 -> 100
~ _IOCoreAnalyticsSendEvent.cold.2 : 84 -> 88
~ _IOCoreAnalyticsSendEvent.cold.3 : 84 -> 88
~ __ZN16CoreAnalyticsHub20__newUserClientGatedEP4taskPvjP12OSDictionaryPP12IOUserClient.cold.1 : 96 -> 100
~ __ZN16CoreAnalyticsHub18setupNewUserClientEP4taskPvjP12OSDictionaryP12IOUserClient.cold.1 : 60 -> 64
~ __ZN16CoreAnalyticsHub18setupNewUserClientEP4taskPvjP12OSDictionaryP12IOUserClient.cold.2 : 60 -> 64
~ __ZN16CoreAnalyticsHub18setupNewUserClientEP4taskPvjP12OSDictionaryP12IOUserClient.cold.3 : 60 -> 64
~ __ZN16CoreAnalyticsHub18setupNewUserClientEP4taskPvjP12OSDictionaryP12IOUserClient.cold.4 : 60 -> 64
~ __ZN16CoreAnalyticsHub16serializePayloadEP8OSObjectP11OSSerializePm.cold.1 : 60 -> 64
~ __ZN16CoreAnalyticsHub16serializePayloadEP8OSObjectP11OSSerializePm.cold.2 : 60 -> 64
~ __ZN16CoreAnalyticsHub20getIndexForEventNameEP8OSString.cold.1 : 96 -> 100
~ __ZN16CoreAnalyticsHub20getIndexForEventNameEP8OSString.cold.2 : 60 -> 64
~ sub_fffffff009ae74dc -> sub_fffffff009b736fc : 84 -> 88
~ sub_fffffff009ae7530 -> sub_fffffff009b73754 : 92 -> 96
~ __ZN16CoreAnalyticsHub24testDemoOversizedMessageEv.cold.2 : 84 -> 88
~ __ZN16CoreAnalyticsHub24testDemoOversizedMessageEv.cold.3 : 92 -> 96
~ sub_fffffff009ae763c -> sub_fffffff009b7386c : 92 -> 96
~ __ZN16CoreAnalyticsHub24testDemoOversizedMessageEv.cold.1 : 84 -> 88
~ sub_fffffff009ae76ec -> sub_fffffff009b73924 : 84 -> 88
~ sub_fffffff009ae7740 -> sub_fffffff009b7397c : 100 -> 104
~ sub_fffffff009ae77a4 -> sub_fffffff009b739e4 : 100 -> 104
~ _analytics_send_event_lazy.cold.1 : 128 -> 132
~ __ZN22CoreAnalyticsMessenger6attachEP9IOService.cold.1 : 76 -> 80
~ __ZN17CoreAnalyticsPipe14initWithParamsENS_6ParamsE.cold.1 : 88 -> 92
~ __ZN17CoreAnalyticsPipe14initWithParamsENS_6ParamsE.cold.2 : 148 -> 152
~ __ZN17CoreAnalyticsPipe14initWithParamsENS_6ParamsE.cold.3 : 148 -> 152
~ __ZN17CoreAnalyticsPipe14initWithParamsENS_6ParamsE.cold.4 : 148 -> 152
~ __ZN17CoreAnalyticsPipe14initWithParamsENS_6ParamsE.cold.5 : 148 -> 152
~ __ZN17CoreAnalyticsPipe14initWithParamsENS_6ParamsE.cold.6 : 148 -> 152
~ __ZN17CoreAnalyticsPipe14initWithParamsENS_6ParamsE.cold.7 : 148 -> 152
~ __ZN17CoreAnalyticsPipe14initWithParamsENS_6ParamsE.cold.8 : 148 -> 152
~ __ZN17CoreAnalyticsPipe22enqueueEventAndPayloadEP8OSStringP8OSObject.cold.1 : 164 -> 168
~ __ZN17CoreAnalyticsPipe22enqueueEventAndPayloadEP8OSStringP8OSObject.cold.2 : 128 -> 132
~ __ZN27CoreAnalyticsTestUserClient5startEP9IOService.cold.1 : 84 -> 88
~ __ZN27CoreAnalyticsTestUserClient5startEP9IOService.cold.2 : 84 -> 88
~ __ZN27CoreAnalyticsTestUserClient12initWithTaskEP4taskPvjP12OSDictionary.cold.1 : 84 -> 88
~ __ZN27CoreAnalyticsTestUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv.cold.1 : 84 -> 88
~ __ZN27CoreAnalyticsTestUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv.cold.2 : 84 -> 88
~ __ZN23CoreAnalyticsUserClient5startEP9IOService.cold.1 : 60 -> 64
~ __ZN23CoreAnalyticsUserClient5startEP9IOService.cold.2 : 60 -> 64
~ __ZN23CoreAnalyticsUserClient5startEP9IOService.cold.3 : 60 -> 64
~ __ZN23CoreAnalyticsUserClient12initWithTaskEP4taskPvjP12OSDictionary.cold.1 : 60 -> 64
~ __ZN23CoreAnalyticsUserClient12initWithTaskEP4taskPvjP12OSDictionary.cold.2 : 60 -> 64
~ __ZN23CoreAnalyticsUserClient12initWithTaskEP4taskPvjP12OSDictionary.cold.3 : 60 -> 64
~ __ZN23CoreAnalyticsUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv.cold.1 : 80 -> 84
```
