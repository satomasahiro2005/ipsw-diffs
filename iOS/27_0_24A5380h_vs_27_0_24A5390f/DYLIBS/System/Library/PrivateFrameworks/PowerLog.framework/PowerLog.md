## PowerLog

> `/System/Library/PrivateFrameworks/PowerLog.framework/PowerLog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ee98` | `0x1efa8` | **`+0x110`** |
| `__TEXT.__const` | `0xf00` | `0xf30` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x2980` | `0x29a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x23b6` | `0x23be` | **`+0x8`** |

### Other Changes

```diff

-3486.0.46.502.1
+3486.0.81.502.4

-  CStrings:  686
+  CStrings:  687
Functions:
~ +[PLModelingUtilities defaultBatteryEnergyCapacity] : 6324 -> 6528
~ _PLSysdiagnoseCopyPowerlog : 328 -> 396
CStrings:
+ "TimeOut"
```
