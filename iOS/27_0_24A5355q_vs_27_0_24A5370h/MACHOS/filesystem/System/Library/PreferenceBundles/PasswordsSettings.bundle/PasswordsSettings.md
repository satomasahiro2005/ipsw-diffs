## PasswordsSettings

> `/System/Library/PreferenceBundles/PasswordsSettings.bundle/PasswordsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x124fc` | `0x123d8` | **`-0x124`** |
| `__TEXT.__cstring` | `0xde6` | `0xdc6` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x380` | `0x378` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-7625.1.18.10.4
+7625.1.20.10.3

-  Symbols:   187
-  CStrings:  252
+  Symbols:   186
+  CStrings:  251
Symbols:
+ _swift_release_x24
+ _swift_release_x25
- _swift_release_x22
- _swift_release_x27
- _swift_release_x28
Functions:
~ sub_2b94 : 504 -> 512
~ sub_34cc -> sub_34d4 : 268 -> 280
~ sub_74cc -> sub_74e0 : 256 -> 264
~ sub_7eb4 -> sub_7ed0 : 256 -> 276
~ sub_8384 -> sub_83b4 : 2400 -> 2060
CStrings:
- "Passwords (app name)"
```
