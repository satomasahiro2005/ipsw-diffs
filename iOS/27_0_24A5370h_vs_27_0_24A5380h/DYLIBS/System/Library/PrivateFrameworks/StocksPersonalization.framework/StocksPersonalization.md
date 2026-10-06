## StocksPersonalization

> `/System/Library/PrivateFrameworks/StocksPersonalization.framework/StocksPersonalization`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x604a4` | `0x5fe38` | **`-0x66c`** |
| `__AUTH.__data` | `0x1d8` | `0x140` | **`-0x98`** |
| `__DATA.__bss` | `0x3080` | `0x3000` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x2d00` | `0x2d80` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x2d10` | `0x2c98` | **`-0x78`** |
| `__DATA_DIRTY.__data` | `0x2610` | `0x2670` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x12f8` | `0x12d0` | **`-0x28`** |
| `__TEXT.__swift5_capture` | `0xad4` | `0xab4` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x2638` | `0x2650` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0xbf2` | `0xbe0` | **`-0x12`** |
| `__TEXT.__objc_methlist` | `0xd34` | `0xd44` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1690` | `0x1688` | **`-0x8`** |
| `__TEXT.__cstring` | `0x2564` | `0x2566` | **`+0x2`** |

### Other Changes

```diff

-2018.0.0.0.0
+2020.0.0.0.0

+  - /System/Library/PrivateFrameworks/AppUserEvents.framework/AppUserEvents

-  - /System/Library/PrivateFrameworks/NewsUserEvents.framework/NewsUserEvents

+  - /System/Library/PrivateFrameworks/_AppUserEvents_AppAnalytics.framework/_AppUserEvents_AppAnalytics

-  Functions: 2134
-  Symbols:   675
+  Functions: 2126
+  Symbols:   665
Symbols:
+ _associated conformance 21StocksPersonalization010Com_Apple_a1_B8_SessionV13AppUserEvents0g5EventE0AA0I0AdEP_AD0gI0
+ _associated conformance 21StocksPersonalization0A19UserEventSerializerC04NewsB007BridgedcdE0AA7SessionAdEP_03AppC6Events0cdH0
+ _symbolic $s13AppUserEvents0B12EventSessionP
+ _symbolic _____y_____G 13AppUserEvents0B12EventHistoryC 21StocksPersonalization010Com_Apple_f1_g8_SessionD0V
- __Block_copy
- __Block_release
- __NSConcreteStackBlock
- _associated conformance 21StocksPersonalization010Com_Apple_a1_B8_SessionV14NewsUserEvents0g5EventE0AA0I0AdEP_AD0gI0
- _associated conformance 21StocksPersonalization0A19UserEventSerializerC04NewsB007BridgedcdE0AA7SessionAdEP_0fC6Events0cdH0
- _block_copy_helper
- _block_descriptor
- _block_destroy_helper
- _swift_isEscapingClosureAtFileLocation
- _swift_retain_x2
- _symbolic $s14NewsUserEvents0B12EventSessionP
- _symbolic _____Ign_ 10Foundation3URLV
- _symbolic _____Sg 10Foundation3URLV
- _symbolic _____y_____G 14NewsUserEvents0B12EventHistoryC 21StocksPersonalization010Com_Apple_f1_g8_SessionD0V
CStrings:
+ "Failed to export stocks user event history for radar attachment with error=%{public}@"
+ "stocks-user-event-history.zip"
- "Failed to copy stocks user event history for radar attachment with error=%{public}@"
- "stocks-user-event-history-"
```
