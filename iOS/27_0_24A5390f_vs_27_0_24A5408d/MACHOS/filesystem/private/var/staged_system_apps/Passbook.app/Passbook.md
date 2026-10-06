## Passbook

> `/private/var/staged_system_apps/Passbook.app/Passbook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x100c4` | `0xffa0` | **`-0x124`** |
| `__TEXT.__objc_methname` | `0x4779` | `0x4828` | **`+0xaf`** |
| `__TEXT.__objc_stubs` | `0x2f20` | `0x2f80` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0xfa8` | `0xfdd` | **`+0x35`** |
| `__DATA_CONST.__cfstring` | `0x500` | `0x520` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xfd8` | `0xff0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x920` | `0x930` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x940` | `0x938` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2d0` | `0x2c8` | **`-0x8`** |
| `__TEXT.__cstring` | `0x74b` | `0x751` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1689.3.0.0.0
+1695.1.2.0.0

-  Functions: 199
-  Symbols:   402
-  CStrings:  785
+  Functions: 198
+  Symbols:   404
+  CStrings:  790
Symbols:
+ _OBJC_CLASS_$_NSUserActivity
+ _PKURLParamAppletSubcredentialReferralSource
CStrings:
+ "_presentOrderManagementForPathComponents:sourceApplication:analyticsEvent:"
+ "https"
+ "initWithActivityType:"
+ "presentResumeForPendingProvisioningOfType:identifier:referralSource:"
+ "presentUserPassEditorForPass:style:sourceImage:analyticsSessionIdentifier:analyticsEntrySource:completion:"
+ "setWebpageURL:"
+ "v64@0:8@\"PKPass\"16q24@\"UIImage\"32@\"NSString\"40@\"NSString\"48@?<v@?B>56"
+ "v64@0:8@16q24@32@40@48@?56"
- "presentResumeForPendingProvisioningOfType:identifier:"
- "presentUserPassEditorForPass:style:sourceImage:completion:"
- "v48@0:8@\"PKPass\"16q24@\"UIImage\"32@?<v@?B>40"
```
