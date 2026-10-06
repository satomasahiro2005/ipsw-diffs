## com.apple.dt.instruments.dtsecurity

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/XPCServices/com.apple.dt.instruments.dtsecurity.xpc/com.apple.dt.instruments.dtsecurity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11a10` | `0x11f9c` | **`+0x58c`** |
| `__TEXT.__cstring` | `0x1216` | `0x1326` | **`+0x110`** |
| `__DATA_CONST.__cfstring` | `0xa40` | `0xb20` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x12cc` | `0x136c` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x16d0` | `0x1740` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x13c5` | `0x1415` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x12c0` | `0x1300` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0xb80` | `0xbb8` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x5a8` | `0x5b8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x550` | `0x560` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x1d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-64578.160.1.0.0
+64578.209.1.0.0

-  Functions: 395
-  Symbols:   456
-  CStrings:  589
+  Functions: 399
+  Symbols:   465
+  CStrings:  600
Symbols:
+ _CFBooleanGetTypeID
+ _CFBooleanGetValue
+ _CFGetTypeID
+ _DVTAuditedCodeValidlyHoldsEntitlement
+ _OBJC_CLASS_$_NSCharacterSet
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateWithAuditToken
+ _os_variant_allows_internal_security_policies
+ _xpc_connection_get_audit_token
CStrings:
+ "\"\\"
+ "DVTEntitlementCheck"
+ "Denying connection from process (%d : %p) because it does not validly hold the entitlement: %{public}s"
+ "characterSetWithCharactersInString:"
+ "invalid entitlement name: contains a quote or backslash"
+ "rangeOfCharacterFromSet:"
+ "the audited process does not hold %@"
+ "the audited process holds %@ but is neither a platform binary nor debuggable (%#x)"
+ "the entitlement name was missing or malformed"
+ "unable to inspect the audited process"
+ "unable to read the audited process' code signing status"
```
