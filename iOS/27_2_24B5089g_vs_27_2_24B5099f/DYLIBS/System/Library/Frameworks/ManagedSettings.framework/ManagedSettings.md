## ManagedSettings

> `/System/Library/Frameworks/ManagedSettings.framework/ManagedSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc0600` | `0xc0b2c` | **`+0x52c`** |
| `__DATA_DIRTY.__data` | `0x6cb0` | `0x6d60` | **`+0xb0`** |
| `__DATA.__data` | `0xd88` | `0xcf0` | **`-0x98`** |
| `__DATA.__bss` | `0x8e30` | `0x8db0` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x2b80` | `0x2c00` | **`+0x80`** |
| `__TEXT.__cstring` | `0x25c2` | `0x25e2` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2b50` | `0x2b70` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0xb48` | `0xb60` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xac8` | `0xad8` | **`+0x10`** |

### Other Changes

```diff

-318.0.0.0.0
+319.40.1.0.0

-  Functions: 5003
+  Functions: 5013

-  CStrings:  405
+  CStrings:  406
CStrings:
+ "enableTelemetry=YES"
```
