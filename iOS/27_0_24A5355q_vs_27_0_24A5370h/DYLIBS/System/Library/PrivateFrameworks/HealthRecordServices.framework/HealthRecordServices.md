## HealthRecordServices

> `/System/Library/PrivateFrameworks/HealthRecordServices.framework/HealthRecordServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8c504` | `0x8e164` | **`+0x1c60`** |
| `__DATA.__bss` | `0x10880` | `0x10c00` | **`+0x380`** |
| `__TEXT.__cstring` | `0x4740` | `0x4959` | **`+0x219`** |
| `__AUTH_CONST.__const` | `0x43c0` | `0x45c8` | **`+0x208`** |
| `__TEXT.__const` | `0x8718` | `0x88bc` | **`+0x1a4`** |
| `__TEXT.__swift5_fieldmd` | `0x1930` | `0x19a4` | **`+0x74`** |
| `__AUTH_CONST.__objc_intobj` | `0x30` | `0x90` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0xb41` | `0xb9b` | **`+0x5a`** |
| `__TEXT.__constg_swiftt` | `0x16ec` | `0x1724` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0x180` | `0x1b0` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0xf0f` | `0xf34` | **`+0x25`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x86c` | `0x888` | **`+0x1c`** |
| `__AUTH_CONST.__objc_arrayobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x21b0` | `0x21c8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xd38` | `0xd48` | **`+0x10`** |
| `__DATA.__data` | `0x23a0` | `0x2390` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x575c` | `0x576c` | **`+0x10`** |
| `__AUTH.__data` | `0xc38` | `0xc40` | **`+0x8`** |
| `__DATA.__common` | `0x30` | `0x28` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x25c` | `0x264` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

+  - /System/Library/PrivateFrameworks/XPCDistributed.framework/XPCDistributed

-  Functions: 4228
-  Symbols:   4417
-  CStrings:  833
+  Functions: 4270
+  Symbols:   4425
+  CStrings:  850
Symbols:
+ +[HKMedicalDownloadableAttachment associatedHKAttachmentStatuses]
+ -[HKMedicalDownloadableAttachment hasAssociatedHKAttachment]
+ _OBJC_CLASS_$_NSConstantArray
+ _associated conformance 20HealthRecordServices10HTTPHeaderV11ContentTypeOSHAASQ
+ _associated conformance 20HealthRecordServices10HTTPHeaderV4NameOSHAASQ
+ _associated conformance 20HealthRecordServices15WebRequestErrorO10Foundation13CustomNSErrorAAs0F0
+ _symbolic _____ 20HealthRecordServices10HTTPHeaderV11ContentTypeO
+ _symbolic _____ 20HealthRecordServices10HTTPHeaderV4NameO
CStrings:
+ "Accept"
+ "Authorization"
+ "Content-Length"
+ "Content-Type"
+ "HealthRecordServices.WebRequestError"
+ "WebRequestError.ErrorCode"
+ "WebRequestError.HTTPStatus"
+ "WebRequestError.HTTPStatusCode"
+ "WebRequestError.InvalidBaseURL"
+ "WebRequestError.InvalidHTTPMethod"
+ "WebRequestError.InvalidURLComponents"
+ "WebRequestError.InvalidURLString"
+ "WebRequestError.NonHTTPURLResponse"
+ "WebRequestError.UnacceptableURL"
+ "application/json"
+ "application/x-www-form-urlencoded"
+ "health_records:assembler"
+ "q"
- "health_records:ips"
```
