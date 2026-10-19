## storekitd

> `/System/Library/Frameworks/StoreKit.framework/Support/storekitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5dbc44` | `0x5e55c0` | **`+0x997c`** |
| `__DATA_CONST.__const` | `0x71198` | `0x72248` | **`+0x10b0`** |
| `__TEXT.__cstring` | `0x1eb45` | `0x1f395` | **`+0x850`** |
| `__TEXT.__eh_frame` | `0x37808` | `0x37ec0` | **`+0x6b8`** |
| `__TEXT.__swift5_capture` | `0x1eff8` | `0x1f67c` | **`+0x684`** |
| `__TEXT.__unwind_info` | `0x16518` | `0x16ae8` | **`+0x5d0`** |
| `__DATA.__data` | `0x13550` | `0x135f0` | **`+0xa0`** |
| `__TEXT.__const` | `0x3f8b0` | `0x3f930` | **`+0x80`** |
| `__TEXT.__swift_as_cont` | `0x2f1c` | `0x2f84` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0xcc18` | `0xcc64` | **`+0x4c`** |
| `__TEXT.__objc_stubs` | `0xc5e0` | `0xc620` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x749f` | `0x74df` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x1ed0` | `0x1f04` | **`+0x34`** |
| `__TEXT.__swift5_typeref` | `0xbe10` | `0xbe3c` | **`+0x2c`** |
| `__TEXT.__constg_swiftt` | `0x949c` | `0x94c4` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x4370` | `0x4390` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x11759` | `0x11779` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x100c` | `0x1024` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x4400` | `0x4410` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x21c8` | `0x21d8` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x18e0` | `0x18f0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xda8` | `0xdac` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-  Functions: 38160
-  Symbols:   1815
-  CStrings:  7152
+  Functions: 38406
+  Symbols:   1817
+  CStrings:  7194
Symbols:
+ _$s10Foundation4DateV12timeInterval5sinceACSd_ACtcfC
+ _$s10Foundation4DateV7compareySo18NSComparisonResultVACF
CStrings:
+ " existing entries"
+ " review entries from database"
+ ", latest rating allowed: "
+ ", requestsPerWindowLimit: "
+ ", requireNewVersionAfterReview: "
+ ", requiredDaysAfterReview: "
+ "01:00:01"
+ "Error retrieving short bundle version: "
+ "Oct  8 2026"
+ "UseSandboxReviewPromptModeForSystemApps"
+ "[ReviewManager] Creating database entry for review token"
+ "[ReviewManager] Failed to check for ad-hoc signing: "
+ "[ReviewManager] Fetching review constants from bag"
+ "[ReviewManager] Forcing sandbox for ad-hoc signed app"
+ "[ReviewManager] Forcing sandbox for system app"
+ "[ReviewManager] Generating review token for bundle: "
+ "[ReviewManager] Querying review entries for bundle: "
+ "[ReviewManager] Retrieved "
+ "[ReviewManager] Successfully generated review token: "
+ "[ReviewManager] System: "
+ "[ReviewManager] Token generation complete, returning token"
+ "[ReviewManager] Using bag value for requestLimitWindow: "
+ "] Determining whether to generate review token for bundle: "
+ "] Error generating review token: "
+ "] Evaluating review eligibility with "
+ "] Failed to insert review request entry in database"
+ "] Rejecting review request because there is no account."
+ "] Retrieved review constants - requestLimitWindow: "
+ "] Review request rejected based on eligibility criteria"
+ "] Review request rejected because requests per window limit reached."
+ "] Review request rejected because the user has already rated this version."
+ "] Review request rejected because the user has rated past the last rating allowed date."
+ "] Review window: "
+ "] Using bag value for requestsPerWindowLimit: "
+ "] Using bag value for requireNewVersionAfterReview: "
+ "] Using bag value for requiredDaysAfterReview: "
+ "] Using default value for requestLimitWindow: "
+ "] Using default value for requestsPerWindowLimit: "
+ "] Using default value for requireNewVersionAfterReview: "
+ "] Using default value for requiredDaysAfterReview: "
+ "]: Creating review entry"
+ "]: Getting review entries"
+ "]: Invalid review entry "
+ "isAdHocCodeSigned"
+ "shortVersionString"
- "02:08:05"
- "Oct  4 2026"
- "[ReviewManager] Review requests are not allowed in seed."
```
