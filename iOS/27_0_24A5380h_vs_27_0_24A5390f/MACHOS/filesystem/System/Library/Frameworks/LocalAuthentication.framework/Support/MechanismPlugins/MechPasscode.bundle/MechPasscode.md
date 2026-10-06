## MechPasscode

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/MechanismPlugins/MechPasscode.bundle/MechPasscode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14438` | `0x14450` | **`+0x18`** |
| `__TEXT.__const` | `0x190` | `0x188` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2319.0.33.0.1
+2319.0.46.0.0
Functions:
~ sub_59b4 : 12 -> 20
~ sub_59c0 -> sub_59c8 : 20 -> 12
~ _DeserializeCredential : 436 -> 460
```
