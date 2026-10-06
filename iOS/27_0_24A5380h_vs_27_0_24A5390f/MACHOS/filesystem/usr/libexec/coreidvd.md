## coreidvd

> `/usr/libexec/coreidvd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f45cc` | `0x6f61e0` | **`+0x1c14`** |
| `__TEXT.__eh_frame` | `0x47c28` | `0x47ef0` | **`+0x2c8`** |
| `__TEXT.__cstring` | `0x2a7c0` | `0x2a930` | **`+0x170`** |
| `__DATA.__data` | `0x182c8` | `0x18418` | **`+0x150`** |
| `__DATA.__objc_const` | `0x11710` | `0x11848` | **`+0x138`** |
| `__TEXT.__const` | `0x32a00` | `0x32b20` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x16098` | `0x16180` | **`+0xe8`** |
| `__TEXT.__constg_swiftt` | `0xda68` | `0xdb38` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x24f00` | `0x24fc0` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0xc11e` | `0xc1ae` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0xe5b8` | `0xe644` | **`+0x8c`** |
| `__DATA.__bss` | `0x38530` | `0x385b0` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x6424` | `0x64a0` | **`+0x7c`** |
| `__TEXT.__oslogstring` | `0x2e979` | `0x2e9e9` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0xdb36` | `0xdb96` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0x36ce` | `0x370e` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x37e0` | `0x3814` | **`+0x34`** |
| `__TEXT.__swift5_typeref` | `0xc10a` | `0xc124` | **`+0x1a`** |
| `__TEXT.__swift_as_entry` | `0x1314` | `0x1328` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0xd320` | `0xd310` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x1c40` | `0x1c4c` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x69a0` | `0x6998` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x2410` | `0x2418` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x42b8` | `0x42c0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x730` | `0x738` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xc2c` | `0xc34` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1e30` | `0x1e34` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-9.36.0.0.0
+9.38.0.0.0

-  Functions: 18844
+  Functions: 18890

-  CStrings:  8542
+  CStrings:  8560
Symbols:
+ _$s11CBORLibrary10COSE_Sign1V13CoreIDVSharedE19fromHexOrBinaryDataAC10Foundation0J0V_tKcfC
+ _$s7CoreIDV27MobileDocumentReaderSessionC5ErrorV4CodeO15documentExpiredyA2GmFWC
- _$s11CBORLibrary10COSE_Sign1V13CoreIDVSharedE11fromHexDataAC10Foundation0H0V_tKcfC
- _$s13CoreIDVShared26DaemonInternalDefaultsKeysO37enableTextUnderstandingVerboseLoggingSSvgZ
CStrings:
+ "\n- PDF417 firstName: "
+ "\n- PDF417 lastName: "
+ "\n- PDF417 postalCode: "
+ "\n- PDF417 state: "
+ "\n- PDF417 street1: "
+ "\n- TU fullAddress: "
+ "\n- TU lastName: "
+ "\n- TU postalCode: "
+ "\n- TU street (extracted): "
+ "IdentityProofingRequestManager: Attached TextUnderstanding metrics to proof-time documents (duration=%s, errorCode=%s, fuzzyMatch=%{bool}d)"
+ "IdentityProofingRequestManager: Cancelled previous TextUnderstanding task"
+ "IdentityProofingRequestManager: PDF417 decode failed for TextUnderstanding: %s"
+ "IdentityProofingRequestManager: Scheduled TextUnderstanding comparison from prepare (runs parallel with review)"
+ "IdentityProofingRequestManager: TextUnderstanding (prepare path) cancelled; not stashing result"
+ "IdentityProofingRequestManager: TextUnderstanding (prepare path) timed out or failed: %s. Continuing without result."
+ "IdentityProofingRequestManager: TextUnderstanding comparison in progress at proof time; metrics not attached"
+ "IdentityProofingRequestManager: TextUnderstanding result available but failed to attach to proof-time corrected_id_front capture metrics"
+ "TextUnderstandingIDComparator: Raw values before comparison\n- TU firstName: "
+ "_TtC8coreidvd38TextUnderstandingComparisonCoordinator"
+ "comparisonTask"
+ "generation"
+ "isComparisonRunning"
+ "pendingResult"
+ "textUnderstandingComparisonCoordinator"
- "IdentityProofingRequestManager: Cancelled previous Text Understanding task"
- "IdentityProofingRequestManager: PDF417 decode failed for Text Understanding: %s"
- "IdentityProofingRequestManager: Scheduled Text Understanding comparison from prepare (runs parallel with review)"
- "IdentityProofingRequestManager: Text Understanding (prepare path) timed out or failed: %s. Continuing without result."
- "TextUnderstandingIDComparator: Raw values before comparison\n- TU firstName: %{private}s\n- PDF417 firstName: %{private}s\n- TU lastName: %{private}s\n- PDF417 lastName: %{private}s\n- TU state: %{private}s\n- PDF417 state: %{private}s\n- TU address (fullAddress): %{private}s\n- PDF417 street1: %{private}s\n- TU postalCode: %{private}s\n- PDF417 postalCode: %{private}s"
- "textUnderstandingComparisonTask"
```
