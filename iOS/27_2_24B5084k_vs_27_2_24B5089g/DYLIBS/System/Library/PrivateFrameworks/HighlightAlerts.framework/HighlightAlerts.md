## HighlightAlerts

> `/System/Library/PrivateFrameworks/HighlightAlerts.framework/HighlightAlerts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a280` | `0x5ca00` | **`+0x2780`** |
| `__DATA_DIRTY.__data` | `0x1828` | `0x19f8` | **`+0x1d0`** |
| `__DATA_DIRTY.__bss` | `0x1a00` | `0x1b80` | **`+0x180`** |
| `__AUTH_CONST.__objc_const` | `0x1320` | `0x1410` | **`+0xf0`** |
| `__TEXT.__const` | `0x3b44` | `0x3c34` | **`+0xf0`** |
| `__TEXT.__swift5_reflstr` | `0x11e9` | `0x1299` | **`+0xb0`** |
| `__DATA.__bss` | `0x4f20` | `0x4ea0` | **`-0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x1200` | `0x1280` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x1234` | `0x12ac` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0xcca` | `0xd38` | **`+0x6e`** |
| `__AUTH_CONST.__const` | `0x2ed8` | `0x2f28` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x628` | `0x678` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1268` | `0x12b0` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x1368` | `0x13b0` | **`+0x48`** |
| `__TEXT.__cstring` | `0x17d3` | `0x1803` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x1cd8` | `0x1d08` | **`+0x30`** |
| `__DATA_DIRTY.__common` | `0xb0` | `0xd8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x810` | `0x830` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x4d8` | `0x4f8` | **`+0x20`** |
| `__DATA.__common` | `0x50` | `0x38` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x630` | `0x648` | **`+0x18`** |
| `__AUTH.__data` | `0x508` | `0x4f8` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x180` | `0x190` | **`+0x10`** |
| `__DATA.__data` | `0x780` | `0x778` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x350` | `0x358` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x15c` | `0x164` | **`+0x8`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 1616
-  Symbols:   791
-  CStrings:  212
+  Functions: 1654
+  Symbols:   808
+  CStrings:  215
Symbols:
+ _OBJC_CLASS_$_NSNotificationCenter
+ __DATA__TtC15HighlightAlerts34HighlightAlertDismissalInputSignal
+ __IVARS__TtC15HighlightAlerts34HighlightAlertDismissalInputSignal
+ __METACLASS_DATA__TtC15HighlightAlerts34HighlightAlertDismissalInputSignal
+ _associated conformance 15HighlightAlerts0A25AlertDismissalInputSignalC19HealthOrchestration0eF0AA6AnchorAdEP_AD0efI0
+ _associated conformance 15HighlightAlerts0A25AlertDismissalInputSignalC19HealthOrchestration0eF0AAs23CustomStringConvertible
+ _flat unique So8NSObject_p
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic SbyYbc
+ _symbolic So20NSNotificationCenterC
+ _symbolic _____ 15HighlightAlerts0A25AlertDismissalInputSignalC
+ _symbolic _____ 15HighlightAlerts0A25AlertDismissalInputSignalC5State33_EA847480A0C8BC9153128CFF8F25F0E1LLV
+ _symbolic _____SgXw 15HighlightAlerts0A25AlertDismissalInputSignalC
+ _symbolic ______pSg So8NSObjectP
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 15HighlightAlerts0E25AlertDismissalInputSignalC5State33_EA847480A0C8BC9153128CFF8F25F0E1LLV
CStrings:
+ "HighlightAlertDismissalInputSignal"
+ "Recording dismissal of %{private}s into alert state."
+ "[%s] Began observing dismissals, anchor: %{public}s"
+ "[%s] Observed a dismissal, anchor: %{public}s"
- "Existing feed item for %{private}s is marked as hideInDiscover but corresponding alert state is not dismissed. Reconciling."
```
