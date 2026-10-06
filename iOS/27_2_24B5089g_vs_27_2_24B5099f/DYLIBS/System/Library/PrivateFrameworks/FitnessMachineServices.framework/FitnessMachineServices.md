## FitnessMachineServices

> `/System/Library/PrivateFrameworks/FitnessMachineServices.framework/FitnessMachineServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53a60` | `0x53e94` | **`+0x434`** |
| `__TEXT.__oslogstring` | `0x1bb0` | `0x1cb0` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x1590` | `0x15a8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xe18` | `0xe28` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1650` | `0x1660` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2027.1.51.0.0
+2027.1.60.0.1

-  Functions: 2329
-  Symbols:   5594
-  CStrings:  337
+  Functions: 2331
+  Symbols:   5596
+  CStrings:  339
Symbols:
+ -[NLAPMachinePairingAlertUIController _hasOutstandingUserIntentRequest]
+ -[NLAPMachinePairingAlertViewController preferredVerticalBarBehavior]
+ GCC_except_table6
- GCC_except_table9
Functions:
+ -[NLAPMachinePairingAlertViewController preferredVerticalBarBehavior]
~ -[NLAPMachinePairingAlertUIController machinePairingAlertViewControllerDidDeactivate:] : 512 -> 1360
+ -[NLAPMachinePairingAlertUIController _hasOutstandingUserIntentRequest]
~ -[NLAPMachinePairingAlertController _resetAlerts] : 252 -> 276
CStrings:
+ "[FMAlerts] Reject machine connection because alert did deactivate before pairing completed, connectionState: %{public}@"
+ "[FMAlerts] Reject machine connection because alert did deactivate with an outstanding intent request, connectionState: %{public}@"
+ "settings-navigation://com.apple.Settings.Apps/com.apple.Fitness/gymkit-detection"
- "settings-navigation://com.apple.Settings.Apps/com.apple.Fitness/gymkit"
```
