## com.apple.driver.AudioDMAController-T8140

> `com.apple.driver.AudioDMAController-T8140`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x2ab30` | `0x2ab70` | **`+0x40`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-600.43.0.0.0
+600.44.0.0.0
Functions:
~ __ZN27AudioDMAChannelStateMachine23stateTransitionPreambleENS_21ADMACChannelOperationE : 568 -> 580
~ sub_fffffff009b42aa0 -> sub_fffffff009b4326c : 276 -> 288
~ __ZN18AudioDMAController9initForPMEP9IOService : 1640 -> 1644
~ sub_fffffff009b49a20 -> sub_fffffff009b4a1fc : 860 -> 880
~ __ZN18AudioDMAController10_gatePowerEmjb : 2360 -> 2376
CStrings:
+ "21:29:44"
+ "Jun 29 2026"
- "19:54:04"
- "Jun 18 2026"
```
