## storekitd

> `/System/Library/Frameworks/StoreKit.framework/Support/storekitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5cfba4` | `0x5d97d0` | **`+0x9c2c`** |
| `__DATA_CONST.__const` | `0x709f8` | `0x71ab8` | **`+0x10c0`** |
| `__TEXT.__cstring` | `0x1e675` | `0x1eec5` | **`+0x850`** |
| `__TEXT.__eh_frame` | `0x36eb0` | `0x375d0` | **`+0x720`** |
| `__TEXT.__swift5_capture` | `0x1ed54` | `0x1f3d8` | **`+0x684`** |
| `__TEXT.__unwind_info` | `0x16300` | `0x163f0` | **`+0xf0`** |
| `__DATA.__data` | `0x133b0` | `0x13450` | **`+0xa0`** |
| `__TEXT.__const` | `0x3f630` | `0x3f6c0` | **`+0x90`** |
| `__TEXT.__swift_as_cont` | `0x2e50` | `0x2eb8` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0xcb80` | `0xcbcc` | **`+0x4c`** |
| `__TEXT.__objc_stubs` | `0xc600` | `0xc640` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x73ff` | `0x743f` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x1e60` | `0x1e94` | **`+0x34`** |
| `__TEXT.__swift5_typeref` | `0xbe04` | `0xbe30` | **`+0x2c`** |
| `__TEXT.__constg_swiftt` | `0x9408` | `0x9430` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x4260` | `0x4280` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x11679` | `0x11699` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0xfe0` | `0xff8` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x43d8` | `0x43e8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2140` | `0x2150` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x18c0` | `0x18d0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xda0` | `0xda4` | **`+0x4`** |

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

-  Functions: 37795
-  Symbols:   1792
-  CStrings:  7125
+  Functions: 38086
+  Symbols:   1794
+  CStrings:  7167
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
+ "22:16:11"
+ "Aug  9 2026"
+ "Error retrieving short bundle version: "
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
- "06:23:00"
- "Aug 10 2026"
- "[ReviewManager] Review requests are not allowed in seed."
```
