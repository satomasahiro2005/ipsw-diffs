## DiagnosticExtensionsKit

> `/System/Library/PrivateFrameworks/DiagnosticExtensionsKit.framework/DiagnosticExtensionsKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39bc8` | `0x3f57c` | **`+0x59b4`** |
| `__AUTH_CONST.__const` | `0x36d0` | `0x3f40` | **`+0x870`** |
| `__TEXT.__swift5_capture` | `0x1544` | `0x188c` | **`+0x348`** |
| `__TEXT.__cstring` | `0x9e6` | `0xa76` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0xe06` | `0xe76` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x5cc` | `0x63a` | **`+0x6e`** |
| `__DATA.__data` | `0x468` | `0x4b0` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x5d0` | `0x610` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x5a0` | `0x5e0` | **`+0x40`** |
| `__TEXT.__const` | `0x5b2` | `0x5e2` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x210` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x728` | `0x708` | **`-0x20`** |
| `__DATA.__bss` | `0x2a0` | `0x2b0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x318` | `0x328` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x34` | `0x44` | **`+0x10`** |
| `__DATA.__common` | `0x8` | `0x11` | **`+0x9`** |
| `__TEXT.__swift_as_cont` | `0x5c` | `0x54` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x44` | **`+0x8`** |

### Other Changes

```diff

-148.1.0.0.0
+149.0.0.0.0

-  Functions: 841
-  Symbols:   330
-  CStrings:  113
+  Functions: 929
+  Symbols:   340
+  CStrings:  120
Symbols:
+ _OBJC_CLASS_$__EXExtensionIdentity
+ _OBJC_CLASS_$__EXQuery
+ _OBJC_CLASS_$__EXQueryController
+ _swift_continuation_await
+ _swift_continuation_init
+ _symbolic SaySo20_EXExtensionIdentityCG
+ _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
+ _symbolic ScCySaySo11DEExtensionCG_____G s5NeverO
+ _symbolic ScCySo11DEExtensionCSg_____G s5NeverO
+ _symbolic xIegHr_
CStrings:
+ "Assertion failed"
+ "Extension not found: %{public}s"
+ "ExtensionKit discovery: %{public}ld extensions"
+ "Legacy lookup is skipped on darwinOS: %{public}s"
+ "On-demand ExtensionKit query failed for [%{public}s]: [%{public}s]"
+ "Start unified extension discovery (synchronous)"
+ "com.apple.diagnosticextensions.dek-discovery"
+ "findExtension(withIdentifier:)"
+ "loadLegacyExtensions()"
- "Extension not found in ExtensionKit and legacy lookup is skipped on darwinOS: %{public}s"
- "On-demand discovery task started for [%{public}s]"
```
