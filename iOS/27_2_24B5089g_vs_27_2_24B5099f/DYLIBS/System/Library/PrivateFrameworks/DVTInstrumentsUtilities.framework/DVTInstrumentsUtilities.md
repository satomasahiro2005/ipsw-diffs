## DVTInstrumentsUtilities

> `/System/Library/PrivateFrameworks/DVTInstrumentsUtilities.framework/DVTInstrumentsUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x325dc` | `0x32708` | **`+0x12c`** |
| `__AUTH_CONST.__cfstring` | `0x8a40` | `0x8b20` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x5cda` | `0x5da7` | **`+0xcd`** |
| `__TEXT.__eh_frame` | `0x530` | `0x580` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x799` | `0x7d1` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0xbb0` | `0xbd0` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x374` | `0x354` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x18c0` | `0x18a8` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x1480` | `0x1498` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x1c` | `0x8` | **`-0x14`** |
| `__TEXT.__objc_methlist` | `0x2fdc` | `0x2fcc` | **`-0x10`** |
| `__TEXT.__const` | `0x177c` | `0x1770` | **`-0xc`** |
| `__TEXT.__gcc_except_tab` | `0x14b8` | `0x14c4` | **`+0xc`** |
| `__TEXT.__swift5_reflstr` | `0x175` | `0x181` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x343` | `0x345` | **`+0x2`** |

### Other Changes

```diff

-64578.160.1.0.0
+64578.209.1.0.0

+  - /System/Library/Frameworks/Security.framework/Security

-  Functions: 1533
-  Symbols:   619
-  CStrings:  1286
+  Functions: 1531
+  Symbols:   624
+  CStrings:  1292
Symbols:
+ _CFBooleanGetTypeID
+ _CFBooleanGetValue
+ _CFGetTypeID
+ _CFRelease
+ _DVTAuditedCodeValidlyHoldsEntitlement
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateWithAuditToken
+ _os_variant_allows_internal_security_policies
+ _swift_release_x27
- _CC_MD5_Final
- _CC_MD5_Init
- _CC_MD5_Update
- _swift_release_x26
CStrings:
+ "\"\\"
+ "DVTEntitlementCheck"
+ "invalid entitlement name: contains a quote or backslash"
+ "the audited process does not hold %@"
+ "the audited process holds %@ but is neither a platform binary nor debuggable (%#x)"
+ "the entitlement name was missing or malformed"
+ "unable to inspect the audited process"
+ "unable to read the audited process' code signing status"
- "-[XREngineeringTypeDefinitions checksum]"
- "chunk.length <= chunkSizeTarget"
```
