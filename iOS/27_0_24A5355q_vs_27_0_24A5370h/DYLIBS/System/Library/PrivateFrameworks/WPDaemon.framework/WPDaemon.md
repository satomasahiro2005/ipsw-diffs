## WPDaemon

> `/System/Library/PrivateFrameworks/WPDaemon.framework/WPDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c820` | `0x5e4fc` | **`+0x1cdc`** |
| `__TEXT.__oslogstring` | `0xaa02` | `0xaf99` | **`+0x597`** |
| `__AUTH_CONST.__const` | `0x6b28` | `0x6e08` | **`+0x2e0`** |
| `__AUTH_CONST.__objc_const` | `0x8968` | `0x8a88` | **`+0x120`** |
| `__TEXT.__cstring` | `0x4940` | `0x4a52` | **`+0x112`** |
| `__TEXT.__gcc_except_tab` | `0x1188` | `0x1294` | **`+0x10c`** |
| `__AUTH_CONST.__cfstring` | `0x3780` | `0x3860` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x44c4` | `0x45a4` | **`+0xe0`** |
| `__DATA_CONST.__objc_selrefs` | `0x27d8` | `0x28b0` | **`+0xd8`** |
| `__TEXT.__unwind_info` | `0x1f90` | `0x2060` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x12d0` | `0x12f8` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x560` | `0x578` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x2c0` | `0x2d0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4b0` | `0x4b8` | **`+0x8`** |
| `__TEXT.__const` | `0x298` | `0x290` | **`-0x8`** |
| `__DATA.__bss` | `0x4` | `0x8` | **`+0x4`** |

### Other Changes

