## SwiftMLS

> `/System/Library/PrivateFrameworks/SwiftMLS.framework/SwiftMLS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29f770` | `0x2acdac` | **`+0xd63c`** |
| `__TEXT.__eh_frame` | `0x1f428` | `0x20130` | **`+0xd08`** |
| `__TEXT.__unwind_info` | `0xa038` | `0xa3e0` | **`+0x3a8`** |
| `__AUTH_CONST.__const` | `0xc6d8` | `0xc950` | **`+0x278`** |
| `__TEXT.__const` | `0x24ad0` | `0x24d08` | **`+0x238`** |
| `__TEXT.__cstring` | `0x3d2d` | `0x3e6d` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x6028` | `0x6108` | **`+0xe0`** |
| `__TEXT.__swift_as_cont` | `0x150c` | `0x15c0` | **`+0xb4`** |
| `__TEXT.__swift5_reflstr` | `0x59e1` | `0x5a91` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x484c` | `0x48e0` | **`+0x94`** |
| `__TEXT.__swift5_fieldmd` | `0x5f04` | `0x5f94` | **`+0x90`** |
| `__TEXT.__swift_as_ret` | `0xb80` | `0xc0c` | **`+0x8c`** |
| `__AUTH.__data` | `0x4a08` | `0x4a48` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0x5e0` | `0x618` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x3886` | `0x38aa` | **`+0x24`** |
| `__TEXT.__swift5_capture` | `0x284` | `0x2a4` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x18c0` | `0x18d0` | **`+0x10`** |
| `__DATA.__data` | `0x3388` | `0x3398` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x6a8` | `0x6b4` | **`+0xc`** |

### Other Changes

```diff

-330.0.0.0.0
+341.0.4.0.0

-  - /usr/lib/libboringssl.dylib

-  Functions: 10308
-  Symbols:   2098
-  CStrings:  807
+  Functions: 10469
+  Symbols:   2107
+  CStrings:  817
Symbols:
+ _objc_retain_x24
+ _symbolic ShySSG
+ _symbolic _____ 8SwiftMLS0B0O29SignedEncryptionIdentityProofV
+ _symbolic _____ 8SwiftMLS0B0O5GroupOADC08ValidateC12MembersInputV
+ _symbolic _____ 8SwiftMLS0B0O5GroupOADC08ValidateC13MembersOutputV
+ _symbolic _____m 8SwiftMLS0B0O21VerifiableDisplayImdnV
+ _symbolic _____m 8SwiftMLS0B0O22VerifiableDeliveryImdnV
+ _symbolic _____m 8SwiftMLS0B0O23VerifiableResentMessageV
+ _type_layout_string 8SwiftMLS0B0O29SignedEncryptionIdentityProofV
+ _type_layout_string 8SwiftMLS0B0O5GroupOADC08ValidateC13MembersOutputV
+ _type_layout_string SaySo17SecCertificateRefaG12certificates_t
- _swift_release_x12
- _symbolic _____y_____G s15CollectionOfOneV s5UInt8V
CStrings:
+ "%s: Added member failed checkCredentialDates validation"
+ "%s: Credential will expire within 30 days"
+ "%s: Generating private group info extensions with continuityToken extension"
+ "%s: Generating private group info extensions with fileInfoForGroupSubject extension"
+ "%s: validateGroupMembers failed { unexpected: %s, missing: %s, unauthorized: %s }"
+ "%s: validateGroupMembers trust evaluation failed for %s: %@"
+ "Added icon key extension to private group info extensions"
+ "Added subject key extension to private group info extensions"
+ "decryptGroupMetadataKeys(_:)"
+ "processIncomingCommit(message:)"
+ "processIncomingCommit(message:readdedWelcome:)"
+ "processIncomingCommitList(message:)"
+ "processIncomingCommitList(message:readdedWelcome:)"
+ "processIncomingProposalList(message:)"
+ "validateGroupMembers is unimplemented"
+ "validateGroupMembers(_:)"
- "%s: Added member failed isValidMember validation"
- "%s: Generating group info extensions with continuityToken extension"
- "%s: Generating group info extensions with fileInfoForGroupSubject extension"
- "Added icon key extension to group info extensions"
- "Added subject key extension to group info extensions"
- "_decryptGroupMetadataKeys(_:)"
```
