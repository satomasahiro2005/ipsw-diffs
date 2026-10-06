## JournalNotifications

> `/System/Library/PreferenceBundles/JournalNotifications.bundle/JournalNotifications`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa8bbc` | `0xa9074` | **`+0x4b8`** |
| `__TEXT.__oslogstring` | `0x11d9` | `0x1209` | **`+0x30`** |
| `__DATA.__objc_const` | `0x3338` | `0x3358` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x3bf0` | `0x3c10` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2ce0` | `0x2cc0` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1adf` | `0x1aff` | **`+0x20`** |
| `__DATA.__objc_data` | `0x6ec8` | `0x6ee0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x1e00` | `0x1e10` | **`+0x10`** |
| `__TEXT.__const` | `0x6cc4` | `0x6cd4` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x3720` | `0x3730` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x30b6` | `0x30c6` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2270` | `0x227c` | **`+0xc`** |
| `__DATA.__common` | `0x498` | `0x4a0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xdb8` | `0xdb0` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xf38` | `0xf30` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1350` | `0x1358` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x3086` | `0x307e` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-84.0.0.0.0
+89.0.0.0.0

-  CStrings:  1022
+  CStrings:  1023
CStrings:
+ "Found an unhandled text attachment: %s"
+ "hasPendingMarkup"
- "textAttachment"
```
