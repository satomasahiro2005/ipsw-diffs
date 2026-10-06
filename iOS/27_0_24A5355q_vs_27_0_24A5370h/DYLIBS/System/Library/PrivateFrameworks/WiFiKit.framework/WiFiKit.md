## WiFiKit

> `/System/Library/PrivateFrameworks/WiFiKit.framework/WiFiKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa47bc` | `0xa4928` | **`+0x16c`** |
| `__TEXT.__oslogstring` | `0xb8f7` | `0xb962` | **`+0x6b`** |
| `__DATA_CONST.__objc_selrefs` | `0x4eb8` | `0x4f18` | **`+0x60`** |
| `__TEXT.__const` | `0x7a3` | `0x7c3` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xcf8` | `0xd08` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1ee0` | `0x1ef0` | **`+0x10`** |

### Other Changes

```diff

-1205.55.0.0.0
+1205.59.4.1.0

-  Symbols:   6897
+  Symbols:   6899
Symbols:
+ _CWFEventLinkChangeStatusKey
+ _CWFEventWiFiUIStateFlagsKey
CStrings:
+ "CWFEventTypeCountryCodeChanged"
+ "CWFEventTypeIPChanged - type=%lu info=%@"
+ "CWFEventTypeJoinStatusChanged - errCode=%ld auto=%d durMs=%lu assocMs=%lu authMs=%lu linkUpMs=%lu"
+ "CWFEventTypeKnownNetworkProfileChanged - changeType=%ld"
+ "CWFEventTypeLinkChanged - down=%d involuntary=%d reason=%d subreason=%ld debounce=%d rssi=%ld noise=%ld cca=%lu"
+ "CWFEventTypeLinkQuality - %@"
+ "CWFEventTypePowerChanged"
+ "CWFEventTypeSSIDChanged"
+ "CWFEventTypeUserSettingsChanged"
+ "CWFEventTypeWiFiUIScanResultsDidChange - count=%lu"
+ "CWFEventTypeWiFiUIScanResultsDidFinish - count=%lu errCode=%ld"
+ "CWFEventTypeWiFiUIStateFlagsChanged - flags=0x%lx"
- "CWFEventTypeCountryCodeChanged - event %@"
- "CWFEventTypeIPChanged - event='%@'"
- "CWFEventTypeJoinStatusChanged - event='%@'"
- "CWFEventTypeKnownNetworkProfileChanged - event %@"
- "CWFEventTypeLinkChanged - event %@"
- "CWFEventTypeLinkQuality - event='%@'"
- "CWFEventTypePowerChanged - event %@"
- "CWFEventTypeSSIDChanged - event %@"
- "CWFEventTypeUserSettingsChanged - event='%@'"
- "CWFEventTypeWiFiUIScanResultsDidChange - event %@"
- "CWFEventTypeWiFiUIScanResultsDidFinish - event %@"
- "CWFEventTypeWiFiUIStateFlagsChanged - event %@"
```
