## SMS

> `/System/Library/Messages/PlugIns/SMS.imservice/SMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b08` | `0x10c78` | **`+0x170`** |
| `__TEXT.__objc_methname` | `0x48ea` | `0x4932` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x1e4b` | `0x1e7b` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x2b00` | `0x2b20` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xdbc` | `0xdd4` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1178` | `0x1184` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x1038` | `0x1040` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x558` | `0x560` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1491.200.73.0.0
+1491.200.95.0.0

-  Functions: 222
+  Functions: 223

-  CStrings:  1024
+  CStrings:  1026
Symbols:
+ _IMNormalizedPhoneNumberForPhoneNumber
- _IMCanonicalizeFormattedString
Functions:
~ sub_74c8 : 4036 -> 252
+ sub_75c4
CStrings:
+ "Incoming recipient %@ is not the altPhoneNumber %@"
+ "_incomingRecipientHandle:matchesHiddenLocalNumber:receivingCountryCode:"
```
