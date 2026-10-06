## PowerUI

> `/System/Library/PrivateFrameworks/PowerUI.framework/PowerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd9e98` | `0xd9ef8` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xf137` | `0xf16f` | **`+0x38`** |

### Other Changes

```diff

-753.0.17.0.0
+753.40.6.0.0

-  CStrings:  3213
+  CStrings:  3214
Symbols:
+ -[PowerUISmartChargeManager loadDefaultsIsInitialLoad:]
- -[PowerUISmartChargeManager loadDefaults]
Functions:
~ +[PowerUISmartChargeUtilities totalPluginDurationAfter:withMinimumDuration:withPluginEvents:] : 364 -> 360
~ -[PowerUISmartChargeManager initWithDefaultsDomain:contextStore:beforeHandlingBatteryChangeCallback:afterHandlingBatteryChangeCallback:] : 6668 -> 6672
~ ___136-[PowerUISmartChargeManager initWithDefaultsDomain:contextStore:beforeHandlingBatteryChangeCallback:afterHandlingBatteryChangeCallback:]_block_invoke_2.1120 -> ___136-[PowerUISmartChargeManager initWithDefaultsDomain:contextStore:beforeHandlingBatteryChangeCallback:afterHandlingBatteryChangeCallback:]_block_invoke_2.754 : 60 -> 132
~ -[PowerUISmartChargeManager loadDefaults] -> -[PowerUISmartChargeManager loadDefaultsIsInitialLoad:] : 2688 -> 2712
CStrings:
+ "Reloading defaults due to defaults-changed notification"
```
