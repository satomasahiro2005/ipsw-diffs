## nsurlsessiond

> `/usr/libexec/nsurlsessiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xf81a` | `0xf76e` | **`-0xac`** |
| `__DATA_CONST.__got` | `0x720` | `0x7a0` | **`+0x80`** |
| `__DATA.__objc_const` | `0x8e78` | `0x8e38` | **`-0x40`** |
| `__TEXT.__text` | `0x82e54` | `0x82e20` | **`-0x34`** |
| `__TEXT.__objc_methname` | `0xf185` | `0xf154` | **`-0x31`** |
| `__TEXT.__gcc_except_tab` | `0xe5d4` | `0xe5b0` | **`-0x24`** |
| `__TEXT.__auth_stubs` | `0x11b0` | `0x11d0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x8f0` | `0x900` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x700` | `0x6f8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3888.100.1.0.0
+3890.100.1.0.0

-  Symbols:   514
-  CStrings:  3856
+  Symbols:   516
+  CStrings:  3852
Symbols:
+ _sqlite3_clear_bindings
+ _sqlite3_free
CStrings:
+ "Failed to delete expired entries from session_tasks table of DB: %s"
+ "Failed to delete expired entries from sessions table of DB: %s"
- "Failed to delete expired entries from session_tasks table of DB. Error= %s"
- "Failed to delete expired entries from sessions table of DB. Error= %s"
- "Failed to init the _deleteEntriesStmt statement for session_tasks. Error = %s"
- "Failed to init the _deleteSessionEntriesStmt statement for sessions. Error = %s"
- "_deleteSessionEntriesStmt"
- "_deleteTaskEntriesStmt"
```
