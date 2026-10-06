## Siri

> `/Applications/Siri.app/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xdb14` | `0xdb84` | **`+0x70`** |
| `__TEXT.__text` | `0xf0f28` | `0xf0f90` | **`+0x68`** |
| `__DATA.__objc_const` | `0x10e48` | `0x10e68` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x2b91f` | `0x2b93f` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x8d8` | `0x8dc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
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

-3600.55.37.11.2
+3600.55.37.11.4

-  CStrings:  9058
+  CStrings:  9060
Functions:
~ sub_100092910 : 292 -> 300
~ sub_100092e8c -> sub_100092e94 : 552 -> 640
~ sub_1000b0054 -> sub_1000b00b4 : 532 -> 540
CStrings:
+ "%s #uifree Incoming-call announce offer turn; holding announce idle timer to preserve the answer window"
+ "_announceIsIncomingCall"
```
