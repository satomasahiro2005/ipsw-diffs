## com.apple.MobileInstallationHelperService

> `/System/Library/PrivateFrameworks/MobileInstallation.framework/XPCServices/com.apple.MobileInstallationHelperService.xpc/com.apple.MobileInstallationHelperService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x151ec` | `0x152b8` | **`+0xcc`** |
| `__TEXT.__cstring` | `0x5e64` | `0x5eb7` | **`+0x53`** |
| `__DATA_CONST.__cfstring` | `0x3440` | `0x3480` | **`+0x40`** |
| `__TEXT.__const` | `0xa8` | `0xb0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1674.2.1.0.0
+1680.40.6.502.1

-  Functions: 308
-  Symbols:   409
-  CStrings:  1007
+  Functions: 310
+  Symbols:   411
+  CStrings:  1009
Symbols:
+ _MICopySupersededApplicationIdentifiersEntitlement
+ _MIHasHomeKitEntitlement
Functions:
+ _MICopySupersededApplicationIdentifiersEntitlement
+ _MIHasHomeKitEntitlement
CStrings:
+ "21:06:02"
+ "Sep  8 2026"
+ "com.apple.developer.homekit"
+ "com.apple.developer.superseded-application-identifiers"
- "16:21:38"
- "Aug  8 2026"
```
