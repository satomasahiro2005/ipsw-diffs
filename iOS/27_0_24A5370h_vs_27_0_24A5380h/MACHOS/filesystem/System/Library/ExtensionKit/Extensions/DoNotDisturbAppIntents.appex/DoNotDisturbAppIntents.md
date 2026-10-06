## DoNotDisturbAppIntents

> `/System/Library/ExtensionKit/Extensions/DoNotDisturbAppIntents.appex/DoNotDisturbAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb5c8` | `0xc048` | **`+0xa80`** |
| `__TEXT.__cstring` | `0x5c8` | `0x778` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `0x6e8` | `0x778` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0xa90` | `0xab0` | **`+0x20`** |
| `__TEXT.__const` | `0xbb8` | `0xbd8` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x3b1` | `0x3c9` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x388` | `0x3a0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x550` | `0x560` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x118` | `0x128` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xd0` | `0xdc` | **`+0xc`** |
| `__DATA.__data` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x44` | `0x4c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x48` | `0x4c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x4c` | `0x50` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-502.0.100.0.0
+506.0.0.0.0

-  Functions: 228
-  Symbols:   109
-  CStrings:  52
+  Functions: 232
+  Symbols:   111
+  CStrings:  63
Symbols:
+ _swift_deallocClassInstance
+ _swift_setDeallocating
CStrings:
+ "A synonym used to match Focus Status in Settings search."
+ "A synonym used to match Focus in Settings search."
+ "FOCUS_STATUS_SYNONYM_AWAY_STATUS"
+ "FOCUS_SYNONYM_APP_FILTER"
+ "FOCUS_SYNONYM_AUTO_REPLY"
+ "FOCUS_SYNONYM_AWAY"
+ "FOCUS_SYNONYM_DND"
+ "FOCUS_SYNONYM_DO_NOT_DISTURB"
+ "FOCUS_SYNONYM_FOCUS_FILTER"
+ "FOCUS_SYNONYM_SILENCE"
+ "FOCUS_SYNONYM_TIME_SENSITIVE"
```