```diff

-2700.37.0.0.0
+2700.41.1.1.0

+  - /System/Library/PrivateFrameworks/Rapport.framework/Rapport

-  Functions: 3519
-  Symbols:   2937
-  CStrings:  1527
+  Functions: 3595
+  Symbols:   2974
+  CStrings:  1559
Symbols:
+ -[WPAdvertisingRequest needsIdentity]
+ -[WPAdvertisingRequest setNeedsIdentity:]
+ -[WPDAdvertisingManager addressMonitor]
+ -[WPDAdvertisingManager cachedNonConnectableAuthTag]
+ -[WPDAdvertisingManager dealloc]
+ -[WPDAdvertisingManager refreshHeySiriAuthTagInActiveRequests]
+ -[WPDAdvertisingManager setAddressMonitor:]
+ -[WPDAdvertisingManager setCachedNonConnectableAuthTag:]
+ -[WPDAdvertisingManager updateCachedAuthTag]
+ -[WPDaemonServer _identitiesEnsureStarted]
+ -[WPDaemonServer _identitiesGet]
+ -[WPDaemonServer identitiesNotifyToken]
+ -[WPDaemonServer identityArray]
+ -[WPDaemonServer identitySelf]
+ -[WPDaemonServer isDynamicScanEnabled]
+ -[WPDaemonServer setIdentitiesNotifyToken:]
+ -[WPDaemonServer setIdentityArray:]
+ -[WPDaemonServer setIdentitySelf:]
+ GCC_except_table109
+ GCC_except_table113
+ GCC_except_table119
+ GCC_except_table121
+ GCC_except_table125
+ GCC_except_table135
+ GCC_except_table139
+ GCC_except_table142
+ GCC_except_table151
+ GCC_except_table166
+ GCC_except_table179
+ GCC_except_table244
+ GCC_except_table248
+ GCC_except_table278
+ GCC_except_table71
+ _OBJC_CLASS_$_RPClient
+ _OBJC_IVAR_$_WPAdvertisingRequest._needsIdentity
+ _OBJC_IVAR_$_WPDAdvertisingManager._addressMonitor
+ _OBJC_IVAR_$_WPDAdvertisingManager._cachedNonConnectableAuthTag
+ _OBJC_IVAR_$_WPDaemonServer._identitiesNotifyToken
+ _OBJC_IVAR_$_WPDaemonServer._identityArray
+ _OBJC_IVAR_$_WPDaemonServer._identitySelf
+ __ZNSt3__110unique_ptrIN2BT12TimeAndTimer5Timer9TimerImplENS_14default_deleteIS4_EEE5resetB9fqe220106EPS4_
+ __ZNSt3__110unique_ptrIN2BT12TimeAndTimer5TimerENS_14default_deleteIS3_EEE5resetB9fqe220106EPS3_
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220106Ev
+ ___32-[WPDaemonServer _identitiesGet]_block_invoke
+ ___32-[WPDaemonServer _identitiesGet]_block_invoke_2
+ ___38-[WPDaemonServer isDynamicScanEnabled]_block_invoke
+ ___40-[WPDAdvertisingManager initWithServer:]_block_invoke_2
+ ___40-[WPDAdvertisingManager initWithServer:]_block_invoke_3
+ ___42-[WPDaemonServer _identitiesEnsureStarted]_block_invoke
+ ___42-[WPDaemonServer _identitiesEnsureStarted]_block_invoke_2
+ ___44-[WPDAdvertisingManager updateCachedAuthTag]_block_invoke
+ ___62-[WPDAdvertisingManager refreshHeySiriAuthTagInActiveRequests]_block_invoke
+ ___block_descriptor_104_e8_32s40r48r56r64r72r80r88r96r_e30_v32?0"WPScanRequest"8Q16^B24ls32l8r40l8r48l8r56l8r64l8r72l8r80l8r88l8r96l8
+ ___block_descriptor_48_e8_32s40w_e29_v24?0"NSArray"8"NSError"16lw40l8s32l8
+ _isDynamicScanEnabled.sCached
+ _isDynamicScanEnabled.sDynamicScanSupported
- GCC_except_table103
- GCC_except_table106
- GCC_except_table117
- GCC_except_table120
- GCC_except_table126
- GCC_except_table137
- GCC_except_table146
- GCC_except_table164
- GCC_except_table174
- GCC_except_table239
- GCC_except_table243
- GCC_except_table273
- GCC_except_table69
- GCC_except_table75
- GCC_except_table96
- __ZNSt3__110unique_ptrIN2BT12TimeAndTimer5Timer9TimerImplENS_14default_deleteIS4_EEE5resetB9fqe220100EPS4_
- __ZNSt3__110unique_ptrIN2BT12TimeAndTimer5TimerENS_14default_deleteIS3_EEE5resetB9fqe220100EPS3_
- __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220100Ev
- ___block_descriptor_96_e8_32s40r48r56r64r72r80r88r_e30_v32?0"WPScanRequest"8Q16^B24ls32l8r40l8r48l8r56l8r64l8r72l8r80l8r88l8
CStrings:
+ "DynamicScanReconfig"
+ "Failed to get controllerInfo for DynamicScanReconfig check: %@"
+ "HSWithIdentity"
+ "HeySiri needsIdentity but no cached auth tag available"
+ "LECAHap"
+ "LECAHapLow"
+ "LECATmap"
+ "LECATmapLow"
+ "RPIdentity: BLE address changed, refreshing auth tag"
+ "RPIdentity: HeySiri adv data length=%lu (expected %lu for identity ext)"
+ "RPIdentity: HeySiri advertisement with auth tag exceeds max length (%lu)"
+ "RPIdentity: Rapport not available"
+ "RPIdentity: cannot refresh active HeySiri advertisements; cached auth tag invalid (len=%lu). Active advertisements may continue broadcasting a stale tag bound to the previous BLE address."
+ "RPIdentity: cannot update auth tag (identitySelf=%@ addressLen=%ld)"
+ "RPIdentity: fetch failed: %@"
+ "RPIdentity: fetched self=%@ others=%ld"
+ "RPIdentity: fetching identities"
+ "RPIdentity: identities changed, refreshing"
+ "RPIdentity: injected auth tag into HeySiri advertisement (total len=%lu)"
+ "RPIdentity: no matching identity for HeySiri peer %@ (identities cached: %ld)"
+ "RPIdentity: refreshed auth tag in active HeySiri advertisement"
+ "RPIdentity: resolved identity for HeySiri peer %@"
+ "RPIdentity: skipping refresh, unexpected HeySiri adv length %lu"
+ "RPIdentity: skipping verification, no valid address for HeySiri peer %@"
+ "RPIdentity: starting identity monitoring"
+ "RPIdentity: updated cached auth tag=%@ address=%@"
+ "RPIdentity: verifying authTag=%@ address=%@ identities=%ld"
+ "The payload size is too large after auth tag injection"
+ "WPDaemon iOS 27.0 (24A5370g) (WirelessProximity-2700.41.1.1) (Release) built on 2026-06-18 19:42:01"
+ "com.apple.rapport.identitiesChanged"
+ "com.apple.siri-device-selection-tool"
+ "com.apple.siri-network-tool"
+ "hasHeySiriScan assertCBDiscoveryScan bypassed — CBStackBLEScanner will not be suppressed"
+ "isDynamicScanEnabled=%d hasHSScan=%d"
+ "kDeviceRPIdentity"
+ "kNeedsIdentity"
+ "v24@?0@\"NSArray\"8@\"NSError\"16"
- "LECA1"
- "LECA2"
- "LECA3"
- "LECA4"
- "WPDaemon iOS 27.0 (24A5355a) (WirelessProximity-2700.37) (Release) built on 2026-05-24 16:32:01"
```
