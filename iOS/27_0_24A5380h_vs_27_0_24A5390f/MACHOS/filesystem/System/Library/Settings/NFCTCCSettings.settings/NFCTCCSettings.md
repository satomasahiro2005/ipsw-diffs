## NFCTCCSettings

> `/System/Library/Settings/NFCTCCSettings.settings/NFCTCCSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8cac` | `0x8b7c` | **`-0x130`** |
| `__TEXT.__auth_stubs` | `0xad0` | `0xae0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x570` | `0x578` | **`+0x8`** |

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
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-70.35.1.0.0
+70.37.0.0.0

-  Symbols:   142
+  Symbols:   143
Symbols:
+ _objc_retain_x21
+ _tcc_authorization_record_create_with_subject
+ _tcc_authorization_set_authorization_with_authorization_record
- _objc_release_x28
- _tcc_server_message_set_authorization_value
Functions:
~ sub_94e8 : 660 -> 356
```
