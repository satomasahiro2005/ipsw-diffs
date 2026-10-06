## MechPasscode

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/MechanismPlugins/MechPasscode.bundle/MechPasscode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14450` | `0x14490` | **`+0x40`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2319.0.46.0.0
+2319.0.63.0.0
Functions:
~ sub_58ac : 8 -> 12
~ sub_58b4 -> sub_58b8 : 12 -> 28
~ sub_58c0 -> sub_58d4 : 16 -> 8
~ sub_58d0 -> sub_58dc : 28 -> 16
~ sub_59a8 : 12 -> 20
~ sub_59b4 -> sub_59bc : 20 -> 12
~ _LibSer_SEPControl_Deserialize : 160 -> 200
~ _LibSer_SEPControlResponse_Deserialize : 64 -> 88
```
