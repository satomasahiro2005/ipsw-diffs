## swtransparencyd

> `/usr/libexec/swtransparencyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x77cd` | `0x780d` | **`+0x40`** |
| `__DATA.__objc_const` | `0xe830` | `0xe860` | **`+0x30`** |
| `__TEXT.__text` | `0xfde8c` | `0xfdeac` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x709c` | `0x70b4` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x2148` | `0x2158` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x464` | `0x468` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1766.0.39.0.2
+1766.0.60.0.0

-  Functions: 6029
+  Functions: 6031

-  CStrings:  2890
+  CStrings:  2894
CStrings:
+ "T@\"NSString\",&,V_requestType"
+ "_requestType"
+ "requestType"
+ "setRequestType:"
```
