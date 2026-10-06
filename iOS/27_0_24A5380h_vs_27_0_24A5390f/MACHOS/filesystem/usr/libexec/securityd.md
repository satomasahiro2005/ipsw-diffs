## securityd

> `/usr/libexec/securityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26c4bc` | `0x26c590` | **`+0xd4`** |
| `__TEXT.__objc_stubs` | `0x1d8c0` | `0x1d8e0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x2e5af` | `0x2e5bf` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x9850` | `0x9858` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62460.0.38.0.1
+62460.0.55.0.1

-  CStrings:  16391
+  CStrings:  16392
Symbols:
+ _kSecurityRTCEventNameJoinButDistrustEveryone
- _kSecurityRTCFieldDistrustEveryoneOnJoin
Functions:
~ sub_10012e48c : 932 -> 1048
~ sub_1001bbabc -> sub_1001bbb30 : 984 -> 996
~ sub_10020bf0c -> sub_10020bf8c : 1432 -> 1444
~ sub_10020c6c0 -> sub_10020c74c : 112 -> 184
CStrings:
+ "setPreventCylonUsage:"
```
