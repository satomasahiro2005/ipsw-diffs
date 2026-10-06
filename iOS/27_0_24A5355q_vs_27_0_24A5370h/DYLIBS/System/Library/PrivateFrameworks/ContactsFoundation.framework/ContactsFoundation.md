## ContactsFoundation

> `/System/Library/PrivateFrameworks/ContactsFoundation.framework/ContactsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x939c8` | `0x950f0` | **`+0x1728`** |
| `__TEXT.__eh_frame` | `0x8e0` | `0xa08` | **`+0x128`** |
| `__AUTH_CONST.__auth_got` | `0x1060` | `0x1120` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x3580` | `0x3630` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x3878` | `0x3918` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x16160` | `0x161d8` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0xa9f4` | `0xaa5c` | **`+0x68`** |
| `__TEXT.__const` | `0xea0` | `0xef0` | **`+0x50`** |
| `__DATA.__bss` | `0x8e0` | `0x910` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x4ba0` | `0x4bd0` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x680` | `0x6ac` | **`+0x2c`** |
| `__AUTH.__data` | `0x430` | `0x458` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xaee0` | `0xaf00` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x2cb0` | `0x2cd0` | **`+0x20`** |
| `__DATA.__data` | `0x1c40` | `0x1c20` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x590` | `0x570` | **`-0x20`** |
| `__TEXT.__cstring` | `0x70f4` | `0x7114` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x644` | `0x65c` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x440` | `0x450` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x221` | `0x216` | **`-0xb`** |
| `__DATA_CONST.__const` | `0x3888` | `0x3890` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xe88` | `0xe90` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xaa0` | `0xaa8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x6c` | `0x70` | **`+0x4`** |

### Other Changes

```diff

-1421.100.1.0.0
+1423.100.1.0.0

+  - /System/Library/Frameworks/CFNetwork.framework/CFNetwork

-  Functions: 4977
-  Symbols:   8650
-  CStrings:  1905
+  Functions: 5006
+  Symbols:   8666
+  CStrings:  1907
Symbols:
+ +[NSString(ContactsFoundationPhoneNumbers) _cn_visibleCharacters]
+ -[CNEntitlementVerifier auditToken:allowsExpressWithError:]
+ -[CNEntitlementVerifier expressBundleIdentifiers]
+ -[CNEntitlementVerifier secTask:allowsExpressWithError:]
+ -[CNEntitlementVerifierTestDouble auditToken:allowsExpressWithError:]
+ -[CNEntitlementVerifierTestDouble setAuditToken:allowsExpress:]
+ -[CNEntitlementVerifierTestDouble setAuditToken:allowsExpressError:]
+ -[NSString(ContactsFoundationPhoneNumbers) _cn_hasVisibleContent]
+ _OBJC_CLASS_$_CNURLSecurity
+ _OBJC_METACLASS_$_CNURLSecurity
+ __CFHostGetTopLevelDomain
+ __CLASS_METHODS_CNURLSecurity
+ __DATA_CNURLSecurity
+ __INSTANCE_METHODS_CNURLSecurity
+ __METACLASS_DATA_CNURLSecurity
+ ___49-[CNEntitlementVerifier expressBundleIdentifiers]_block_invoke
+ ___65+[NSString(ContactsFoundationPhoneNumbers) _cn_visibleCharacters]_block_invoke
+ __cn_LTRControlCharacters.cn_once_object_4
+ __cn_LTRControlCharacters.cn_once_token_4
+ __cn_phoneNumberInvalidCharacters.cn_once_object_3
+ __cn_phoneNumberInvalidCharacters.cn_once_token_3
+ __cn_visibleCharacters.cn_once_object_2
+ __cn_visibleCharacters.cn_once_token_2
+ __cn_whitespaceExceptAscii32CharacterSet.cn_once_object_5
+ __cn_whitespaceExceptAscii32CharacterSet.cn_once_token_5
+ _expressBundleIdentifiers.cn_once_object_1
+ _expressBundleIdentifiers.cn_once_token_1
+ _inet_pton
+ _symbolic _____ 18ContactsFoundation13CNURLSecurityC
+ _symbolic _____Sg 10Foundation3URLV
+ _symbolic _____ySsG s23_ContiguousArrayStorageC
- -[CNEntitlementVerifier auditToken:allowsHighPriorityWithError:]
- -[CNEntitlementVerifier highPriorityBundleIdentifiers]
- -[CNEntitlementVerifier secTask:allowsHighPriorityWithError:]
- -[CNEntitlementVerifierTestDouble auditToken:allowsHighPriorityWithError:]
- -[CNEntitlementVerifierTestDouble setAuditToken:allowsHighPriority:]
- -[CNEntitlementVerifierTestDouble setAuditToken:allowsHighPriorityError:]
- ___54-[CNEntitlementVerifier highPriorityBundleIdentifiers]_block_invoke
- __cn_LTRControlCharacters.cn_once_object_3
- __cn_LTRControlCharacters.cn_once_token_3
- __cn_phoneNumberInvalidCharacters.cn_once_object_2
- __cn_phoneNumberInvalidCharacters.cn_once_token_2
- __cn_whitespaceExceptAscii32CharacterSet.cn_once_object_4
- __cn_whitespaceExceptAscii32CharacterSet.cn_once_token_4
- _highPriorityBundleIdentifiers.cn_once_object_1
- _highPriorityBundleIdentifiers.cn_once_token_1
CStrings:
+ "Poster Legibility"
+ "__isExpressAllowed__"
+ "poster_legibility"
- "__isHighPriorityAllowed__"
```
