## WPDaemon

> `/System/Library/PrivateFrameworks/WPDaemon.framework/WPDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4b73` | `0x4b84` | **`+0x11`** |
| `__TEXT.__text` | `0x5fd64` | `0x5fd54` | **`-0x10`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-2701.3.0.0.0
+2701.7.0.0.0

-  CStrings:  1576
+  CStrings:  1577
Functions:
~ -[WPScanRequest convertUseCaseToString:] : 3660 -> 3640
~ sub_2bccde4f4 -> sub_2bcafc4e0 : 64 -> 68
CStrings:
+ "MusicHandoffScan"
+ "WPDaemon iOS 27.2 (24B5098u) (WirelessProximity-2701.7) (Release) built on 2026-09-27 23:14:45"
- "WPDaemon iOS 27.2 (24B5088s) (WirelessProximity-2701.3) (Release) built on 2026-09-13 19:56:53"
```
