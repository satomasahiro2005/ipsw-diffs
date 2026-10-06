## PassKitWrapperXPCServiceUI

> `/System/Library/Frameworks/PassKit.framework/XPCServices/PassKitWrapperXPCServiceUI.xpc/PassKitWrapperXPCServiceUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc664` | `0xc824` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0x223` | `0x277` | **`+0x54`** |
| `__TEXT.__objc_methname` | `0x90b` | `0x8db` | **`-0x30`** |
| `__TEXT.__objc_stubs` | `0x6c0` | `0x6a0` | **`-0x20`** |
| `__DATA.__data` | `0x6c0` | `0x6d0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xf70` | `0xf80` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x280` | `0x278` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x7c0` | `0x7c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1677.4.0.0.0
+1682.1.0.0.0

-  Functions: 312
-  Symbols:   197
+  Functions: 313
+  Symbols:   198
Symbols:
+ _OBJC_CLASS_$_PKPaymentApplication
CStrings:
+ "Default pass has no payment applications that supports in app payments"
+ "deviceInAppPaymentApplications"
- "devicePrimaryPaymentApplication"
- "supportsInAppPayment"
```
