## CoreIDVShared

> `/System/Library/PrivateFrameworks/CoreIDVShared.framework/CoreIDVShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x243468` | `0x23f8b8` | **`-0x3bb0`** |
| `__TEXT.__eh_frame` | `0xf1e0` | `0xef20` | **`-0x2c0`** |
| `__AUTH_CONST.__const` | `0x17180` | `0x16ef0` | **`-0x290`** |
| `__DATA.__bss` | `0x30e80` | `0x30d00` | **`-0x180`** |
| `__TEXT.__const` | `0x2db34` | `0x2da04` | **`-0x130`** |
| `__TEXT.__cstring` | `0x16d6e` | `0x16c7e` | **`-0xf0`** |
| `__TEXT.__swift5_capture` | `0x2050` | `0x1f6c` | **`-0xe4`** |
| `__TEXT.__swift5_reflstr` | `0x14a36` | `0x14b16` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x4a00` | `0x4940` | **`-0xc0`** |
| `__TEXT.__unwind_info` | `0x9428` | `0x9370` | **`-0xb8`** |
| `__TEXT.__swift5_typeref` | `0x6f10` | `0x6e9c` | **`-0x74`** |
| `__TEXT.__swift_as_cont` | `0x944` | `0x90c` | **`-0x38`** |
| `__TEXT.__constg_swiftt` | `0x6c6c` | `0x6c40` | **`-0x2c`** |
| `__TEXT.__swift5_fieldmd` | `0xd010` | `0xd03c` | **`+0x2c`** |
| `__TEXT.__objc_methlist` | `0x1b4c` | `0x1b24` | **`-0x28`** |
| `__DATA.__data` | `0x6ed8` | `0x6eb8` | **`-0x20`** |
| `__TEXT.__swift_as_entry` | `0x4e0` | `0x4c4` | **`-0x1c`** |
| `__TEXT.__swift_as_ret` | `0x4d8` | `0x4bc` | **`-0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0xa88` | `0xa70` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0xf48` | `0xf30` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x1970` | `0x1964` | **`-0xc`** |
| `__AUTH_CONST.__objc_const` | `0x6c10` | `0x6c08` | **`-0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x2cb0` | `0x2ca8` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x9d0` | `0x9cc` | **`-0x4`** |

### Other Changes

```diff

-9.42.0.0.0
+9.104.0.0.0

-  Functions: 14018
-  Symbols:   4100
-  CStrings:  2657
+  Functions: 13956
+  Symbols:   4089
+  CStrings:  2645
Symbols:
+ ___swift_closure_destructor.201Tm
+ ___swift_closure_destructor.210Tm
+ ___swift_closure_destructor.225Tm
+ ___swift_closure_destructor.285Tm
+ ___swift_closure_destructor.570Tm
+ ___swift_closure_destructor.585Tm
- +[AppleIDVClient appleIDVPersistModifiedACLBlob:withReferenceACLBlob:withLAContextData:intoBlob:returnBioUUIDs:]
- +[AppleIDVClient appleIDVPersistModifiedSESlot:withReferenceBlob:withLAContextData:intoBlob:]
- _OUTLINED_FUNCTION_71
- _OUTLINED_FUNCTION_72
- _OUTLINED_FUNCTION_73
- ___swift_closure_destructor.208Tm
- ___swift_closure_destructor.217Tm
- ___swift_closure_destructor.232Tm
- ___swift_closure_destructor.292Tm
- ___swift_closure_destructor.457Tm
- ___swift_closure_destructor.592Tm
- ___swift_closure_destructor.607Tm
- _associated conformance 13CoreIDVShared11UIAnalyticsC34BiometricBindingReplacementOutcomeOSHAASQ
- _symbolic ScCySay_____G______pG 10Foundation4UUIDV s5ErrorP
- _symbolic So7NSArrayCSgSo7NSErrorCSgIeyByy_
- _symbolic _____ 13CoreIDVShared11UIAnalyticsC34BiometricBindingReplacementOutcomeO
- _symbolic ______pSay_____G______pIeghHnrzo_ 13CoreIDVShared28IdentityManagementUIProtocolP 10Foundation4UUIDV s5ErrorP
CStrings:
+ "245 Main Street, Phoenix, AZ 85254, USA"
+ "debug.disable-selfie-orientation-restrictions"
+ "debug.mobile-document-reader.disable-filter-vical-by-document-type"
+ "〇〇県△△市⬜︎⬜︎町１ー２ー３"
- "AppleIDVManager persistModifiedACLBlob"
- "appleIDV.persistModifiedACL"
- "appleIDV.persistModifiedACLBlob"
- "appleIDV.persistModifiedSESlot"
- "appleIDVPersistModifiedACLBlob returned success but did not return data"
- "authFailed"
- "bioLockout"
- "com.apple.CoreIDVUI.biometricReplaced"
- "debug.mobile-document-reader.filter-vical-by-document-type"
- "error from appleIDVPersistModifiedACLBlob"
- "persistModifiedACLBlob(_:referenceACLBlob:externalizedLAContext:)"
- "replaced"
- "sendBiometricReplacedEvent authType = %s, outcome = %s, target = %lld"
- "wrongFinger"
- "〇〇県△△市⬜︎⬜︎町１−２−３"
- "平成12年1月1日"
```
