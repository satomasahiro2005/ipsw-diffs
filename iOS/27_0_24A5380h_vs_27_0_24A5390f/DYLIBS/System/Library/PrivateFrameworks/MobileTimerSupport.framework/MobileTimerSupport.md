## MobileTimerSupport

> `/System/Library/PrivateFrameworks/MobileTimerSupport.framework/MobileTimerSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd7784` | `0xd9a4c` | **`+0x22c8`** |
| `__TEXT.__oslogstring` | `0xae1` | `0xe33` | **`+0x352`** |
| `__TEXT.__cstring` | `0x32ab` | `0x315b` | **`-0x150`** |
| `__TEXT.__eh_frame` | `0x5a24` | `0x5ab4` | **`+0x90`** |
| `__DATA_DIRTY.__data` | `0x2258` | `0x2298` | **`+0x40`** |
| `__TEXT.__const` | `0x9dd8` | `0x9e18` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x2062` | `0x20a2` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3698` | `0x36c0` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x6550` | `0x6570` | **`+0x20`** |
| `__DATA.__data` | `0x2208` | `0x2228` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x3b08` | `0x3b28` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x22d4` | `0x22ec` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x5d0` | `0x5c4` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x15f0` | `0x15f8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x930` | `0x938` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x318` | `0x320` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1f8` | `0x200` | **`+0x8`** |

### Other Changes

```diff

-2329.0.0.0.0
+2330.0.0.0.0

-  Functions: 4890
+  Functions: 4906

-  CStrings:  423
+  CStrings:  433
CStrings:
+ "%@ clearig out old stopwatch session %s)"
+ "%@ got active stopwatches %s)"
+ "%@ got restored stopwatch sessions %s)"
+ "Does not support multiple stopwatches, aborting update of stopwatch: %@"
+ "No changes after removal of extra stopwatches"
+ "No multiple stopwatches found during migration, returning"
+ "Removing extra stopwatches during migration"
+ "Returning active stopwatch during migration: %@"
+ "Returning non active stopwatch during migration"
+ "Stopwatches changed after removal of extras, persisting"
+ "Storage version: %f, current version: %f"
+ "actor: returning stopwatches %s"
+ "added default stopwatch, now %s"
+ "error restoring stopwatches %@"
+ "restored stopwatches %s"
+ "saving stopwatches to store"
+ "setting stopwatches %s"
- " clearig out old stopwatch session "
- " got active stopwatches "
- " got restored stopwatch sessions "
- "actor: returning stopwatches "
- "added default stopwatch, now "
- "error restoring stopwatches "
- "restored stopwatches "
```
