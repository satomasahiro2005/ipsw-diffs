## SpotlightReceiver

> `/System/Library/PrivateFrameworks/SpotlightReceiver.framework/SpotlightReceiver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb7e4` | `0xb7d0` | **`-0x14`** |

### Other Changes

```diff

-2444.104.0.0.0
+2448.100.0.0.0
Functions:
~ __SpotlightDaemonClientHandleCommand : 3732 -> 3728
~ -[CSReceiverConnection initWithScheduledReceiver:forServiceName:] : 884 -> 880
~ -[CSReceiverConnection handleSetup:] : 2320 -> 2316
~ ___136-[CSReceiverConnection indexWithFd:offset:size:donation:additionalAttributes:config:updateDestination:skipIndexCheck:completionHandler:]_block_invoke_2 : 3684 -> 3672
~ ___136-[CSReceiverConnection indexWithFd:offset:size:donation:additionalAttributes:config:updateDestination:skipIndexCheck:completionHandler:]_block_invoke.487 : 1320 -> 1316
~ ___79-[CSReceiverConnection indexWithCascadeData:donation:config:completionHandler:]_block_invoke : 1624 -> 1620
~ ___79-[CSReceiverConnection indexWithCascadeData:donation:config:completionHandler:]_block_invoke.506 : 1036 -> 1032
~ _SpotlightScheduledReceiverRegisterConfigs : 276 -> 272
~ -[SpotlightReceiverResponse(Internal) enumerateUpdatesUsingBlock:] : 1076 -> 1096
```
