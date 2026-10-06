## BluetoothSettings

> `/System/Library/PreferenceBundles/BluetoothSettings.bundle/BluetoothSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x2172` | `0x2182` | **`+0x10`** |

### Other Changes

```diff

-2701.2.0.0.0
+2701.4.0.0.0
Symbols:
+ -[BTSDevicesController handleDADaemonSessionEvent:]
+ -[BTSDevicesController reinitDADaemonSession]
+ _OBJC_CLASS_$_DADaemonSession
+ ___45-[BTSDevicesController reinitDADaemonSession]_block_invoke
- -[BTSDevicesController handleDASessionEvent:]
- -[BTSDevicesController reinitDASession]
- _OBJC_CLASS_$_DASession
- ___39-[BTSDevicesController reinitDASession]_block_invoke
CStrings:
+ "DADaemonSession from BTSettings activated"
+ "Re-init DADaemonSession"
- "DASession from BTSettings activated"
- "Re-init DASession"
```
