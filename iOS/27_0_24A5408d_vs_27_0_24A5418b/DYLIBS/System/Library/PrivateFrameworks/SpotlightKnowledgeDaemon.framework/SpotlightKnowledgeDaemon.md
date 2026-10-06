## SpotlightKnowledgeDaemon

> `/System/Library/PrivateFrameworks/SpotlightKnowledgeDaemon.framework/SpotlightKnowledgeDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48acd0` | `0x48c2cc` | **`+0x15fc`** |
| `__TEXT.__oslogstring` | `0x116be` | `0x1186e` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `0x145a8` | `0x14680` | **`+0xd8`** |
| `__TEXT.__cstring` | `0x15963` | `0x159f3` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0xc858` | `0xc880` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x87ed` | `0x880d` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x18b30` | `0x18b40` | **`+0x10`** |
| `__DATA.__data` | `0x3a60` | `0x3a70` | **`+0x10`** |
| `__TEXT.__const` | `0x17408` | `0x17418` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x8d40` | `0x8d4c` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0xe9a8` | `0xe9b2` | **`+0xa`** |
| `__AUTH_CONST.__auth_got` | `0x36e8` | `0x36f0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x8dc0` | `0x8dc8` | **`+0x8`** |

### Other Changes

```diff

-2459.102.0.0.0
+2459.105.0.0.0

-  Functions: 16549
-  Symbols:   11663
-  CStrings:  3672
+  Functions: 16556
+  Symbols:   11664
+  CStrings:  3680
Symbols:
+ ___swift_memcpy392_8
+ _symbolic _____ySSG s10ArraySliceV
- ___swift_memcpy384_8
CStrings:
+ "PRAGMA integrity_check("
+ "Running one-time StateStore integrity check (recorded version %{public}ld, current %{public}ld)..."
+ "SQLite Database Integrity Check Marker Path is Illegal: "
+ "StateStore WAL %{public}s exceeds recovery threshold %{public}s; deleting database, WAL and SHM before open"
+ "StateStore integrity check FAILED with %{public}ld problem(s); deleting database and exiting. First problems: %{public}s"
+ "StateStore integrity check could not run: %@"
+ "StateStore integrity check failed: "
+ "StateStore integrity check passed; recording version %{public}ld"
+ "StateStore integrity-check marker write failed: %@"
- "StateStore WAL %{public}s exceeds recovery threshold %{public}s; deleting WAL and SHM before open"
```
