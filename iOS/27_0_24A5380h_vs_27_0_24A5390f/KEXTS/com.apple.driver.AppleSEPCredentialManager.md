## com.apple.driver.AppleSEPCredentialManager

> `com.apple.driver.AppleSEPCredentialManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x4dcf4` | `0x4e214` | **`+0x520`** |
| `__TEXT.__cstring` | `0x1312c` | `0x13342` | **`+0x216`** |
| `__TEXT.__const` | `0x420` | `0x428` | **`+0x8`** |

### Other Changes

```diff

-949.0.9.0.0
-  Functions: 1016
+949.0.13.0.0
+  Functions: 1019

-  CStrings:  1971
+  CStrings:  1981
CStrings:
+ "%s: %s: *** GOING OFFLINE *** ---> aborting SEP command=%u (isPoweringOff=%s, isSystemShuttingDown=%s).\n"
+ "%s: %s: marked system shutting down, stateFlags=0x%x.\n"
+ "%s: %s: newState=%u (prev=%u), stateFlags=0x%x.\n"
+ "%s: %s: prepared for system shutdown.\n"
+ "%s: %s: preparing for system shutdown.\n"
+ "%s: %s: timed out waiting for %s (timeoutMs=%llu).\n"
+ "%s: %s: timed out waiting for AppleSEPManager (timeoutMs=%llu).\n"
+ "%s: %s: wait canceled, system is shutting down (cmd=%u).\n"
+ "%s: %s: waiting (cmd=%u).\n"
+ "121111121222121212111111111111112121122211122212211"
+ "21:20:00"
+ "Jul 14 2026"
+ "markSystemIsShuttingDownGated"
+ "newState"
+ "sigSize > 0 && sigSize <= kACMCredentialDataSignatureMaxSize"
+ "systemWillShutdown"
+ "waitForSEPEndpoint"
- "%s: %s: called, currentState=%u -> newState=%u.\n"
- "%s: %s: waiting cmd=%u.\n"
- "12111112122212121211111111111111212112211122212211"
- "20:59:31"
- "Jun 30 2026"
- "newstate"
- "sepEndpoint"
```
