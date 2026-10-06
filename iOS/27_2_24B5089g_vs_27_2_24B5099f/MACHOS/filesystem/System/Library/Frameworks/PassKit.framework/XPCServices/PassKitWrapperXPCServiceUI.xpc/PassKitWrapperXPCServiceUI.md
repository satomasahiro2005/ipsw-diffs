## PassKitWrapperXPCServiceUI

> `/System/Library/Frameworks/PassKit.framework/XPCServices/PassKitWrapperXPCServiceUI.xpc/PassKitWrapperXPCServiceUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc81c` | `0xd09c` | **`+0x880`** |
| `__TEXT.__oslogstring` | `0x277` | `0x327` | **`+0xb0`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x200` | **`+0x20`** |
| `__DATA.__data` | `0x6d0` | `0x6e0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xf80` | `0xf90` | **`+0x10`** |
| `__TEXT.__const` | `0xc92` | `0xca2` | **`+0x10`** |
| `__DATA.__objc_data` | `0x4d8` | `0x4e0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x7c8` | `0x7d0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x340` | `0x348` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x51c` | `0x524` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x117e` | `0x1186` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x378` | `0x380` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x130` | `0x134` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1696.2.5.0.0
+1696.2.8.1.0

-  Functions: 313
-  Symbols:   198
-  CStrings:  179
+  Functions: 314
+  Symbols:   195
+  CStrings:  182
Symbols:
- _PKAggDKeyApplePayButtonErrorTypeNoPassImageReceived
- _objc_release_x28
- _objc_retain_x26
CStrings:
+ "Matched pass could not be resolved to a payment pass"
+ "Pass library unavailable, cannot render card art"
+ "Pass snapshot did not carry a CGImage."
```
