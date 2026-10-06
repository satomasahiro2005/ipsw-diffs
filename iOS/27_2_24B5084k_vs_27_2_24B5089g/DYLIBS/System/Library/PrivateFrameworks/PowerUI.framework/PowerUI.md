## PowerUI

> `/System/Library/PrivateFrameworks/PowerUI.framework/PowerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd9ef8` | `0xd9fd4` | **`+0xdc`** |
| `__TEXT.__oslogstring` | `0xf16f` | `0xf1a2` | **`+0x33`** |
| `__AUTH_CONST.__cfstring` | `0xdca0` | `0xdcc0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xf815` | `0xf81d` | **`+0x8`** |

### Other Changes

```diff

-753.40.6.0.0
+753.40.8.0.0

-  CStrings:  3214
+  CStrings:  3216
Functions:
~ -[PowerUIDemoCECManager recordEntryInDefaults:withChargeDecisionReason:atBatteryLevel:] : 1948 -> 2168
CStrings:
+ "Skipping recordEntryInDefaults: algoManager is nil"
+ "unknown"
```
