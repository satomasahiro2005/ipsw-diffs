## DualShock4HIDServicePlugin

> `/System/Library/HIDPlugins/ServicePlugins/DualShock4HIDServicePlugin.plugin/DualShock4HIDServicePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3be0` | `0x3bb0` | **`-0x30`** |
| `__TEXT.__objc_stubs` | `0x6c0` | `0x6a0` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0xa55` | `0xa45` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x310` | `0x308` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-14.0.17.0.0
+14.0.19.0.0

-  CStrings:  271
+  CStrings:  270
Functions:
~ sub_3114 : 988 -> 980
~ sub_37a8 -> sub_37a0 : 668 -> 628
CStrings:
- "propertyForKey:"
```
