## KeychainCircle

> `/System/Library/PrivateFrameworks/KeychainCircle.framework/KeychainCircle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x298f4` | `0x29b18` | **`+0x224`** |
| `__AUTH_CONST.__objc_const` | `0x2c10` | `0x2d90` | **`+0x180`** |
| `__AUTH_CONST.__cfstring` | `0x3a80` | `0x3b60` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x36fb` | `0x37c6` | **`+0xcb`** |
| `__AUTH.__objc_data` | `0x5a0` | `0x640` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x1e2c` | `0x1ebc` | **`+0x90`** |
| `__DATA.__data` | `0x320` | `0x380` | **`+0x60`** |
| `__DATA_DIRTY.__objc_data` | `0xf0` | `0xa0` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x1288` | `0x12c0` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x1e0` | `0x200` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x7f0` | `0x810` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1200` | `0x121c` | **`+0x1c`** |
| `__DATA.__bss` | `0x170` | `0x180` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x88` | `0x98` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x214` | `0x21c` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2e8` | `0x2f0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xa8` | `0xb0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1078` | `0x1080` | **`+0x8`** |

### Other Changes

```diff

-62460.2.3.0.0
+62460.40.49.502.1

-  Functions: 779
-  Symbols:   1853
-  CStrings:  797
+  Functions: 786
+  Symbols:   1886
+  CStrings:  804
Symbols:
+ +[AAFAnalyticsEventSecurity reporterRTCAdapter]
+ +[AAFAnalyticsEventSecurity setReporterRTCAdapter:]
+ +[MetricSessionInfo sessionInfoWithAltDSID:]
+ +[MetricSessionInfo sessionInfoWithAltDSID:flowID:deviceSessionID:]
+ -[AAFAnalyticsEventSecurity initWithMetrics:session:eventName:]
+ -[AAFAnalyticsEventSecurity initWithMetrics:session:eventName:canSendMetrics:]
+ -[AAFAnalyticsEventSecurity initWithSession:eventName:]
+ -[MetricSessionInfo .cxx_destruct]
+ -[MetricSessionInfo altDSID]
+ -[MetricSessionInfo deviceSessionID]
+ -[MetricSessionInfo flowID]
+ -[MetricSessionInfo initWithAltDSID:]
+ -[MetricSessionInfo initWithAltDSID:flowID:deviceSessionID:]
+ -[SecurityAnalyticsReporterRTCActualAdapter init]
+ -[SecurityAnalyticsReporterRTCActualAdapter sendEvent:]
+ GCC_except_table527
+ GCC_except_table537
+ GCC_except_table539
+ _OBJC_CLASS_$_MetricSessionInfo
+ _OBJC_CLASS_$_SecurityAnalyticsReporterRTCActualAdapter
+ _OBJC_IVAR_$_MetricSessionInfo._altDSID
+ _OBJC_IVAR_$_MetricSessionInfo._deviceSessionID
+ _OBJC_IVAR_$_MetricSessionInfo._flowID
+ _OBJC_METACLASS_$_MetricSessionInfo
+ _OBJC_METACLASS_$_SecurityAnalyticsReporterRTCActualAdapter
+ __OBJC_$_CLASS_METHODS_MetricSessionInfo
+ __OBJC_$_INSTANCE_METHODS_MetricSessionInfo
+ __OBJC_$_INSTANCE_METHODS_SecurityAnalyticsReporterRTCActualAdapter
+ __OBJC_$_INSTANCE_VARIABLES_MetricSessionInfo
+ __OBJC_$_PROP_LIST_MetricSessionInfo
+ __OBJC_$_PROP_LIST_SecurityAnalyticsReporterRTCActualAdapter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SecurityAnalyticsReporterRTCAdapter
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SecurityAnalyticsReporterRTCAdapter
+ __OBJC_$_PROTOCOL_REFS_SecurityAnalyticsReporterRTCAdapter
+ __OBJC_CLASS_PROTOCOLS_$_SecurityAnalyticsReporterRTCActualAdapter
+ __OBJC_CLASS_RO_$_MetricSessionInfo
+ __OBJC_CLASS_RO_$_SecurityAnalyticsReporterRTCActualAdapter
+ __OBJC_LABEL_PROTOCOL_$_SecurityAnalyticsReporterRTCAdapter
+ __OBJC_METACLASS_RO_$_MetricSessionInfo
+ __OBJC_METACLASS_RO_$_SecurityAnalyticsReporterRTCActualAdapter
+ __OBJC_PROTOCOL_$_SecurityAnalyticsReporterRTCAdapter
+ ___47+[AAFAnalyticsEventSecurity reporterRTCAdapter]_block_invoke
+ ___55-[SecurityAnalyticsReporterRTCActualAdapter sendEvent:]_block_invoke
+ __reporterRTCAdapterOverride
+ _kSecurityRTCEventNamePrepareTDIDPresence
+ _kSecurityRTCEventNameTDLTDIDDuplicates
+ _kSecurityRTCEventNameTDLTDIDStability
+ _kSecurityRTCFieldAllowedRecordCount
+ _kSecurityRTCFieldDisallowedRecordCount
+ _kSecurityRTCFieldMachineRecordAllowed
+ _kSecurityRTCFieldStableIDDuplicateDeviceCount
+ _kSecurityRTCFieldStableTrustedDeviceIDInclusionEnabled
+ _reporterRTCAdapter.defaultAdapter
+ _reporterRTCAdapter.onceToken
+ _sendEvent:.onceToken
+ _sendEvent:.rtcReporter
- +[SecurityAnalyticsReporterRTC rtcAnalyticsReporter]
- -[AAFAnalyticsEventSecurity areTestsEnabled]
- -[AAFAnalyticsEventSecurity initWithCKKSMetrics:altDSID:eventName:testsAreEnabled:category:sendMetric:]
- -[AAFAnalyticsEventSecurity initWithKeychainCircleMetrics:altDSID:eventName:category:]
- -[AAFAnalyticsEventSecurity initWithKeychainCircleMetrics:altDSID:flowID:deviceSessionID:eventName:testsAreEnabled:canSendMetrics:category:]
- -[AAFAnalyticsEventSecurity setAreTestsEnabled:]
- GCC_except_table530
- GCC_except_table540
- GCC_except_table542
- _MetricsDisable
- _MetricsEnable
- _MetricsOverrideTestsAreEnabled
- _OBJC_CLASS_$_SecurityAnalyticsReporterRTC
- _OBJC_IVAR_$_AAFAnalyticsEventSecurity._areTestsEnabled
- _OBJC_METACLASS_$_SecurityAnalyticsReporterRTC
- __OBJC_$_CLASS_METHODS_SecurityAnalyticsReporterRTC
- __OBJC_CLASS_RO_$_SecurityAnalyticsReporterRTC
- __OBJC_METACLASS_RO_$_SecurityAnalyticsReporterRTC
- ___52+[SecurityAnalyticsReporterRTC rtcAnalyticsReporter]_block_invoke
- _kSecurityRTCEventNameTDLDuplicateStableID
- _metricsAreEnabled
- _rtcAnalyticsReporter.onceToken
- _rtcAnalyticsReporter.rtcReporter
CStrings:
+ "allowedRecordCount"
+ "com.apple.security.prepareTDIDPresence"
+ "com.apple.security.tdlTDIDDuplicates"
+ "com.apple.security.tdlTDIDStability"
+ "disallowedRecordCount"
+ "machineRecordAllowed"
+ "stableIDDuplicateDeviceCount"
+ "stableTrustedDeviceIDInclusionEnabled"
- "com.apple.security.tdlDuplicateStableID"
```
