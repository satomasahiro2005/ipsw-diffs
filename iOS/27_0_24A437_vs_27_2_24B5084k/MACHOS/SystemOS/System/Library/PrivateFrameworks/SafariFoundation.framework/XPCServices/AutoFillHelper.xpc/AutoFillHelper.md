## AutoFillHelper

> `/System/Library/PrivateFrameworks/SafariFoundation.framework/XPCServices/AutoFillHelper.xpc/AutoFillHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x668` | `0x20c` | **`-0x45c`** |
| `__TEXT.__objc_methname` | `0x4e4` | `0x265` | **`-0x27f`** |
| `__TEXT.__objc_stubs` | `0x2c0` | `0x160` | **`-0x160`** |
| `__TEXT.__auth_stubs` | `0x1b0` | `0xc0` | **`-0xf0`** |
| `__TEXT.__objc_methtype` | `0x1c5` | `0x111` | **`-0xb4`** |
| `__TEXT.__cstring` | `0xf2` | `0x43` | **`-0xaf`** |
| `__DATA_CONST.__auth_got` | `0xe0` | `0x68` | **`-0x78`** |
| `__DATA.__objc_selrefs` | `0x168` | `0x108` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x50` | `—` | **`-0x50`** |
| `__TEXT.__objc_methlist` | `0x19c` | `0x164` | **`-0x38`** |
| `__DATA_CONST.__got` | `0x60` | `0x38` | **`-0x28`** |
| `__DATA_CONST.__cfstring` | `0x40` | `0x20` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x78` | `0x60` | **`-0x18`** |
| `__DATA.__objc_const` | `0x318` | `0x308` | **`-0x10`** |
| `__TEXT.__const` | `0x8` | `—` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-7625.1.29.10.29
+7625.2.4.1.0

-  Functions: 8
-  Symbols:   51
-  CStrings:  80
+  Functions: 3
+  Symbols:   31
+  CStrings:  61
Symbols:
- _OBJC_CLASS_$_LSBundleRecord
- _OBJC_CLASS_$_NSMutableArray
- _OBJC_CLASS_$_SFStrongPasswordGenerator
- _WBSApplicationIdentifierFromAuditToken
- _WBSAuditTokenHasEntitlement
- __NSConcreteStackBlock
- ___NSArray0__struct
- _objc_autoreleaseReturnValue
- _objc_release_x22
- _objc_release_x23
- _objc_release_x24
- _objc_release_x25
- _objc_release_x26
- _objc_release_x8
- _objc_retain_x1
- _objc_retain_x19
- _objc_retain_x20
- _objc_retain_x21
- _objc_retain_x22
- _objc_retain_x8
CStrings:
- "@\"NSString\"16@?0@\"SFSharedWebCredentialsDatabaseEntry\"8"
- "_getAutomaticStrongPasswordForAppWithPasswordRules:confirmPasswordRules:overrideApplicationIdentifier:completion:"
- "addObject:"
- "addObjectsFromArray:"
- "auditToken"
- "bestDomainAndAllApprovedDatabaseEntriesForAppID:completionHandler:"
- "bundleRecordWithApplicationIdentifier:error:"
- "canOfferToSuggestStrongPasswordsForApplication:"
- "com.apple.private.safari.automatic-strong-passwords.can-override-application-identifier"
- "domain"
- "generatedPasswordForAppWithAssociatedDomains:passwordRules:confirmPasswordRules:"
- "getAutomaticStrongPasswordForAppWithPasswordRules:confirmPasswordRules:completion:"
- "getAutomaticStrongPasswordForAppWithPasswordRules:confirmPasswordRules:overrideApplicationIdentifier:completion:"
- "safari_mapAndFilterObjectsUsingBlock:"
- "v24@?0@\"NSString\"8@\"NSArray\"16"
- "v40@0:8@\"NSString\"16@\"NSString\"24@?<v@?@\"NSString\"@\"NSError\">32"
- "v40@0:8@16@24@?32"
- "v48@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32@?<v@?@\"NSString\"@\"NSError\">40"
- "v48@0:8@16@24@32@?40"
```
