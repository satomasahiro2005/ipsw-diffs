## WirelessRadioManagerd

> `/usr/sbin/WirelessRadioManagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1772a4` | `0x1776c4` | **`+0x420`** |
| `__TEXT.__cstring` | `0x5a831` | `0x5aa2f` | **`+0x1fe`** |
| `__DATA_CONST.__cfstring` | `0x33400` | `0x334c0` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x347ee` | `0x34893` | **`+0xa5`** |
| `__TEXT.__objc_stubs` | `0x21920` | `0x219c0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x11cac` | `0x11cec` | **`+0x40`** |
| `__DATA.__objc_const` | `0x1d038` | `0x1d068` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0xa080` | `0xa0a8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x51b0` | `0x51c8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x65a0` | `0x65b0` | **`+0x10`** |
| `__DATA.__bss` | `0x7f0` | `0x7f8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1e9c` | `0x1ea0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-1939.3.0.0.0
+1950.2.0.0.0

-  Functions: 7862
+  Functions: 7867

-  CStrings:  16934
+  CStrings:  16949
CStrings:
+ "%s state:%d"
+ "-[WCM_BTController handleBTMusicHandoff:]"
+ "TB,N,V_musicHandoffState"
+ "_musicHandoffState"
+ "_now2c"
+ "evaluateActiveCallQuality: RTP metrics ignored on current SSID, dropping RTP loss and jitter buffer terms"
+ "handleBTMusicHandoff:"
+ "handleBTMusicHandoffState"
+ "isMovingAverageAudioQualityOfCurrentCallGood: RTP metrics ignored on current SSID, dropping moving average RTP loss terms"
+ "isRTPMetricsIgnoredOnCurrentSSID"
+ "isRTPMetricsIgnoredOnCurrentSSID: true"
+ "isWiFiVoIPQualityGoodEnough: RTP metrics ignored on current SSID, suppressing handover. Rx Pkt loss: %llu, rxSpeechPktLoss: %llu, nominal buffer delay: %llu"
+ "kWCMBTMusicHandoffActive"
+ "musicHandoffState"
+ "setMusicHandoffState:"
```
