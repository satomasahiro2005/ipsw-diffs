## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/AirPlayReceiver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0x0` | `0x980` | **`+0x980`** |
| `__TEXT.__text` | `0x17d188` | `0x17d6b4` | **`+0x52c`** |
| `__TEXT.__cstring` | `0x338bf` | `0x33c71` | **`+0x3b2`** |
| `__AUTH_CONST.__cfstring` | `0xbb80` | `0xbbe0` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x9480` | `0x9460` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x2098` | `0x20b0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x16b8` | `0x16a0` | **`-0x18`** |
| `__DATA.__bss` | `0x608` | `0x5f8` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1e50` | `0x1e58` | **`+0x8`** |

### Other Changes

```diff

-980.63.2.0.0
+980.67.2.0.0

-  Functions: 1711
-  Symbols:   3593
-  CStrings:  5236
+  Functions: 1708
+  Symbols:   3590
+  CStrings:  5250
Symbols:
+ GCC_except_table1004
+ GCC_except_table1116
+ GCC_except_table1135
+ GCC_except_table1186
+ GCC_except_table1190
+ GCC_except_table1243
+ GCC_except_table1251
+ GCC_except_table1253
+ GCC_except_table1298
+ GCC_except_table1361
+ GCC_except_table1370
+ GCC_except_table215
+ GCC_except_table222
+ GCC_except_table228
+ GCC_except_table417
+ GCC_except_table480
+ GCC_except_table529
+ GCC_except_table587
+ GCC_except_table591
+ GCC_except_table598
+ GCC_except_table606
+ GCC_except_table740
+ _BonjourAdvertiserSetNANPairingClientInfo
+ _audioSessionBufferedHose_setMulticastGroupInfo
+ _kAPReceiverAudioSessionOption_MulticastGroupInfo
- GCC_except_table1005
- GCC_except_table1119
- GCC_except_table1138
- GCC_except_table1189
- GCC_except_table1193
- GCC_except_table1246
- GCC_except_table1254
- GCC_except_table1256
- GCC_except_table1301
- GCC_except_table1364
- GCC_except_table1373
- GCC_except_table217
- GCC_except_table223
- GCC_except_table229
- GCC_except_table418
- GCC_except_table481
- GCC_except_table530
- GCC_except_table588
- GCC_except_table592
- GCC_except_table599
- GCC_except_table607
- GCC_except_table741
- _APTransportConnectionAddEventCallback
- _APTransportConnectionResume
- _CMBaseObjectSetProperty
- __APAdvertiserSetupBonjourAdvertiser.sBonjourAdvertiserSetNANPairingClientInfo
- __APAdvertiserSetupBonjourAdvertiser.sSetNANPairingClientInfoOnce
- ____APAdvertiserSetupBonjourAdvertiser_block_invoke
CStrings:
+ "### Auxiliary screen session already registered [%{ptr}], rejecting new one [%{ptr}]\n"
+ "980.67.2"
+ "Added an auxiliary screen session [%{ptr}] (paired with main [%{ptr}]); sessions array capacity %d\n"
+ "MulticastGroupInfo"
+ "PairedSessionEnded"
+ "Releasing auxiliary screen session; sessions array capacity %d\n"
+ "Terminating paired session [%{ptr}] (partner of [%{ptr}])\n"
+ "[%{ptr}] Auxiliary screen session reusing PWD context [%{ptr}] from primary session [%{ptr}] (clientDeviceID=%llu, protectionBits=0x%x)\n"
+ "[%{ptr}] Auxiliary screen session: clientDeviceID is 0\n"
+ "[%{ptr}] Auxiliary screen session: no primary mirroring session (clientDeviceID=%llu)\n"
+ "[%{ptr}] Auxiliary screen session: primary [%{ptr}] clientDeviceID=%llu mismatch (ours=%llu)\n"
+ "[%{ptr}] Auxiliary screen session: primary [%{ptr}] has not completed PWD key exchange\n"
+ "_AdoptPWDProtectionContextFromPrimaryScreenSession"
+ "isAuxiliaryScreenSession"
+ "multicastGroupInfo"
+ "void _AdoptPWDProtectionContextFromPrimaryScreenSession(AirPlayReceiverSessionRef)"
- "980.63.2"
- "BonjourAdvertiserSetNANPairingClientInfo"
```
