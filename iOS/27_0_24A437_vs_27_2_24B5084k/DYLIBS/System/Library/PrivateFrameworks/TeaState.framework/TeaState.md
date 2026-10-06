## TeaState

> `/System/Library/PrivateFrameworks/TeaState.framework/TeaState`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x857bc` | `0x85b9c` | **`+0x3e0`** |
| `__TEXT.__eh_frame` | `0x3fa0` | `0x41e0` | **`+0x240`** |
| `__TEXT.__oslogstring` | `0x102e` | `0x10ae` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1e30` | `0x1ea0` | **`+0x70`** |
| `__TEXT.__const` | `0x4d0c` | `0x4cfc` | **`-0x10`** |

### Other Changes

```diff

-1478.1.0.0.0
+1510.0.0.0.0

-  Functions: 2358
+  Functions: 2367

-  CStrings:  89
+  CStrings:  91
CStrings:
+ "Handled event (main actor, async dispatch). Node=%s, Event=%s, Changed=%{bool}d"
+ "Invoked command (async). Node=%s, Command=%s"
```
