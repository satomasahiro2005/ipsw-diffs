## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/AirPlayReceiver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17c69c` | `0x17d188` | **`+0xaec`** |
| `__TEXT.__cstring` | `0x3371a` | `0x338bf` | **`+0x1a5`** |
| `__TEXT.__oslogstring` | `0x23b` | `0x2eb` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0xbb60` | `0xbb80` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x82c` | `0x848` | **`+0x1c`** |
| `__TEXT.__unwind_info` | `0x16a0` | `0x16b8` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x198` | `0x1a8` | **`+0x10`** |
| `__TEXT.__const` | `0x275b9` | `0x275a9` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1e48` | `0x1e50` | **`+0x8`** |

### Other Changes

```diff

-980.58.1.11.1
+980.63.2.0.0

-  Functions: 1710
-  Symbols:   3588
-  CStrings:  5223
+  Functions: 1711
+  Symbols:   3593
+  CStrings:  5236
Symbols:
+ GCC_except_table1005
+ GCC_except_table1119
+ GCC_except_table1138
+ GCC_except_table1189
+ GCC_except_table1193
+ GCC_except_table1246
+ GCC_except_table1254
+ GCC_except_table1256
+ GCC_except_table1301
+ GCC_except_table1364
+ GCC_except_table1373
+ GCC_except_table151
+ GCC_except_table156
+ GCC_except_table159
+ GCC_except_table167
+ GCC_except_table183
+ GCC_except_table194
+ GCC_except_table217
+ GCC_except_table223
+ GCC_except_table229
+ GCC_except_table418
+ GCC_except_table481
+ GCC_except_table530
+ GCC_except_table588
+ GCC_except_table592
+ GCC_except_table599
+ GCC_except_table607
+ GCC_except_table741
+ _APTransportGetCMBaseObject
+ _CFStringGetIntValue
+ ___73-[AirPlayReceiverMediaRemoteHelper startNowPlayingSessionWithCompletion:]_block_invoke_4
+ ___block_descriptor_44_e8_32b_e5_v8?0ls32l8
+ ___block_descriptor_56_e8_32o40b48r_e5_v8?0ls40l8r48l8s32l8
+ _airplayReqProcessor_deregisterReqProcWithSessionManagerIfNeeded
+ _kAPSAudioProtocolDriverReceiverProperty_RedundancyLevelHistogram
+ _kAPSAudioProtocolDriverReceiverProperty_RedundancyLevelHistogramCount
- GCC_except_table1004
- GCC_except_table1118
- GCC_except_table1137
- GCC_except_table1188
- GCC_except_table1192
- GCC_except_table1245
- GCC_except_table1253
- GCC_except_table1255
- GCC_except_table1300
- GCC_except_table1363
- GCC_except_table1372
- GCC_except_table154
- GCC_except_table158
- GCC_except_table165
- GCC_except_table182
- GCC_except_table193
- GCC_except_table215
- GCC_except_table222
- GCC_except_table228
- GCC_except_table417
- GCC_except_table480
- GCC_except_table529
- GCC_except_table587
- GCC_except_table591
- GCC_except_table598
- GCC_except_table606
- GCC_except_table740
- _FigTransportGetCMBaseObject
- ___block_descriptor_40_e8_32b_e5_v8?0ls32l8
- ___block_descriptor_56_e8_32o40b_e5_v8?0ls32l8s40l8
- _airplayReqProcessor_updateUserVersionIfProvided
CStrings:
+ "%@ Audio session create completed"
+ "%@ Creating buffered audio session hose\n"
+ "980.63.2"
+ "APRAS Platform Create"
+ "APRASBH Buffered Hose Create"
+ "APRASBH UnbufferedNW Connections Create and Resume"
+ "APRS Update Active Session Registration"
+ "APRSRV HTTP Request"
+ "HoseAU Create"
+ "Invalid during BTLE event %d."
+ "UserVersion"
+ "[%{ptr}] ### Failed to remove from session manager (type %d): %#m\n"
+ "[%{ptr}] <APConn> Downgrading not supported for non-shared connection [%{ptr}]. Closing instead.\n"
+ "[%{ptr}] General audio setup\n"
+ "[%{ptr}] Unexpected error removing speculative RC registration: %#m\n"
+ "[%{ptr}] _AudioStartPresentation\n"
+ "void _APAdvertiserBTLEEventHandler(APAdvertiserBTLEManagerRef, APAdvertiserBTLEEventType, CFTypeRef _Nullable)_block_invoke"
+ "void _AudioStartPresentation(AirPlayReceiverSessionRef, CFNumberRef, CFDictionaryRef)"
+ "void airplayReqProcessor_deregisterReqProcWithSessionManagerIfNeeded(APReceiverRequestProcessorRef, APReceiverSessionType, Boolean)"
- "980.58.1.11.1"
- "[%{ptr}] <APConn> Non-shared session [%{ptr}] can't be downgraded\n"
- "[%{ptr}] setting user version to %u\n"
- "airplayReqProcessor_DowngradeSession"
- "void AirPlayReceiverSessionSetUserVersion(AirPlayReceiverSessionRef, uint32_t)"
- "void _APAdvertiserBTLEEventHandler(APAdvertiserBTLEManagerRef, APAdvertiserBTLEEventType, void *)_block_invoke"
```
