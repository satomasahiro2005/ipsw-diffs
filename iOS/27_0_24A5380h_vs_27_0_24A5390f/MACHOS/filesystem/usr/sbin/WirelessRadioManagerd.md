## WirelessRadioManagerd

> `/usr/sbin/WirelessRadioManagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x170d3c` | `0x1713d8` | **`+0x69c`** |
| `__TEXT.__cstring` | `0x59fd1` | `0x5a193` | **`+0x1c2`** |
| `__DATA_CONST.__cfstring` | `0x32e80` | `0x32f60` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x34630` | `0x346a6` | **`+0x76`** |
| `__DATA.__objc_const` | `0x1cf18` | `0x1cf78` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x216e0` | `0x21720` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x5858` | `0x5888` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x11bdc` | `0x11bf4` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x8afe` | `0x8b16` | **`+0x18`** |
| `__DATA.__common` | `0x642` | `0x632` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0xa028` | `0xa038` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x26e0` | `0x26f0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1e7c` | `0x1e88` | **`+0xc`** |
| `__DATA.__data` | `0x840` | `0x838` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x1388` | `0x1390` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x50e8` | `0x50f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-1935.2.0.0.0
+1937.1.0.0.0

-  Functions: 7805
-  Symbols:   873
-  CStrings:  16861
+  Functions: 7810
+  Symbols:   874
+  CStrings:  16874
Symbols:
+ _WiFiDeviceClientRegisterPowerCallback
CStrings:
+ "%s Received RRC state: %d from BB"
+ "ON"
+ "WiFiS: callbackWiFiDeviceClientPower power is %s"
+ "^{WRMMetricsGenericCellularScore=dIQIdddIIIIIIBB}16@0:8"
+ "evaluateGenericCellularScore RRC idle with history: finalScore: %s"
+ "getForegroundApp app: %@, webkit streaming active: %s"
+ "handleGamingStateChange state=%d, appId=%@"
+ "handleVoIPStateChange state=%d, appId=%@"
+ "handleVoIPandStreamingStateChange state=%d, appId=%@"
+ "handleWebKitStateChange state=%d, appId=%@"
+ "mAudioAccessoryTkn"
+ "mPrevAudioBandMessage"
+ "mPrevAudioMessage"
+ "maybeNotifyStreamingStop"
+ "maybeNotifyStreamingStop: mStreamingConnectionReferenceCount: %llu, mWebkitStreamingActiveRefCnt: %d, mForegroundRunningVoipAndStreamingApps.count: %lu, mForegroundRunningStreamingApps.count: %lu"
+ "maybeNotifyStreamingStop: notify streaming stop"
+ "smartLQM"
+ "startMonitoringAppSessions %@ configuration status: %d, for app: %@"
+ "startMonitoringAppSessions %@ start monitoring for app: %@"
+ "updateWebkitStreamingActiveStatus"
+ "updateWebkitStreamingActiveStatus: resetting refcount from %d to 0"
+ "{WRMMetricsGenericCellularScore=\"timestamp\"d\"lastCellScore\"I\"lastCellScoreDuration\"Q\"currentCellScore\"I\"rsrp\"d\"rsrq\"d\"snr\"d\"dataLQM\"I\"voiceLQM\"I\"smartLQM\"I\"dlConf\"I\"dlBw\"I\"rrcState\"I\"wifiPrimary\"B\"historicalInfoGood\"B}"
- "WiFiS: callbackWiFiDeviceClientDeviceAvailable Power ON due to DextCrash recovery"
- "^{WRMMetricsGenericCellularScore=dIQIdddIIIIBB}16@0:8"
- "evaluateGenericCellularScore RRC idle with history: dataLQM: %d, finalScore: %s"
- "handleGamingStateChange state= %d, appId=%@"
- "handleVoIPStateChange state= %d, appId=%@"
- "handleVoIPandStreamingStateChange state= %d, appId=%@"
- "handleWebKitStateChange state= %d, appId=%@"
- "stats manager configuration status %d"
- "{WRMMetricsGenericCellularScore=\"timestamp\"d\"lastCellScore\"I\"lastCellScoreDuration\"Q\"currentCellScore\"I\"rsrp\"d\"rsrq\"d\"snr\"d\"dataLQM\"I\"dlConf\"I\"dlBw\"I\"rrcState\"I\"wifiPrimary\"B\"historicalInfoGood\"B}"
```
