## AppState

> `/System/Library/PrivateFrameworks/AppState.framework/AppState`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x469c4` | `0x465b4` | **`-0x410`** |
| `__TEXT.__constg_swiftt` | `0xeb0` | `0xef4` | **`+0x44`** |
| `__AUTH_CONST.__const` | `0x21f8` | `0x2220` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x26d8` | `0x2700` | **`+0x28`** |
| `__TEXT.__const` | `0x2dcc` | `0x2dec` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x1070` | `0x1084` | **`+0x14`** |
| `__DATA.__data` | `0x328` | `0x338` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x1300` | `0x12f0` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0xad7` | `0xac7` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1320` | `0x1330` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa50` | `0xa48` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x398` | `0x390` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x1d0` | `0x1c8` | **`-0x8`** |
| `__TEXT.__swift5_fieldmd` | `0xdd8` | `0xddc` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x1b4` | `0x1b8` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x44` | `0x48` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-4.0.8.0.0
+4.0.9.0.0

-  Functions: 1541
-  Symbols:   685
+  Functions: 1539
+  Symbols:   687
Symbols:
+ _symbolic $s8AppState0A8QueryingP
+ _symbolic _____ s12StaticStringV
+ _symbolic ______p 8AppState0A8QueryingP
- _symbolic So11ASDAppQueryC
CStrings:
+ "fetchQuery(_:signpostName:)"
- "ASDAppQuery(custom).execute"
```
