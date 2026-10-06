## Matter

> `/System/Library/Frameworks/Matter.framework/Matter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80e9c8` | `0x835010` | **`+0x26648`** |
| `__TEXT.__gcc_except_tab` | `0xbb6d4` | `0xc030c` | **`+0x4c38`** |
| `__AUTH_CONST.__objc_const` | `0x6f880` | `0x73328` | **`+0x3aa8`** |
| `__TEXT.__objc_methlist` | `0x59994` | `0x5c054` | **`+0x26c0`** |
| `__TEXT.__unwind_info` | `0x4e9f8` | `0x50200` | **`+0x1808`** |
| `__AUTH.__objc_data` | `0x1cc00` | `0x1db50` | **`+0xf50`** |
| `__TEXT.__cstring` | `0x2ec96` | `0x2fa0c` | **`+0xd76`** |
| `__AUTH_CONST.__cfstring` | `0x16fa0` | `0x17ae0` | **`+0xb40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b7d0` | `0x1c008` | **`+0x838`** |
| `__DATA.__objc_ivar` | `0x3c48` | `0x3e64` | **`+0x21c`** |
| `__AUTH_CONST.__objc_intobj` | `0x67c8` | `0x6990` | **`+0x1c8`** |
| `__DATA_CONST.__const` | `0x128c8` | `0x12a88` | **`+0x1c0`** |
| `__DATA_CONST.__objc_classlist` | `0x2e00` | `0x2f88` | **`+0x188`** |
| `__DATA_CONST.__got` | `0x2188` | `0x22c8` | **`+0x140`** |
| `__DATA_CONST.__objc_superrefs` | `0x2038` | `0x2160` | **`+0x128`** |
| `__TEXT.__oslogstring` | `0x1b0de` | `0x1b1c6` | **`+0xe8`** |
| `__TEXT.__const` | `0x63179` | `0x63239` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x1c3e8` | `0x1c420` | **`+0x38`** |

### Other Changes

```diff

-315.0.0.0.0
+320.1.0.0.0

