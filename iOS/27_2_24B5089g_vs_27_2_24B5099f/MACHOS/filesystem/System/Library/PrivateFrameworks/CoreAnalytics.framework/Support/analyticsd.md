## analyticsd

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1442a8` | `0x144f18` | **`+0xc70`** |
| `__TEXT.__gcc_except_tab` | `0x17794` | `0x178b8` | **`+0x124`** |
| `__TEXT.__cstring` | `0x16215` | `0x162b5` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x1af99` | `0x1b039` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x8608` | `0x8650` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x398` | `0x3d8` | **`+0x40`** |
| `__DATA_CONST.__const` | `0xadc8` | `0xade8` | **`+0x20`** |
| `__TEXT.__const` | `0xa464` | `0xa474` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-577.40.5.0.0
+577.40.7.0.0

-  Functions: 6410
+  Functions: 6418

-  CStrings:  4139
+  CStrings:  4141
Symbols:
+ _swift_release_x19
- _swift_release_x20
CStrings:
+ "SELECT session_id FROM sessions WHERE cadence = ?1 AND start <= ?2 UNION SELECT DISTINCT tm.session_id FROM transform_metadata tm LEFT JOIN sessions s ON tm.session_id = s.session_id WHERE s.session_id IS NULL AND tm.session_id IS NOT NULL"
+ "SessionNotAcceptingEvents"
+ "[FW Event] ERROR: Event '%s' dropped: session '%{public}s' does not exist or has ended."
+ "[SessionManager] Failed to re-create session row for leftover state: %s"
+ "[Sink] No session row for %{public}s; stamping log with the cadence log start instead"
- "SELECT session_id FROM sessions WHERE state = ?1 AND cadence = ?2 AND start <= ?3"
- "[Transform Manager] Session %s not enabled for transform, using main session"
- "sessionsEnabled"
```
