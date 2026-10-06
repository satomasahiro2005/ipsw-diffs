## SoftwareUpdateServicesUIPlugin

> `/System/Library/PrivateFrameworks/SoftwareUpdateServicesUI.framework/Plugins/SoftwareUpdateServicesUIPlugin.servicebundle/SoftwareUpdateServicesUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41260` | `0x4135c` | **`+0xfc`** |
| `__TEXT.__oslogstring` | `0x48c5` | `0x48ec` | **`+0x27`** |
| `__TEXT.__objc_stubs` | `0x5540` | `0x5520` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x6170` | `0x6154` | **`-0x1c`** |
| `__DATA.__objc_selrefs` | `0x1968` | `0x1960` | **`-0x8`** |

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
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-305.0.1.0.0
+305.40.5.0.0
Functions:
~ sub_6e54 : 872 -> 1092
~ sub_1fbd0 -> sub_1fcac : 1164 -> 1196
CStrings:
+ "Failed to serialize install policy: %@"
- "archivedDataWithRootObject:"
```
