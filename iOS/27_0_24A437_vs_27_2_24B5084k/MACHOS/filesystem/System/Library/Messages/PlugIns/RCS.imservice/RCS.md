## RCS

> `/System/Library/Messages/PlugIns/RCS.imservice/RCS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1119e8` | `0x111a48` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x6163` | `0x61b3` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x5980` | `0x59a0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1fe0` | `0x1fd0` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1958` | `0x1960` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xff8` | `0xff0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x3c28` | `0x3c30` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Symbols:   493
-  CStrings:  1693
+  Symbols:   492
+  CStrings:  1694
Symbols:
- _IMDCreateIMMessageItemFromIMDMessageRecordRef
Functions:
~ sub_746f4 : 568 -> 572
~ sub_7cae4 -> sub_7cae8 : 672 -> 708
~ sub_c2234 -> sub_c225c : 120 -> 124
~ sub_c62cc -> sub_c62f8 : 272 -> 324
CStrings:
+ "createIMMessageItemFromIMDMessageRecordRef:inputHandleString:useAttachmentCache:"
```
