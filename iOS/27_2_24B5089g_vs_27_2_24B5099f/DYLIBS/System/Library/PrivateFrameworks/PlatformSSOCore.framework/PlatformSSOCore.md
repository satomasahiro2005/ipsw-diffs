## PlatformSSOCore

> `/System/Library/PrivateFrameworks/PlatformSSOCore.framework/PlatformSSOCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x98550` | `0x99c18` | **`+0x16c8`** |
| `__AUTH_CONST.__cfstring` | `0x7c20` | `0x80c0` | **`+0x4a0`** |
| `__TEXT.__cstring` | `0xae78` | `0xb2a8` | **`+0x430`** |
| `__DATA_CONST.__objc_arraydata` | `0x58` | `0x120` | **`+0xc8`** |
| `__AUTH_CONST.__const` | `0xc60` | `0xce0` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d68` | `0x2dd0` | **`+0x68`** |
| `__DATA.__bss` | `0x791` | `0x7d1` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x2027` | `0x2067` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x21b0` | `0x21f0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x2600` | `0x2630` | **`+0x30`** |
| `__TEXT.__ustring` | `—` | `0x2c` | **`+0x2c`** |
| `__TEXT.__objc_methlist` | `0x6388` | `0x63b0` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x78` | `0x90` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x240` | `0x258` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x14e40` | `0x14e50` | **`+0x10`** |
| `__TEXT.__const` | `0x1a04` | `0x1a14` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xdc0` | `0xdb8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x9d0` | `0x9d8` | **`+0x8`** |

### Other Changes

```diff

-643.40.27.0.0
+643.40.34.0.0

-  Functions: 3869
-  Symbols:   5877
-  CStrings:  1775
+  Functions: 3894
+  Symbols:   5899
+  CStrings:  1814
Symbols:
+ +[POConstantCoreUtil validatedAdditionalHTTPHeaders:]
+ -[POAuthenticationProcess addAdditionalHTTPHeadersToRequest:context:]
+ -[PODeviceConfiguration additionalHTTPHeaders]
+ -[PODeviceConfiguration setAdditionalHTTPHeaders:]
+ GCC_except_table128
+ GCC_except_table153
+ GCC_except_table56
+ _OBJC_CLASS_$_NSCountedSet
+ _OBJC_IVAR_$_PODeviceConfiguration._additionalHTTPHeaders
+ _POIsReservedHTTPHeaderField.onceToken
+ _POIsReservedHTTPHeaderField.reservedFields
+ _POIsValidHTTPHeaderFieldName.illegalFieldCharacters
+ _POIsValidHTTPHeaderFieldName.onceToken
+ _POIsValidHTTPHeaderFieldValue.illegalValueCharacters
+ _POIsValidHTTPHeaderFieldValue.onceToken
+ _PO_LOG_POConstantCoreUtil
+ _PO_LOG_POConstantCoreUtil.log
+ _PO_LOG_POConstantCoreUtil.once
+ ___53+[POConstantCoreUtil validatedAdditionalHTTPHeaders:]_block_invoke
+ ___69-[POAuthenticationProcess addAdditionalHTTPHeadersToRequest:context:]_block_invoke
+ ___POAdditionalHTTPHeadersForDisplay_block_invoke
+ ___POIsReservedHTTPHeaderField_block_invoke
+ ___POIsValidHTTPHeaderFieldName_block_invoke
+ ___POIsValidHTTPHeaderFieldValue_block_invoke
+ ___PO_LOG_POConstantCoreUtil_block_invoke
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSString"8"NSString"16^B24ls32l8
+ _kPOErrorDomain
- -[POUserConfiguration newUser]
- GCC_except_table126
- GCC_except_table151
- _NSClassFromString
- _OBJC_IVAR_$_POUserConfiguration._newUser
CStrings:
+ "!#$%&'*+-.^_`|~"
+ "%@…%@ (%@ characters)"
+ "Added %{public}@ of %{public}@ additional HTTP headers to request: %{public}@"
+ "Additional HTTP header is already set on the request; not overwriting it."
+ "AdditionalHTTPHeaders entry is not a string pair; discarding it."
+ "AdditionalHTTPHeaders field collides with another entry that differs only in case; discarding all of them."
+ "AdditionalHTTPHeaders field is not a valid header name; discarding it."
+ "AdditionalHTTPHeaders field is reserved; discarding it."
+ "AdditionalHTTPHeaders is not a dictionary; ignoring it."
+ "AdditionalHTTPHeaders value is not a valid header value; discarding it."
+ "Headers: %@, Limit: %@"
+ "Missing device encryption key."
+ "Missing temporary account credential."
+ "POConstantCoreUtil"
+ "Too many entries in AdditionalHTTPHeaders; ignoring all of them."
+ "Unable to decrypt temporary account credential with the outgoing key; dropping entry."
+ "accept"
+ "accept-encoding"
+ "authentication-info"
+ "authorization"
+ "connection"
+ "content-encoding"
+ "content-length"
+ "content-type"
+ "cookie"
+ "cookie2"
+ "expect"
+ "host"
+ "keep-alive"
+ "proxy-authenticate"
+ "proxy-authentication-info"
+ "proxy-authorization"
+ "set-cookie"
+ "set-cookie2"
+ "soapaction"
+ "te"
+ "trailer"
+ "transfer-encoding"
+ "upgrade"
+ "www-authenticate"
- "XCTestCase"
```
