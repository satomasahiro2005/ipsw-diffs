## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/WiFiPolicy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x7a8` | `0x6b8` | **`-0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0x3468` | `0x3558` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x25c2b` | `0x25ceb` | **`+0xc0`** |
| `__TEXT.__text` | `0xe2c04` | `0xe2b64` | **`-0xa0`** |
| `__TEXT.__eh_frame` | `0x98` | `—` | **`-0x98`** |
| `__AUTH_CONST.__cfstring` | `0x20d20` | `0x20da0` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x2738` | `0x2790` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0xf18` | `0xed8` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x13cf0` | `0x13d18` | **`+0x28`** |
| `__DATA.__bss` | `0x60` | `0x48` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xaf00` | `0xaf18` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x378` | `0x390` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x178` | `0x160` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0xb8` | `0xa4` | **`-0x14`** |
| `__AUTH_CONST.__objc_const` | `0x25970` | `0x25980` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xbc8` | `0xbb8` | **`-0x10`** |
| `__TEXT.__const` | `0x878` | `0x868` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x29f0` | `0x29e0` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xc0` | `0xb4` | **`-0xc`** |
| `__TEXT.__constg_swiftt` | `0x188` | `0x180` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x2564` | `0x2568` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-1070.55.0.0.0
+1070.59.0.0.0

-  Functions: 7203
-  Symbols:   11973
-  CStrings:  5315
+  Functions: 7205
+  Symbols:   11983
+  CStrings:  5319
Symbols:
+ -[WFLoggerFileWithTTL _stopWatchingLogFileOnQueue]
+ -[WiFiUsagePowerAnalytics collectCurrentNetworkInfo]
+ -[WiFiUsagePowerAnalytics mloConnection]
+ -[WiFiUsagePowerAnalytics setMloConnection:]
+ _OBJC_IVAR_$_WiFiUsagePowerAnalytics._mloConnection
+ ___30-[WFLoggerFileWithTTL dealloc]_block_invoke
+ ___39-[WFLoggerFileWithTTL checkForRotation]_block_invoke
+ ___42-[WFLoggerFileWithTTL stopWatchingLogFile]_block_invoke
+ ___46-[WFLoggerFileWithTTL WFLog:privacy:cfStrMsg:]_block_invoke
+ ___52-[WFLoggerFileWithTTL WFLog:privacy:message:valist:]_block_invoke
+ ___block_descriptor_56_e8_32o40o_e5_v8?0ls32l8s40l8
+ ___block_descriptor_56_e8_32o_e5_v8?0ls32l8
+ _swift_isEscapingClosureAtFileLocation
+ _swift_release_x19
+ _swift_release_x21
+ _swift_release_x24
+ _swift_retain_x21
+ _symbolic Ig_
- _swift_release_x26
- _swift_retain
- _swift_retain_x26
- _swift_weakDestroy
- _swift_weakInit
- _swift_weakLoadStrong
- _symbolic _____SgXw 10WiFiPolicy0aB19AONSenseBeaconCacheC
- _symbolic _____SgXwz_Xx 10WiFiPolicy0aB19AONSenseBeaconCacheC
CStrings:
+ "-[WFLoggerFileWithTTL _stopWatchingLogFileOnQueue]"
+ "25%"
+ "EMLSR_CONNECTION"
+ "MLO_CONNECTION"
+ "collectCurrentNetworkInfo - APPLE80211_IOC_CURRENT_NETWORK failed with error: %d"
+ "collectCurrentNetworkInfo - APPLE80211_IOC_CURRENT_NETWORK returned nil dict"
+ "collectCurrentNetworkInfo - No Apple80211 reference available"
+ "com.apple.WiFiPolicy.WFLoggerFileWithTTL"
- "-[WFLoggerFileWithTTL stopWatchingLogFile]"
- "LP_EMLSR_SUPPORTED"
- "WiFiUsagePowerAnalytics: extractMloLinkInfo - Processing %lu MLO links"
- "com.apple.wifi.aonsense.cache"
```
