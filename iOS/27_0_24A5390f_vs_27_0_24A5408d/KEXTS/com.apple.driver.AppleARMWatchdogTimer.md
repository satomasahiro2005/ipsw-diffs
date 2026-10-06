## com.apple.driver.AppleARMWatchdogTimer

> `com.apple.driver.AppleARMWatchdogTimer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x5378` | `0x5434` | **`+0xbc`** |
| `__TEXT.__cstring` | `0x135a` | `0x13ff` | **`+0xa5`** |

### Other Changes

```diff

-334.0.3.0.0
-  Functions: 188
+334.0.4.0.0
+  Functions: 189

-  CStrings:  126
+  CStrings:  128
Functions:
~ __ZN21AppleARMWatchdogTimer5startEP9IOService : 4224 -> 4260
~ __ZN21AppleARMWatchdogTimer20_handlePEHaltRestartEj : 668 -> 768
~ __ZN10IOWatchdog5startEP9IOServiceyy : 1164 -> 1200
+ sub_fffffff00862a930
CStrings:
+ "AppleARMWatchdogTimer::start: _wdtBaseAddress: %#lx _wdtResetCount=%#x _SMCWatchdogAvailable=%d\n"
+ "wdog: Nested panic detected: APWD promotion disabled, system will reset shortly...\n"
+ "wdog: Nested panic detected: attempting to promote this panic to an APWD report...\n"
+ "wdog: panic chipreset\n"
+ "wdog: restart\n"
- "AppleARMWatchdogTimer::start: _wdtBaseAddress: %#lx _wdtResetCount=%#x _useSMCEnforcedWatchdog=%d\n"
- "wdog panic (attempt %d)\n"
- "wdog restart\n"
```
