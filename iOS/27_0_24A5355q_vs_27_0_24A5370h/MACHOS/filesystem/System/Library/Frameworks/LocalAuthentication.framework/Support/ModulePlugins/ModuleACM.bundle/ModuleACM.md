## ModuleACM

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/ModulePlugins/ModuleACM.bundle/ModuleACM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x2742` | `0x27cb` | **`+0x89`** |
| `__TEXT.__cstring` | `0x2d38` | `0x2cd1` | **`-0x67`** |
| `__TEXT.__objc_stubs` | `0x2620` | `0x2680` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x617` | `0x643` | **`+0x2c`** |
| `__DATA.__objc_const` | `0x4f8` | `0x518` | **`+0x20`** |
| `__TEXT.__text` | `0x20cfc` | `0x20d18` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0xa58` | `0xa70` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x290` | `0x298` | **`+0x8`** |
| `__TEXT.__const` | `0x2b8` | `0x2c0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x48` | `0x4c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2305.0.0.0.1
+2319.0.16.502.1

-  Functions: 640
-  Symbols:   447
-  CStrings:  919
+  Functions: 636
+  Symbols:   448
+  CStrings:  922
Symbols:
+ _OBJC_CLASS_$_LACAnalyticsContextManagementReporterProvider
CStrings:
+ "@\"<LACAnalyticsContextManagementReporting>\""
+ "_analyticsReporter"
+ "checkOriginatorCanAccessEncodingSeed:error:"
+ "credentialEncodingSeedWithOriginator:reply:"
+ "reportContextExhaustionWithGreediestCount:uniquePids:"
+ "reporter"
- "ACMCredential - ACMCredentialDataPKITokenValidated"
- "ACMCredential - ACMCredentialDataPKITokenValidated2"
- "credentialEncodingSeedWithReply:"
```
