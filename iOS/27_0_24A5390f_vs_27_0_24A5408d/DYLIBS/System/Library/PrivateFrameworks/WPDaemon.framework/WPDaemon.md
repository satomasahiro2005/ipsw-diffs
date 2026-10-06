## WPDaemon

> `/System/Library/PrivateFrameworks/WPDaemon.framework/WPDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4a80` | `0x4a6f` | **`-0x11`** |
| `__TEXT.__text` | `0x5e4fc` | `0x5e50c` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-2700.46.1.1.0
+2700.51.1.1.0

-  CStrings:  1560
+  CStrings:  1559
Functions:
~ -[WPScanRequest convertUseCaseToString:] : 3640 -> 3660
~ sub_2b55394d8 -> sub_2b54bc4ec : 68 -> 64
CStrings:
+ "WPDaemon iOS 27.0 (24A5408a) (WirelessProximity-2700.51.1.1) (Release) built on 2026-08-04 23:57:11"
- "MockA2DPActivity"
- "WPDaemon iOS 27.0 (24A5390e) (WirelessProximity-2700.46.1.1) (Release) built on 2026-07-16 20:40:43"
```
