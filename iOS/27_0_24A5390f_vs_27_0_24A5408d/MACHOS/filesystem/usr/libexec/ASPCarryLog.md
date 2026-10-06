## ASPCarryLog

> `/usr/libexec/ASPCarryLog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x274bc` | `0x27504` | **`+0x48`** |
| `__TEXT.__cstring` | `0x8e0b` | `0x8e3f` | **`+0x34`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-849.0.5.0.0
+849.0.11.0.0

-  CStrings:  2530
+  CStrings:  2532
Functions:
~ sub_1000144f0 : 68076 -> 68148
CStrings:
+ "gcSlowInlineWritesMigration"
+ "gcSlowInlineWritesTotal"
```
