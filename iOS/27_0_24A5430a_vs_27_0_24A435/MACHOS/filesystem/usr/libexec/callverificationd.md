## callverificationd

> `/usr/libexec/callverificationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12f34` | `0x12ea8` | **`-0x8c`** |
| `__TEXT.__objc_stubs` | `0x540` | `0x520` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x899` | `0x87f` | **`-0x1a`** |
| `__DATA.__objc_selrefs` | `0x2a8` | `0x2a0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x198` | `0x190` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   364
-  CStrings:  214
+  Symbols:   363
+  CStrings:  213
Symbols:
- _AKSeedBuildHeaderKey
Functions:
~ sub_1000048f8 : 28 -> 20
~ sub_100004914 -> sub_10000490c : 20 -> 28
~ sub_100004950 : 20 -> 12
~ sub_100004964 -> sub_10000495c : 12 -> 20
~ sub_100004970 : 20 -> 12
~ sub_100004984 -> sub_10000497c : 12 -> 20
~ sub_10000ab24 : 1220 -> 1116
~ sub_10000b520 -> sub_10000b4b8 : 100 -> 104
~ sub_10000bd04 -> sub_10000bca0 : 656 -> 648
~ sub_10000d0e4 -> sub_10000d078 : 24 -> 12
~ sub_10000d0fc -> sub_10000d084 : 12 -> 24
~ sub_10000d108 -> sub_10000d09c : 44 -> 12
CStrings:
- "shouldHideSeedBuildHeader"
```
