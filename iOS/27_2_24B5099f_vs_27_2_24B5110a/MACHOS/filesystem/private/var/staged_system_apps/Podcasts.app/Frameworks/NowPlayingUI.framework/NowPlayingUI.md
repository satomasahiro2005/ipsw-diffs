## NowPlayingUI

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/NowPlayingUI.framework/NowPlayingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3440` | `0xd3b78` | **`+0x738`** |
| `__DATA.__data` | `0x7bc8` | `0x7cb8` | **`+0xf0`** |
| `__DATA_CONST.__got` | `0x1330` | `0x1398` | **`+0x68`** |
| `__TEXT.__cstring` | `0x1140` | `0x1190` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2b18` | `0x2b58` | **`+0x40`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4027.200.32.0.0
+4027.210.1.0.0

-  Functions: 3987
+  Functions: 4007

-  CStrings:  771
+  CStrings:  772
CStrings:
+ "Header of the queue section that lists the episodes that play after the queue"
+ "QUEUE_SECTION_TITLE_COMING_UP"
- "Continue Playing"
```
