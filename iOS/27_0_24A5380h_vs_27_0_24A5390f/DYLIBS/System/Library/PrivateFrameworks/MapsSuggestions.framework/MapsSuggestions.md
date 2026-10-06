## MapsSuggestions

> `/System/Library/PrivateFrameworks/MapsSuggestions.framework/MapsSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1940a0` | `0x193e64` | **`-0x23c`** |
| `__TEXT.__cstring` | `0x2c160` | `0x2c130` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x17c90` | `0x17c70` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x11640` | `0x11624` | **`-0x1c`** |
| `__TEXT.__oslogstring` | `0x1763f` | `0x1762f` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x6870` | `0x6860` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x97c` | `0x978` | **`-0x4`** |

### Other Changes

```diff

-2972.30.6.12.16
+2972.30.6.12.32

-  Functions: 6679
-  Symbols:   10177
-  CStrings:  5453
+  Functions: 6677
+  Symbols:   10175
+  CStrings:  5452
Symbols:
- _OBJC_IVAR_$_MapsSuggestionsXPCActivityTimer._taskCompleted
- ___67-[MapsSuggestionsXPCActivityTimer scheduleWithTimeInterval:leeway:]_block_invoke_2
CStrings:
+ "%@ did not have a current location to work with."
+ "23:33:39"
+ "Jul 13 2026"
+ "Task completed: %@ (expired: %@)"
- "00:25:40"
- "Jun 28 2026"
- "Task already completed (expiration handler won the race): %@"
- "Task completed successfully: %@"
- "com.apple.maps.suggestions.xpc-activity-expiration"
```
