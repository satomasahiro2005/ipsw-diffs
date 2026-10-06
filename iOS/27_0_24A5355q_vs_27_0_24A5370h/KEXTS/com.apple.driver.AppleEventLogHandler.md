## com.apple.driver.AppleEventLogHandler

> `com.apple.driver.AppleEventLogHandler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x100` | **`+0x100`** |
| `__TEXT_EXEC.__text` | `0x1488` | `0x14b8` | **`+0x30`** |

### Other Changes

```diff

-1966.0.0.0.0
+1976.0.0.0.0
Functions:
~ _OUTLINED_FUNCTION_0 : 1552 -> 1540
~ __ZN20AppleEventLogHandler28_eventLogPanicTimeoutHandlerEP18IOTimerEventSource : 160 -> 180
~ _OUTLINED_FUNCTION_1 : 96 -> 100
~ __ZN20AppleEventLogHandler16_readEventLogRegEtj : 96 -> 100
~ sub_fffffff008bbcf98 -> sub_fffffff008bdb938 : 76 -> 80
~ __ZN20AppleEventLogHandler24_handleEventLogInterruptEtb : 760 -> 804
~ __ZN20AppleEventLogHandler27_handleEventLogInterruptAllEib : 260 -> 244
```
