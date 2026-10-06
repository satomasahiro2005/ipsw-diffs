## apsd

> `/System/Library/PrivateFrameworks/ApplePushService.framework/apsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x120354` | `0x1203cc` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x144c5` | `0x14525` | **`+0x60`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1168.200.31.0.0
+1168.200.41.0.0

-  CStrings:  8695
+  CStrings:  8696
Functions:
~ sub_1000ad54c : 276 -> 380
~ sub_100113754 -> sub_1001137bc : 208 -> 212
~ sub_10011670c -> sub_100116778 : 488 -> 500
CStrings:
+ "%@ ignoring connect notification from stream %@ that is no longer bound to an interface"
```
