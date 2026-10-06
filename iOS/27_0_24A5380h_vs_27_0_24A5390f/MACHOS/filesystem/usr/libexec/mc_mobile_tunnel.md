## mc_mobile_tunnel

> `/usr/libexec/mc_mobile_tunnel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7064` | `0x7098` | **`+0x34`** |
| `__TEXT.__objc_stubs` | `0x12e0` | `0x1300` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1417` | `0x1432` | **`+0x1b`** |
| `__TEXT.__auth_stubs` | `0x6d0` | `0x6e0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x538` | `0x540` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x378` | `0x380` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-111.0.0.0.0
+113.0.2.0.0

-  Symbols:   231
-  CStrings:  378
+  Symbols:   232
+  CStrings:  379
Symbols:
+ _MDMCreateSecureLAContextWithPasscodeData
Functions:
~ sub_100003698 : 268 -> 320
CStrings:
+ "clearPasscodeWithEscrowKeybagData:secretContext:outError:"
+ "externalizedContext"
- "clearPasscodeWithEscrowKeybagData:secret:outError:"
```
