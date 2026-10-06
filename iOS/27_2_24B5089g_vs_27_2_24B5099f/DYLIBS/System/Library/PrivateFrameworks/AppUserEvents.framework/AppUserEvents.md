## AppUserEvents

> `/System/Library/PrivateFrameworks/AppUserEvents.framework/AppUserEvents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x388d0` | `0x39d58` | **`+0x1488`** |
| `__DATA_DIRTY.__data` | `—` | `0x710` | **`+0x710`** |
| `__DATA.__data` | `0x1720` | `0x1168` | **`-0x5b8`** |
| `__DATA.__bss` | `0x3a10` | `0x3810` | **`-0x200`** |
| `__DATA_DIRTY.__bss` | `—` | `0x200` | **`+0x200`** |
| `__TEXT.__cstring` | `0xb3a` | `0xc4a` | **`+0x110`** |
| `__TEXT.__eh_frame` | `0x2558` | `0x2650` | **`+0xf8`** |
| `__AUTH.__data` | `0x6c8` | `0x610` | **`-0xb8`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1060` | `0x1018` | **`-0x48`** |
| `__DATA.__common` | `0x48` | `0x30` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x944` | `0x954` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x175c` | `0x1768` | **`+0xc`** |
| `__TEXT.__swift5_fieldmd` | `0xeec` | `0xef8` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xcc0` | `0xcc8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x30` | `0x28` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x1013` | `0x1019` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x11c` | `0x120` | **`+0x4`** |

### Other Changes

```diff

-11.0.0.0.0
+12.0.0.0.0

-  Functions: 1299
-  Symbols:   593
-  CStrings:  83
+  Functions: 1310
+  Symbols:   594
+  CStrings:  87
Symbols:
+ _objc_release_x26
+ _symbolic ySS______SayxGtYbc 10Foundation4DateV
- _symbolic ySS_SayxGtYbc
CStrings:
+ "CREATE TABLE IF NOT EXISTS sessions (\n    id INTEGER PRIMARY KEY,\n    session_id TEXT UNIQUE NOT NULL,\n    end_date INTEGER NOT NULL\n);\nCREATE TABLE IF NOT EXISTS events (\n    session_row_id INTEGER NOT NULL REFERENCES sessions(id) ON DELETE CASCADE,\n    event_index INTEGER NOT NULL,\n    PRIMARY KEY (session_row_id, event_index)\n);\nCREATE TABLE IF NOT EXISTS session_index_coverage (\n    session_id TEXT NOT NULL REFERENCES sessions(session_id) ON DELETE CASCADE,\n    field_name TEXT NOT NULL,\n    PRIMARY KEY (session_id, field_name)\n);\nCREATE INDEX IF NOT EXISTS idx_coverage_field ON session_index_coverage(field_name, session_id);"
+ "DROP TABLE IF EXISTS session_index_coverage;\nDROP TABLE IF EXISTS events;\nDROP TABLE IF EXISTS sessions;"
+ "INSERT OR IGNORE INTO sessions (id, session_id, end_date) VALUES (?, ?, ?) RETURNING id;"
+ "PRAGMA user_version = "
+ "PRAGMA user_version;"
+ "SELECT MAX(id) FROM sessions WHERE id >= ? AND id <= ?;"
- "CREATE TABLE IF NOT EXISTS sessions (\n    id INTEGER PRIMARY KEY AUTOINCREMENT,\n    session_id TEXT UNIQUE NOT NULL\n);\nCREATE TABLE IF NOT EXISTS events (\n    session_row_id INTEGER NOT NULL REFERENCES sessions(id) ON DELETE CASCADE,\n    event_index INTEGER NOT NULL,\n    PRIMARY KEY (session_row_id, event_index)\n);\nCREATE TABLE IF NOT EXISTS session_index_coverage (\n    session_id TEXT NOT NULL REFERENCES sessions(session_id) ON DELETE CASCADE,\n    field_name TEXT NOT NULL,\n    PRIMARY KEY (session_id, field_name)\n);\nCREATE INDEX IF NOT EXISTS idx_coverage_field ON session_index_coverage(field_name, session_id);"
- "INSERT OR IGNORE INTO sessions (session_id) VALUES (?) RETURNING id;"
```
