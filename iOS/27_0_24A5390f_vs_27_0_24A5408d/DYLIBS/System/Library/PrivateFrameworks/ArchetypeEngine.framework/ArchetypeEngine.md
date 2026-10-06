## ArchetypeEngine

> `/System/Library/PrivateFrameworks/ArchetypeEngine.framework/ArchetypeEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x97de0` | `0x9c42c` | **`+0x464c`** |
| `__TEXT.__eh_frame` | `0x46f8` | `0x4968` | **`+0x270`** |
| `__AUTH_CONST.__const` | `0x2410` | `0x24e0` | **`+0xd0`** |
| `__DATA.__data` | `0xd10` | `0xde0` | **`+0xd0`** |
| `__TEXT.__const` | `0x2108` | `0x21c8` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0x1cf0` | `0x1da8` | **`+0xb8`** |
| `__TEXT.__oslogstring` | `0x2b49` | `0x2bf9` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x1838` | `0x18c8` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x1406` | `0x1490` | **`+0x8a`** |
| `__TEXT.__swift5_capture` | `0xacc` | `0xb0c` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0xc64` | `0xca0` | **`+0x3c`** |
| `__TEXT.__cstring` | `0xfeb` | `0x1025` | **`+0x3a`** |
| `__DATA_CONST.__objc_selrefs` | `0x720` | `0x758` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x974` | `0x9a0` | **`+0x2c`** |
| `__DATA_DIRTY.__data` | `0x5f8` | `0x620` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0xa2c` | `0xa51` | **`+0x25`** |
| `__TEXT.__swift_as_cont` | `0x28c` | `0x298` | **`+0xc`** |
| `__DATA.__common` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xb0` | `0xb4` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x2c` | `0x30` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x98` | `0x9c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xec` | `0xf0` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x108` | `0x10c` | **`+0x4`** |

### Other Changes

```diff

-41.7.0.0.0
+41.11.0.0.0

+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  - /System/Library/PrivateFrameworks/GenerativeSearch.framework/GenerativeSearch

-  Functions: 2742
-  Symbols:   344
-  CStrings:  249
+  Functions: 2800
+  Symbols:   347
+  CStrings:  253
Symbols:
+ _OBJC_CLASS_$_CCMailAddressForm
+ _OBJC_CLASS_$_CNContactFormatter
+ _OBJC_CLASS_$_NSUserDefaults
CStrings:
+ "Exact-match filter kept %ld of %ld result(s)"
+ "HybridSearchClient: Failed to extract  profile content: %s"
+ "HybridSearchClient: Failed to extract remote profile content: %s"
+ "LearningPlatformWritingStyleRetrieval: Mail Smart Reply profiles gated — PersonalizedSmartReplies disabled; returning none"
+ "PersonalizedSmartReplies"
+ "group.com.apple.mail"
- "GenerativeSearchClient: Failed to extract  profile content: %s"
- "GenerativeSearchClient: Failed to extract remote profile content: %s"
```
