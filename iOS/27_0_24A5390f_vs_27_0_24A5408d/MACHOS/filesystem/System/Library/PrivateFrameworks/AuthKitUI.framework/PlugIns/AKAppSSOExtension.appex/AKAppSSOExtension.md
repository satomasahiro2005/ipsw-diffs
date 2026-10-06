## AKAppSSOExtension

> `/System/Library/PrivateFrameworks/AuthKitUI.framework/PlugIns/AKAppSSOExtension.appex/AKAppSSOExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11018` | `0x12278` | **`+0x1260`** |
| `__DATA.__objc_const` | `0x7d8` | `0xfd0` | **`+0x7f8`** |
| `__TEXT.__oslogstring` | `0xe16` | `0x1026` | **`+0x210`** |
| `__TEXT.__objc_methname` | `0x1b95` | `0x1d20` | **`+0x18b`** |
| `__TEXT.__objc_stubs` | `0x1800` | `0x1960` | **`+0x160`** |
| `__DATA.__data` | `0x130` | `0x1f0` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x6e8` | `0x798` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x4578` | `0x4628` | **`+0xb0`** |
| `__DATA.__objc_data` | `0x190` | `0x230` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x5d4` | `0x66c` | **`+0x98`** |
| `__TEXT.__objc_methtype` | `0x303` | `0x382` | **`+0x7f`** |
| `__TEXT.__objc_classname` | `0xe9` | `0x165` | **`+0x7c`** |
| `__DATA.__objc_selrefs` | `0x860` | `0x8b8` | **`+0x58`** |
| `__DATA_CONST.__cfstring` | `0x2680` | `0x26c0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x1b8` | `0x1d0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x38` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x18` | `0x28` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2e0` | `0x2f0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x180` | `0x188` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x4` | `0x8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-555.0.0.0.0
+559.0.0.0.0

+  - /System/Library/PrivateFrameworks/SharedWebCredentials.framework/SharedWebCredentials

-  Functions: 133
-  Symbols:   194
-  CStrings:  705
+  Functions: 143
+  Symbols:   202
+  CStrings:  737
Symbols:
+ _OBJC_CLASS_$_AKBrowserEntitlementChecker
+ _OBJC_CLASS_$_AKRedirectDomainOwnershipChecker
+ _OBJC_CLASS_$__SWCServiceDetails
+ _OBJC_CLASS_$__SWCServiceSpecifier
+ _OBJC_METACLASS_$_AKBrowserEntitlementChecker
+ _OBJC_METACLASS_$_AKRedirectDomainOwnershipChecker
+ __SWCServiceTypeAuthServices
+ _objc_opt_new
CStrings:
+ "@48@0:8{?=[8I]}16"
+ "AKBrowserEntitlementChecker"
+ "AKBrowserEntitlementChecking"
+ "AKRedirectDomainOwnershipChecker"
+ "AKRedirectDomainOwnershipChecking"
+ "B24@0:8@\"NSString\"16"
+ "Caller is not entitled for third-party redirect. Authorization request not handled."
+ "Caller is valid and owns the redirect domain."
+ "Caller owns redirect domain via swcd-verified association."
+ "Error while waiting for site approval: %@"
+ "Missing audit token for third-party redirect. Authorization request not handled."
+ "No approved or pending association for caller; redirect-domain ownership denied."
+ "Redirect-domain association is not yet approved; waiting for swcd to resolve its site approval."
+ "_applicationIdentifierForTeamID:bundleID:"
+ "_auditToken"
+ "_hasBrowserEntitlement:"
+ "_isFirstPartyRedirectURL:"
+ "_proceedWithClassificationForRequest:"
+ "com.apple.authentication-services.allow-authentication-request-any-rpid"
+ "com.apple.developer.web-browser.public-key-credential"
+ "hasEntitlement:"
+ "initWithAuditToken:"
+ "initWithServiceType:applicationIdentifier:domain:"
+ "isApproved"
+ "serviceDetailsWithServiceSpecifier:limit:auditToken:error:"
+ "siteApprovalState"
+ "swcd service-details lookup failed: %@"
+ "v12@?0B8"
+ "v24@?0@\"_SWCServiceDetails\"8@\"NSError\"16"
+ "v80@0:8@\"NSURL\"16@\"NSString\"24@\"NSString\"32{?=[8I]}40@?<v@?B>72"
+ "v80@0:8@16@24@32{?=[8I]}40@?72"
+ "verifyOwnershipOfRedirectURL:callerTeamID:callerBundleID:auditToken:completion:"
+ "waitForSiteApprovalWithCompletionHandler:"
+ "{?=\"val\"[8I]}"
- "B56@0:8{?=[8I]}16@48"
- "checkEntitlementForAuditToken:entitlement:"
```
