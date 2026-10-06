## DiagnosticExtensionsKit

> `/System/Library/PrivateFrameworks/DiagnosticExtensionsKit.framework/DiagnosticExtensionsKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38710` | `0x39b74` | **`+0x1464`** |
| `__AUTH_CONST.__const` | `0x3518` | `0x36d0` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0xd16` | `0xe06` | **`+0xf0`** |
| `__TEXT.__swift5_capture` | `0x14a8` | `0x1544` | **`+0x9c`** |
| `__TEXT.__eh_frame` | `0x6b0` | `0x728` | **`+0x78`** |
| `__TEXT.__const` | `0x560` | `0x5b2` | **`+0x52`** |
| `__TEXT.__swift5_typeref` | `0x5a4` | `0x5cc` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x588` | `0x5a0` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0xc0` | `0xd7` | **`+0x17`** |
| `__AUTH_CONST.__auth_got` | `0x5c8` | `0x5d0` | **`+0x8`** |
| `__DATA.__data` | `0x460` | `0x468` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x14` | `0x18` | **`+0x4`** |

### Other Changes

```diff

-148.0.0.0.0
+148.1.0.0.0

-  Functions: 824
+  Functions: 841

-  CStrings:  111
+  CStrings:  113
Symbols:
+ _symbolic _____ySo11DEExtensionCSg______pGSg s6ResultOsRi_zRi0_zrlE s5ErrorP
+ _symbolic _____y_____ySo11DEExtensionCSg______pGSgG 2os21OSAllocatedUnfairLockV s6ResultOsRi_zRi0_zrlE s5ErrorP
- _symbolic So11DEExtensionCSgz_Xx
- _symbolic ______pSgz_Xx s5ErrorP
CStrings:
+ "Extension point query returned [%{public}ld] identities for [%{public}s]"
+ "Extension point query started for [%{public}s]"
+ "On-demand discovery for [%{public}s] did not complete within 60s; returning nil, which callers surface as \"extension not found\" even though the extension may be present"
+ "On-demand discovery task started for [%{public}s]"
- "Found %ld total extensions at extension point"
- "extensionWithIdentifier timed out after 60 seconds for: %{public}s"
```
