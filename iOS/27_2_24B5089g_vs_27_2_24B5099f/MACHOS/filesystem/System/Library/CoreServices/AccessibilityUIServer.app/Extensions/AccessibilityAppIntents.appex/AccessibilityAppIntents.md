## AccessibilityAppIntents

> `/System/Library/CoreServices/AccessibilityUIServer.app/Extensions/AccessibilityAppIntents.appex/AccessibilityAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x73bc` | `0x7938` | **`+0x57c`** |
| `__TEXT.__auth_stubs` | `0xa90` | `0xb10` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x420` | `0x470` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x550` | `0x590` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x250` | `0x288` | **`+0x38`** |
| `__DATA_CONST.__got` | `0xf8` | `0x118` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x318` | `0x338` | **`+0x20`** |
| `__TEXT.__const` | `0xc22` | `0xc32` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x52c` | `0x53a` | **`+0xe`** |
| `__TEXT.__objc_methname` | `0x11b` | `0x128` | **`+0xd`** |
| `__DATA.__data` | `0x380` | `0x388` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x9` | `0xf` | **`+0x6`** |
| `__TEXT.__swift_as_cont` | `0x10` | `0x14` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x20` | `0x24` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-3245.8.2.0.0
+3245.8.4.2.0

-  Functions: 239
-  Symbols:   116
-  CStrings:  78
+  Functions: 247
+  Symbols:   123
+  CStrings:  79
Symbols:
+ __Block_copy
+ __Block_release
+ __NSConcreteStackBlock
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_deallocObject
+ _swift_retain_x2
CStrings:
+ "toggleAccessibilityShortcutOptionFromAppIntent:completion:"
+ "v8@?0"
- "toggleAccessibilityShortcutOption:fromSource:"
```
