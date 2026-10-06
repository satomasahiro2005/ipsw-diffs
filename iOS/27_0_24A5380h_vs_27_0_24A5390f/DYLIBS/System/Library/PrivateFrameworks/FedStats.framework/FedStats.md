## FedStats

> `/System/Library/PrivateFrameworks/FedStats.framework/FedStats`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x179e0` | `0x17ec8` | **`+0x4e8`** |
| `__AUTH_CONST.__cfstring` | `0x2dc0` | `0x2e40` | **`+0x80`** |
| `__TEXT.__cstring` | `0x307f` | `0x30e9` | **`+0x6a`** |
| `__TEXT.__objc_methlist` | `0x177c` | `0x1794` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xc98` | `0xca8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x460` | `0x470` | **`+0x10`** |

### Other Changes

```diff

-83.0.0.0.0
+84.0.0.0.0

-  Functions: 434
-  Symbols:   1087
-  CStrings:  404
+  Functions: 437
+  Symbols:   1092
+  CStrings:  408
Symbols:
+ -[FedStatsSQLiteDatabase execute:withParameters:error:]
+ -[FedStatsSQLiteDatabase runQuery:withParameters:error:]
+ _bindTextParameters
+ _sqlite3_bind_text
+ _sqlite3_free
CStrings:
+ "?"
+ "Cannot bind query parameter: %s"
+ "Cannot prepare command: %s"
+ "INSERT INTO '%@' VALUES (%lu, ?)"
+ "Query parameters must be strings"
+ "SELECT %@ FROM '%@' WHERE %@ == ? ORDER BY RANDOM() LIMIT 1"
+ "SELECT COUNT(1) AS %@ FROM '%@' WHERE %@ == ?"
+ "SELECT COUNT(1) AS %@ FROM '%@' WHERE ? LIKE '%%' || %@ || '%%'"
+ "`command` should be a string"
- "\"%@\""
- "INSERT INTO '%@' VALUES (%lu, \"%@\")"
- "SELECT %@ FROM '%@' WHERE %@ == \"%@\" ORDER BY RANDOM() LIMIT 1"
- "SELECT COUNT(1) AS %@ FROM '%@' WHERE %@ == \"%@\""
- "SELECT COUNT(1) AS %@ FROM '%@' WHERE '%@' LIKE '%%' || %@ || '%%'"
```
