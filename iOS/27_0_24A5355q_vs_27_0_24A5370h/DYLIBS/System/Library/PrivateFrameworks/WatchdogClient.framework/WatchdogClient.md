## WatchdogClient

> `/System/Library/PrivateFrameworks/WatchdogClient.framework/WatchdogClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1350` | `0x13a8` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0xa0` | `0xa8` | **`+0x8`** |

### Other Changes

```diff

-333.0.0.0.0
+334.0.1.0.0
Functions:
~ __WDOGClient_PollIsAlive : 1300 -> 1328
~ _wd_kickoff_ping : 596 -> 604
~ ___wd_kickoff_ping_block_invoke : 72 -> 76
~ ___wd_kickoff_ping_block_invoke_2 : 76 -> 80
~ _wd_endpoint_begin_watchdog_monitoring_for_service : 316 -> 336
~ _wd_endpoint_disable_monitoring_for_service : 212 -> 232
~ ___wd_kickoff_ping_block_invoke_3 : 76 -> 80
```
