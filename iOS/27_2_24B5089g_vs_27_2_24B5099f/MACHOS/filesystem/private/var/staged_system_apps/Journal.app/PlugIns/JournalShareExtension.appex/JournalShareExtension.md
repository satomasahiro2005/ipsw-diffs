## JournalShareExtension

> `/private/var/staged_system_apps/Journal.app/PlugIns/JournalShareExtension.appex/JournalShareExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x65e4` | `0x65c4` | **`-0x20`** |
| `__DATA.__objc_data` | `0x7bd8` | `0x7bf0` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x3da4` | `0x3dbc` | **`+0x18`** |
| `__TEXT.__text` | `0xfd410` | `0xfd428` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x1a41` | `0x1a51` | **`+0x10`** |
| `__DATA.__common` | `0x648` | `0x640` | **`-0x8`** |
| `__DATA.__data` | `0x5e10` | `0x5e18` | **`+0x8`** |

### Same-size Content Changes

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
~ sub_10004d9b4 : 420 -> 448
~ sub_10004ea98 -> sub_10004eab4 : 1452 -> 1444
~ sub_10007c14c -> sub_10007c160 : 164 -> 168
~ sub_1000f0340 -> sub_1000f0358 : 1328 -> 1324
~ sub_1000f9394 -> sub_1000f93a8 : 76 -> 80
CStrings:
+ "pendingMarkupGeneration"
- "hasPendingMarkup"
```
