## libchannel.dylib

> `/usr/lib/libchannel.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3184` | `0x3090` | **`-0xf4`** |
| `__TEXT.__gcc_except_tab` | `0x280` | `0x1e0` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x158` | `0xde` | **`-0x7a`** |
| `__TEXT.__unwind_info` | `0x270` | `0x248` | **`-0x28`** |

### Other Changes

```diff

-  Symbols:   267
-  CStrings:  19
+  Symbols:   261
+  CStrings:  16
Symbols:
- GCC_except_table1
- GCC_except_table12
- GCC_except_table15
- GCC_except_table16
- _realtime_runtime_check_pop_authorization
- _realtime_runtime_check_push_authorization
Functions:
~ __ZN9RTChannel5closeEv : 168 -> 108
~ __ZN7Channel26advance_commit_assert_headEv : 300 -> 348
~ __ZN7Channel10msg_notifyEv : 152 -> 84
~ __ZN7Channel8msg_waitEj : 172 -> 100
~ __ZN7Channel27poll_dead_name_notificationEv : 444 -> 184
~ __ZN7Channel27poll_dead_name_notificationEv.cold.1 : 4 -> 172
CStrings:
- "mach_msg with timeout=0 is RT safe"
- "mach_port_mod_refs is RT safe here"
- "os_crash is not realtime_safe, but crashing is okay"
```