-  Functions: 50883
-  Symbols:   3292
-  CStrings:  8749
+  Functions: 51797
+  Symbols:   3387
+  CStrings:  8855
Symbols:
+ _OBJC_CLASS_$_MTRAVAnalysisClusterActivateAnalysisStreamParams
+ _OBJC_CLASS_$_MTRAVAnalysisClusterAnalysisSessionEndEvent
+ _OBJC_CLASS_$_MTRAVAnalysisClusterAnalysisSessionStartEvent
+ _OBJC_CLASS_$_MTRAVAnalysisClusterAnalysisStreamStruct
+ _OBJC_CLASS_$_MTRAVAnalysisClusterContextTriggerStruct
+ _OBJC_CLASS_$_MTRAVAnalysisClusterDeactivateAnalysisStreamParams
+ _OBJC_CLASS_$_MTRAVAnalysisClusterDisableContextTriggersParams
+ _OBJC_CLASS_$_MTRAVAnalysisClusterEnableContextTriggersParams
+ _OBJC_CLASS_$_MTRAVAnalysisClusterEstablishAnalysisStreamParams
+ _OBJC_CLASS_$_MTRAVAnalysisClusterEstablishAnalysisStreamResponseParams
+ _OBJC_CLASS_$_MTRAVAnalysisClusterPerceivedContextEvent
+ _OBJC_CLASS_$_MTRAVAnalysisClusterRemoveAnalysisStreamParams
+ _OBJC_CLASS_$_MTRAVAnalysisClusterTrackedContext
+ _OBJC_CLASS_$_MTRAmbientSensingUnionClusterUnionContributorAddedEvent
+ _OBJC_CLASS_$_MTRAmbientSensingUnionClusterUnionContributorRemovedEvent
+ _OBJC_CLASS_$_MTRAmbientSensingUnionClusterUnionContributorStatusChangedEvent
+ _OBJC_CLASS_$_MTRAmbientSensingUnionClusterUnionContributorStruct
+ _OBJC_CLASS_$_MTRBaseClusterAVAnalysis
+ _OBJC_CLASS_$_MTRBaseClusterAmbientSensingUnion
+ _OBJC_CLASS_$_MTRBaseClusterCommissioningProxy
+ _OBJC_CLASS_$_MTRBaseClusterElectricalAlarm
+ _OBJC_CLASS_$_MTRBaseClusterTemperatureControlledCabinetTopology
+ _OBJC_CLASS_$_MTRBaseClusterTestHiddenManufacturerSpecific
+ _OBJC_CLASS_$_MTRClusterAVAnalysis
+ _OBJC_CLASS_$_MTRClusterAmbientSensingUnion
+ _OBJC_CLASS_$_MTRClusterCommissioningProxy
+ _OBJC_CLASS_$_MTRClusterElectricalAlarm
+ _OBJC_CLASS_$_MTRClusterTemperatureControlledCabinetTopology
+ _OBJC_CLASS_$_MTRClusterTestHiddenManufacturerSpecific
+ _OBJC_CLASS_$_MTRCommissioningProxyClusterProxyBackGroundScanStartRequestParams
+ _OBJC_CLASS_$_MTRCommissioningProxyClusterProxyBackGroundScanStopRequestParams
+ _OBJC_CLASS_$_MTRCommissioningProxyClusterProxyConnectRequestParams
+ _OBJC_CLASS_$_MTRCommissioningProxyClusterProxyConnectResponseParams
+ _OBJC_CLASS_$_MTRCommissioningProxyClusterProxyDisconnectRequestParams
+ _OBJC_CLASS_$_MTRCommissioningProxyClusterProxyMessageRequestParams
+ _OBJC_CLASS_$_MTRCommissioningProxyClusterProxyMessageResponseParams
+ _OBJC_CLASS_$_MTRCommissioningProxyClusterProxyScanRequestParams
+ _OBJC_CLASS_$_MTRCommissioningProxyClusterProxyScanResponseParams
+ _OBJC_CLASS_$_MTRCommissioningProxyClusterScanResultStruct
+ _OBJC_CLASS_$_MTRDeviceEnergyManagementClusterCancelPowerRangeAdjustRequestParams
+ _OBJC_CLASS_$_MTRDeviceEnergyManagementClusterPowerRangeAdjustEndEvent
+ _OBJC_CLASS_$_MTRDeviceEnergyManagementClusterPowerRangeAdjustRequestParams
+ _OBJC_CLASS_$_MTRDeviceEnergyManagementClusterPowerRangeAdjustStartEvent
+ _OBJC_CLASS_$_MTRDeviceEnergyManagementClusterPowerRangeAdjustStruct
+ _OBJC_CLASS_$_MTRElectricalAlarmClusterModifyEnabledAlarmsParams
+ _OBJC_CLASS_$_MTRElectricalAlarmClusterNotifyEvent
+ _OBJC_CLASS_$_MTRElectricalAlarmClusterResetParams
+ _OBJC_CLASS_$_MTRElectricalAlarmClusterSetElectricalAlarmThresholdsParams
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterActivateAnalysisStreamParams
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterAnalysisSessionEndEvent
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterAnalysisSessionStartEvent
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterAnalysisStreamStruct
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterContextTriggerStruct
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterDeactivateAnalysisStreamParams
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterDisableContextTriggersParams
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterEnableContextTriggersParams
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterEstablishAnalysisStreamParams
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterEstablishAnalysisStreamResponseParams
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterPerceivedContextEvent
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterRemoveAnalysisStreamParams
+ _OBJC_METACLASS_$_MTRAVAnalysisClusterTrackedContext
+ _OBJC_METACLASS_$_MTRAmbientSensingUnionClusterUnionContributorAddedEvent
+ _OBJC_METACLASS_$_MTRAmbientSensingUnionClusterUnionContributorRemovedEvent
+ _OBJC_METACLASS_$_MTRAmbientSensingUnionClusterUnionContributorStatusChangedEvent
+ _OBJC_METACLASS_$_MTRAmbientSensingUnionClusterUnionContributorStruct
+ _OBJC_METACLASS_$_MTRBaseClusterAVAnalysis
+ _OBJC_METACLASS_$_MTRBaseClusterAmbientSensingUnion
+ _OBJC_METACLASS_$_MTRBaseClusterCommissioningProxy
+ _OBJC_METACLASS_$_MTRBaseClusterElectricalAlarm
+ _OBJC_METACLASS_$_MTRBaseClusterTemperatureControlledCabinetTopology
+ _OBJC_METACLASS_$_MTRBaseClusterTestHiddenManufacturerSpecific
+ _OBJC_METACLASS_$_MTRClusterAVAnalysis
+ _OBJC_METACLASS_$_MTRClusterAmbientSensingUnion
+ _OBJC_METACLASS_$_MTRClusterCommissioningProxy
+ _OBJC_METACLASS_$_MTRClusterElectricalAlarm
+ _OBJC_METACLASS_$_MTRClusterTemperatureControlledCabinetTopology
+ _OBJC_METACLASS_$_MTRClusterTestHiddenManufacturerSpecific
+ _OBJC_METACLASS_$_MTRCommissioningProxyClusterProxyBackGroundScanStartRequestParams
+ _OBJC_METACLASS_$_MTRCommissioningProxyClusterProxyBackGroundScanStopRequestParams
+ _OBJC_METACLASS_$_MTRCommissioningProxyClusterProxyConnectRequestParams
+ _OBJC_METACLASS_$_MTRCommissioningProxyClusterProxyConnectResponseParams
+ _OBJC_METACLASS_$_MTRCommissioningProxyClusterProxyDisconnectRequestParams
+ _OBJC_METACLASS_$_MTRCommissioningProxyClusterProxyMessageRequestParams
+ _OBJC_METACLASS_$_MTRCommissioningProxyClusterProxyMessageResponseParams
+ _OBJC_METACLASS_$_MTRCommissioningProxyClusterProxyScanRequestParams
+ _OBJC_METACLASS_$_MTRCommissioningProxyClusterProxyScanResponseParams
+ _OBJC_METACLASS_$_MTRCommissioningProxyClusterScanResultStruct
+ _OBJC_METACLASS_$_MTRDeviceEnergyManagementClusterCancelPowerRangeAdjustRequestParams
+ _OBJC_METACLASS_$_MTRDeviceEnergyManagementClusterPowerRangeAdjustEndEvent
+ _OBJC_METACLASS_$_MTRDeviceEnergyManagementClusterPowerRangeAdjustRequestParams
+ _OBJC_METACLASS_$_MTRDeviceEnergyManagementClusterPowerRangeAdjustStartEvent
+ _OBJC_METACLASS_$_MTRDeviceEnergyManagementClusterPowerRangeAdjustStruct
+ _OBJC_METACLASS_$_MTRElectricalAlarmClusterModifyEnabledAlarmsParams
+ _OBJC_METACLASS_$_MTRElectricalAlarmClusterNotifyEvent
+ _OBJC_METACLASS_$_MTRElectricalAlarmClusterResetParams
+ _OBJC_METACLASS_$_MTRElectricalAlarmClusterSetElectricalAlarmThresholdsParams
- _MTRUnpoweredPhaseOverNFCKey
CStrings:
+ "<%@: addedContributor:%@; >"
+ "<%@: address:%@; transport:%@; discriminator:%@; vendorID:%@; productID:%@; extendedData:%@; wiFiBand:%@; >"
+ "<%@: address:%@; transport:%@; discriminator:%@; vendorID:%@; productID:%@; timeout:%@; wiFiBand:%@; >"
+ "<%@: adjustment:%@; duration:%@; >"
+ "<%@: ambientContextDetected:%@; objectCountThresholdReached:%@; objectCount:%@; >"
+ "<%@: ambientContextSensed:%@; detectionConfidence:%@; >"
+ "<%@: analysisStreamID:%@; >"
+ "<%@: analysisStreamID:%@; webRTCEndpointID:%@; pushAVEndpointID:%@; >"
+ "<%@: analysisStreamID:%@; webRTCEndpointID:%@; pushAVEndpointID:%@; analysisStreamState:%@; >"
+ "<%@: clientIndex:%@; clientIdentifier:%@; clientIdentityType:%@; networkIdentityIndex:%@; >"
+ "<%@: cmafInterface:%@; segmentDuration:%@; chunkDuration:%@; sessionGroup:%@; trackName:%@; metadataEnabled:%@; >"
+ "<%@: context:%@; zoneIDs:%@; >"
+ "<%@: contextTriggers:%@; >"
+ "<%@: contributorNodeID:%@; contributorEndpointID:%@; contributorName:%@; contributorHealth:%@; >"
+ "<%@: eventStartTimePos:%@; eventStartTimeSys:%@; >"
+ "<%@: identifiedContextID:%@; identifiedContext:%@; previousZone:%@; currentZone:%@; startTime:%@; endTime:%@; >"
+ "<%@: minPower:%@; maxPower:%@; cause:%@; endTime:%@; >"
+ "<%@: minPower:%@; maxPower:%@; duration:%@; cause:%@; >"
+ "<%@: networkIdentityIndex:%@; networkIdentityType:%@; clientIndex:%@; identifier:%@; >"
+ "<%@: numberOfResults:%@; proxyScanResult:%@; >"
+ "<%@: overVoltageThreshold:%@; underVoltageThreshold:%@; overFrequencyThreshold:%@; underFrequencyThreshold:%@; overPowerThreshold:%@; underPowerThreshold:%@; overCurrentThreshold:%@; underCurrentThreshold:%@; powerImportThreshold:%@; powerExportThreshold:%@; >"
+ "<%@: removedContributor:%@; >"
+ "<%@: sessionID:%@; message:%@; >"
+ "<%@: sessionID:%@; responseTimeout:%@; message:%@; >"
+ "<%@: sessionID:%@; sourceNodeId:%@; >"
+ "<%@: sessionID:%@; sourceNodeId:%@; sourceStartTimestamp:%@; newIdentifiedContexts:%@; currentIdentifiedContexts:%@; expiredContexts:%@; >"
+ "<%@: sessionID:%@; sourceNodeId:%@; triggeredZones:%@; >"
+ "<%@: statusChangedContributor:%@; >"
+ "<%@: tariffComponentID:%@; price:%@; friendlyCredit:%@; auxiliaryLoad:%@; peakPeriod:%@; powerThreshold:%@; threshold:%@; label:%@; predicted:%@; externalID:%@; >"
+ "<%@: transport:%@; timeout:%@; wiFiBands:%@; >"
+ "<%@: transport:%@; wiFiBands:%@; >"
+ "AVAnalysis"
+ "ActivateAnalysisStream"
+ "ActiveAmbientContextTriggers"
+ "AmbientSensingUnion"
+ "AnalysisSessionEnd"
+ "AnalysisSessionStart"
+ "AnalysisStreams"
+ "AppleThreadResetCountBootRelativeTime"
+ "CacheTimeout"
+ "CachedResults"
+ "CancelPowerRangeAdjustRequest"
+ "Commissioning By Proxy"
+ "CommissioningProxy"
+ "CurrentAnalysisStreamCount"
+ "DeactivateAnalysisStream"
+ "DisableContextTriggers"
+ "DisabledCabinets"
+ "Electrical Circuit Breaker"
+ "ElectricalAlarm"
+ "EnableContextTriggers"
+ "EstablishAnalysisStream"
+ "EstablishAnalysisStreamResponse"
+ "GroupPeerTable: Evicting %s peer %08X%08X due to table being full"
+ "JCMTrustVerification"
+ "MaxAnalysisStreamCount"
+ "MaxCachedResults"
+ "MaxSessions"
+ "Mdns: Failed to allocate %u TXT entries"
+ "Mdns: Failed to allocate %u-byte TXT value"
+ "Mdns: Failed to allocate TXT key"
+ "Mdns: TXT record has %u entries; truncating to %u"
+ "NumCachedResults"
+ "ObjectCountThresholdReached"
+ "OverCurrentThreshold"
+ "OverFrequencyThreshold"
+ "OverPowerThreshold"
+ "OverVoltageThreshold"
+ "PerceivedContext"
+ "PowerExportThreshold"
+ "PowerImportThreshold"
+ "PowerRangeAdjustEnd"
+ "PowerRangeAdjustRequest"
+ "PowerRangeAdjustStart"
+ "PowerRangeAdjustment"
+ "ProxyBackGroundScanStartRequest"
+ "ProxyBackGroundScanStopRequest"
+ "ProxyConnectRequest"
+ "ProxyConnectResponse"
+ "ProxyDisconnectRequest"
+ "ProxyMessageRequest"
+ "ProxyMessageResponse"
+ "ProxyScanRequest"
+ "ProxyScanResponse"
+ "RemoveAnalysisStream"
+ "ScanMaxTime"
+ "SensorFusionSupported"
+ "SetElectricalAlarmThresholds"
+ "SupportedAmbientContexts"
+ "TemperatureControlledCabinetTopology"
+ "TestAttribute"
+ "TestHiddenManufacturerSpecific"
+ "Topology"
+ "TrackingEnabled"
+ "Transport"
+ "UnderCurrentThreshold"
+ "UnderFrequencyThreshold"
+ "UnderPowerThreshold"
+ "UnderVoltageThreshold"
+ "UnionContributorAdded"
+ "UnionContributorList"
+ "UnionContributorRemoved"
+ "UnionContributorStatusChanged"
+ "UnionHealth"
+ "UnionName"
+ "WiFiBand"
+ "bad_variant_access was thrown in -fno-exceptions mode"
+ "control"
+ "core_commissioning_stage_attestation_revocation_check"
+ "core_commissioning_stage_configure_tc_acknowledgements"
+ "core_commissioning_stage_jcm_trust_verification"
+ "core_commissioning_stage_primary_operational_network_failed"
+ "core_commissioning_stage_remove_thread_network_config"
+ "core_commissioning_stage_remove_wifi_network_config"
+ "core_commissioning_stage_request_thread_credentials"
+ "core_commissioning_stage_request_wifi_credentials"
+ "std::holds_alternative<NotSynced>(mSyncState)"
- "<%@: ambientContextDetected:%@; objectCountReached:%@; objectCount:%@; >"
- "<%@: ambientContextSensed:%@; detectionStartTime:%@; >"
- "<%@: clientIndex:%@; clientIdentifier:%@; networkIdentityIndex:%@; >"
- "<%@: cmafInterface:%@; segmentDuration:%@; chunkDuration:%@; sessionGroup:%@; trackName:%@; cencKey:%@; cencKeyID:%@; metadataEnabled:%@; >"
- "<%@: eventStartTime:%@; >"
- "<%@: groupKeySetID:%@; groupKeySecurityPolicy:%@; epochKey0:%@; epochStartTime0:%@; epochKey1:%@; epochStartTime1:%@; epochKey2:%@; epochStartTime2:%@; groupKeyMulticastPolicy:%@; >"
- "<%@: networkIdentityIndex:%@; networkIdentityType:%@; identifier:%@; >"
- "<%@: tariffComponentID:%@; price:%@; friendlyCredit:%@; auxiliaryLoad:%@; peakPeriod:%@; powerThreshold:%@; threshold:%@; label:%@; predicted:%@; >"
- "ObjectCountReached"
- "UnpoweredPhaseOverNFC"
- "mStatus == Status::NotSynced"
```
