## JournalSettings

> `/System/Library/PreferenceBundles/JournalSettings.bundle/JournalSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b3fc` | `0x7b438` | **`+0x3c`** |
| `__TEXT.__const` | `0x4684` | `0x4664` | **`-0x20`** |
| `__DATA.__objc_data` | `0x6968` | `0x6980` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x2e6c` | `0x2e84` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x150a` | `0x151a` | **`+0x10`** |
| `__DATA.__common` | `0x460` | `0x458` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-109.0.0.0.0
+113.0.0.0.0
Functions:
~ sub_b270 : 572 -> 580
~ sub_b4ac -> sub_b4b4 : 212 -> 216
~ sub_11918 -> sub_11924 : 260 -> 272
~ sub_37db4 -> sub_37dcc : 76 -> 80
~ sub_520ec -> sub_52108 : 164 -> 168
~ sub_60310 -> sub_60330 : 420 -> 448
CStrings:
+ "pendingMarkupGeneration"
- "hasPendingMarkup"
```
