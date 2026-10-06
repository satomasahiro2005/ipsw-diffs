## FedStatsEncoder

> `/System/Library/PrivateFrameworks/FedStatsEncoder.framework/FedStatsEncoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4035c` | `0x40bd4` | **`+0x878`** |
| `__TEXT.__oslogstring` | `0x1caf` | `0x1cff` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x85b` | `0x89f` | **`+0x44`** |
| `__TEXT.__eh_frame` | `0x22c0` | `0x22f8` | **`+0x38`** |
| `__TEXT.__const` | `0x1a40` | `0x1a70` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xb00` | `0xb18` | **`+0x18`** |
| `__DATA.__data` | `0x598` | `0x5a8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x66b` | `0x65b` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xd48` | `0xd58` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x968` | `0x970` | **`+0x8`** |

### Other Changes

```diff

-35.0.0.0.0
+38.0.0.0.0

-  Functions: 1007
-  Symbols:   527
-  CStrings:  177
+  Functions: 1011
+  Symbols:   528
+  CStrings:  179
Symbols:
+ _sqlite3_bind_text
CStrings:
+ "Cannot bind parameter at index %d: %s"
+ "Cannot prepare command: %s"
+ "SELECT %@ FROM '%@' WHERE %@ == ? ORDER BY RANDOM() LIMIT 1"
+ "SELECT COUNT(1) AS %@ FROM '%@' WHERE %@ == ?"
+ "SELECT COUNT(1) AS %@ FROM '%@' WHERE ? LIKE '%%' || \"%@\" || '%%'"
- "SELECT %@ FROM '%@' WHERE %@ == \"%@\" ORDER BY RANDOM() LIMIT 1"
- "SELECT COUNT(1) AS %@ FROM '%@' WHERE \"%@\" LIKE '%%' || \"%@\" || '%%'"
- "SELECT COUNT(1) AS %@ FROM '%@' WHERE %@ == \"%@\""
```
