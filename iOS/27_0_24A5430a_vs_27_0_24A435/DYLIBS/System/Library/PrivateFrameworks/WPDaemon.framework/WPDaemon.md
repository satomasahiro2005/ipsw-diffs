## WPDaemon

> `/System/Library/PrivateFrameworks/WPDaemon.framework/WPDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5e50c` | `0x5e514` | **`+0x8`** |
| `__TEXT.__cstring` | `0x4a6f` | `0x4a6d` | **`-0x2`** |
| `__TEXT.__oslogstring` | `0xaf99` | `0xaf97` | **`-0x2`** |

### Other Changes

```diff
Functions:
~ _OUTLINED_FUNCTION_2 -> _OUTLINED_FUNCTION_7 : 20 -> 12
~ _OUTLINED_FUNCTION_7 -> _OUTLINED_FUNCTION_2 : 12 -> 20
~ -[WPDState registerManager:].cold.2 : 64 -> 72
~ -[WPDState updateWithManager:Completion:].cold.2 : 68 -> 64
~ -[WPDState updateWithManager:Completion:].cold.4 : 64 -> 72
~ -[WPDState updateWithCompletion:].cold.2 : 100 -> 96
CStrings:
+ "WPDaemon iOS 27.0 (24A425) (WirelessProximity-2700.51.1.3) (Release) built on 2026-08-21 20:41:23"
- "WPDaemon iOS 27.0 (24A5417a) (WirelessProximity-2700.51.1.3) (Release) built on 2026-08-13 22:19:08"
```
