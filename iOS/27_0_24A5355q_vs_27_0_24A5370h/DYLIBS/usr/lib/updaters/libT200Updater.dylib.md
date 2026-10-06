## libT200Updater.dylib

> `/usr/lib/updaters/libT200Updater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12708` | `0x12760` | **`+0x58`** |
| `__DATA_CONST.__const` | `0xee8` | `0xef8` | **`+0x10`** |
| `__TEXT.__const` | `0x1498` | `0x14a0` | **`+0x8`** |

### Other Changes

```diff

-1.0.0.8.94
+1.0.0.8.96

-  Symbols:   834
+  Symbols:   836
Symbols:
+ __oidSmtpUTF8Mailbox
+ _oidSmtpUTF8Mailbox
Functions:
~ _keyToString : 36 -> 40
~ _BC__selectGG : 128 -> 136
~ _Stop_smc_communication : 72 -> 100
~ _Enable_smc_communication : 76 -> 104
~ _T200UpdaterCreate : 1496 -> 1500
~ _T200UpdaterIsDone : 648 -> 652
~ _performVersionCheck : 920 -> 912
~ _T200GetBatteryModelIDs : 348 -> 372
~ __getInfoSMCIF : 2524 -> 2496
~ __performBatteryUpdateThread : 11696 -> 11708
~ __commitImageSMCIF : 1476 -> 1488
~ __T200PrintDigest : 212 -> 220
~ __send_bin_retry : 1732 -> 1728
~ _OUTLINED_FUNCTION_1 : 24 -> 32
~ _OUTLINED_FUNCTION_3 -> _OUTLINED_FUNCTION_2 : 32 -> 24
~ __performBatteryUpdateThread.cold.1 : 120 -> 112
~ __performBatteryUpdateThread.cold.90 : 120 -> 124
```
