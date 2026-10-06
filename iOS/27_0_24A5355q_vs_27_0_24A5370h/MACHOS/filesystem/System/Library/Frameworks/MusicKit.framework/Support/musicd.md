## musicd

> `/System/Library/Frameworks/MusicKit.framework/Support/musicd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26d60` | `0x2737c` | **`+0x61c`** |
| `__TEXT.__eh_frame` | `0x2180` | `0x2290` | **`+0x110`** |
| `__TEXT.__auth_stubs` | `0x1470` | `0x14c0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x520` | `0x560` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0xa40` | `0xa68` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xa28` | `0xa48` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x188` | `0x18c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.100.68.0.0
+4026.110.78.1.0

-  Functions: 895
-  Symbols:   574
-  CStrings:  193
+  Functions: 902
+  Symbols:   579
+  CStrings:  194
Symbols:
+ _objc_release_x26
+ _swift_retain_x25
+ _swift_task_deinitOnExecutor
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
CStrings:
+ "musicd/MusicLibraryAndAccountRelatedUpdates.swift"
```
