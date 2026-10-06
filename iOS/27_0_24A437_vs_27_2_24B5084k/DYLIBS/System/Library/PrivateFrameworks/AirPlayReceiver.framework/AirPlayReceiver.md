## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/AirPlayReceiver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17be4c` | `0x17c374` | **`+0x528`** |
| `__TEXT.__cstring` | `0x33175` | `0x33200` | **`+0x8b`** |
| `__AUTH_CONST.__cfstring` | `0xba60` | `0xbac0` | **`+0x60`** |
| `__TEXT.__const` | `0x275db` | `0x2762b` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x9400` | `0x9420` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1690` | `0x16a8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1e30` | `0x1e40` | **`+0x10`** |
| `__DATA.__bss` | `0x5e8` | `0x5f8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x988` | `0x998` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xbe0` | `0xbf0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x834` | `0x838` | **`+0x4`** |

### Other Changes

```diff

-980.77.1.2.0
+1005.7.1.0.0

-  Functions: 1703
-  Symbols:   3579
-  CStrings:  5194
+  Functions: 1706
+  Symbols:   3588
+  CStrings:  5200
Symbols:
+ GCC_except_table1005
+ GCC_except_table1118
+ GCC_except_table1137
+ GCC_except_table1192
+ GCC_except_table1245
+ GCC_except_table1253
+ GCC_except_table1255
+ GCC_except_table1299
+ GCC_except_table1362
+ GCC_except_table209
+ GCC_except_table216
+ GCC_except_table222
+ GCC_except_table411
+ GCC_except_table474
+ GCC_except_table523
+ GCC_except_table587
+ GCC_except_table594
+ GCC_except_table602
+ GCC_except_table739
+ _APAdvertiserUpdateAdvertising
+ _APSIsTerminusMeshRegistrationEnabled
+ _APTransportSocketQoSFromConnectionQoS
+ _OBJC_CLASS_$_NSFileManager
+ __APAdvertiserUpdateAdvertising
+ __IsWiFiDECaptureAllowed.sBuildAllowsCapture
+ __IsWiFiDECaptureAllowed.sOnce
+ __UpdateAdvertisingIfStarted
+ ___APAdvertiserUpdateAdvertising_block_invoke
+ ____IsWiFiDECaptureAllowed_block_invoke
+ _kAPReceiverAudioSessionOption_AudioQoS
+ _kAPReceiverAudioSessionOption_RTCPQoS
+ _kAPTransportConnectionOption_QualityOfService
+ _sysInfo_updateAdvertiserInfo
- GCC_except_table1001
- GCC_except_table1114
- GCC_except_table1133
- GCC_except_table1184
- GCC_except_table1241
- GCC_except_table1249
- GCC_except_table1251
- GCC_except_table1296
- GCC_except_table1359
- GCC_except_table208
- GCC_except_table214
- GCC_except_table220
- GCC_except_table409
- GCC_except_table472
- GCC_except_table521
- GCC_except_table579
- GCC_except_table590
- GCC_except_table598
- GCC_except_table735
- __APAdvertiserProcessP2PConfig
- __UpdateAdvertiserInfo
- ___APAdvertiserBTLEManagerUpdatePreferences_block_invoke
- _kAPAdvertiserProperty_AdvertiserInfo
- _kAPAdvertiserProperty_P2PConfig
CStrings:
+ "/private/var/Managed Preferences/mobile/com.apple.wifianalyticsd.plist"
+ "1005.7.1"
+ "APAdvertiser.%{ptr}.dnssd"
+ "APAdvertiser.%{ptr}.nan"
+ "APAdvertiserUpdateAdvertising"
+ "AudioQoS"
+ "Dispatching onto HTTP queue in order to handle stall state: %u\n"
+ "Handling of stall state: %u finished\n"
+ "Now running on HTTP queue in order to handle stall state: %u\n"
+ "OSStatus _UpdateAdvertisingIfStarted(AirPlayReceiverServerRef)"
+ "RTCPQoS"
+ "Skipping WiFiDiagnosticExtension capture (%@): not collected on this build\n"
+ "_APAdvertiserApplyAdvertiserInfo"
+ "_APAdvertiserUpdateAdvertising"
+ "streamConnectionKeyQoS"
+ "sysInfo_updateAdvertiserInfo"
+ "tightSyncGroupUUID"
+ "void _PostAdvertisingDidChange(void)"
- "980.77.1.2"
- "Call to WiFiDiagnosticExtension for stall state: %u finished\n"
- "Dispatching onto HTTP queue in order to call WiFiDiagnosticExtension for stall state: %u\n"
- "Now running on HTTP queue in order to call WiFiDiagnosticExtension for stall state: %u\n"
- "OSStatus _UpdateAdvertiserInfo(AirPlayReceiverServerRef)"
- "OSStatus _UpdateAdvertising(AirPlayReceiverServerRef)"
- "Terminus_MeshRegistration"
- "_APAdvertiserProcessP2PConfig"
- "_APAdvertiserSetAdvertiserInfo"
- "_UpdateAdvertiserInfo"
- "_UpdateAdvertiserP2PConfig"
- "advertiserInfo"
```
