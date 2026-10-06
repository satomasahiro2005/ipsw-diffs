## installd

> `/usr/libexec/installd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x73f2c` | `0x740f0` | **`+0x1c4`** |
| `__TEXT.__cstring` | `0x19583` | `0x19733` | **`+0x1b0`** |
| `__DATA_CONST.__cfstring` | `0xaa60` | `0xaac0` | **`+0x60`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1680.40.6.502.1
+1680.40.8.0.1

-  CStrings:  4005
+  CStrings:  4008
Functions:
~ sub_1000549b8 : 948 -> 1400
CStrings:
+ "\"%@\" has the \"%@\" entitlement, which is set to an empty list. At least one app's application identifier is required."
+ "\"%@\" is missing the \"%@\" entitlement. This entitlement is required on this app because the extensions with bundle identifier(s) %@ in the app, carry this entitlement."
+ "The app extension at \"%@\" has the \"%@\" entitlement, which is set to an empty list. At least one extension's application identifier is required."
```
