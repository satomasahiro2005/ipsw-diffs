## com.apple.iokit.IOAccessoryManager

> `com.apple.iokit.IOAccessoryManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xe49e8` | `0xe4e84` | **`+0x49c`** |
| `__TEXT.__os_log` | `0x12066` | `0x121cf` | **`+0x169`** |
| `__DATA_CONST.__const` | `0x2ac50` | `0x2ac98` | **`+0x48`** |
| `__TEXT.__cstring` | `0x11056` | `0x11078` | **`+0x22`** |

### Other Changes

```diff

-1064.0.0.0.1
-  Functions: 5009
+1068.0.0.0.0
+  Functions: 5013

-  CStrings:  2956
+  CStrings:  2962
CStrings:
+ "%s::%s(): Setting forcePortWet... (target: %s, forcePortWet: %s)\n"
+ "%s::%s(): [%s%s%s] ForcePortWet override active — treating measurement as wet\n\n"
+ "%s::%s(): [%s%s%s] LDCM: Empty port, no charger present - setting mitigations to Triggered\n\n"
+ "%s::%s(): [%s%s%s] LDCM: Empty port, was Failed - resetting to Triggered to dismiss intrusive UI\n\n"
+ "%s::%s(): [%s%s%s] forcePortWet: %s\n\n"
+ "1211111212221212111111211112112212122222222122121212"
+ "_setForcePortWet"
+ "setForcePortWet"
- "%s::%s(): [%s%s%s] Empty port, was Failed - resetting to Triggered to dismiss intrusive UI\n\n"
- "121111121222121211111121111211221212222222212212121"
```
