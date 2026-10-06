## KeyboardSettings

> `/System/Library/PreferenceBundles/KeyboardSettings.bundle/KeyboardSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e1a4` | `0x2e268` | **`+0xc4`** |
| `__TEXT.__cstring` | `0x2982` | `0x29b2` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x11c0` | `0x11e0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x8e8` | `0x8f8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-9127.1.6.0.0
+9127.1.7.2.101

-  Symbols:   631
-  CStrings:  2046
+  Symbols:   633
+  CStrings:  2047
Symbols:
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
Functions:
~ sub_2e394 : 220 -> 312
~ sub_2e470 -> sub_2e4cc : 592 -> 596
~ sub_2e6c0 -> sub_2e720 : 2288 -> 2388
CStrings:
+ "KeyboardSettings/KeyboardSettings.swift"
```
