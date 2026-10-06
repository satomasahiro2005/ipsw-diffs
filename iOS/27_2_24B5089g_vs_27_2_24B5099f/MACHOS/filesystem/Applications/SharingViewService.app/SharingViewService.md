## SharingViewService

> `/Applications/SharingViewService.app/SharingViewService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x169e38` | `0x169eb8` | **`+0x80`** |
| `__TEXT.__cstring` | `0x109c3` | `0x10a19` | **`+0x56`** |
| `__TEXT.__objc_stubs` | `0x9d80` | `0x9dc0` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x4120` | `0x4140` | **`+0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0x78` | `0x90` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x3c88` | `0x3c98` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x178` | `0x180` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_capture`
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

-2131.20.71.0.0
+2131.21.21.0.0

-  CStrings:  5816
+  CStrings:  5820
Functions:
~ sub_1000050c0 : 580 -> 704
~ sub_100062c6c -> sub_100062ce8 : 124 -> 128
~ sub_100082fcc -> sub_10008304c : 6704 -> 6716
~ sub_10009350c -> sub_100093598 : 2588 -> 2576
~ sub_100145078 -> sub_1001450f8 : 6704 -> 6716
~ sub_100154eac -> sub_100154f38 : 2588 -> 2576
CStrings:
+ "### Disallowed Home launch URL scheme '%@', falling back to bundle ID\n"
+ "com.apple.home"
+ "scheme"
+ "sf_hasSchemeIn:"
```
