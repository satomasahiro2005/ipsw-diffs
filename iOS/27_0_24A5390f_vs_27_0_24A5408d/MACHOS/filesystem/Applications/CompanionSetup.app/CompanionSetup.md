## CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa03b4` | `0xa1f40` | **`+0x1b8c`** |
| `__DATA_CONST.__const` | `0x8428` | `0x85e8` | **`+0x1c0`** |
| `__TEXT.__eh_frame` | `0x4570` | `0x4680` | **`+0x110`** |
| `__TEXT.__swift5_capture` | `0x3118` | `0x3200` | **`+0xe8`** |
| `__TEXT.__const` | `0x3694` | `0x3714` | **`+0x80`** |
| `__TEXT.__cstring` | `0x3b9a` | `0x3c1a` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x17d0` | `0x1804` | **`+0x34`** |
| `__TEXT.__unwind_info` | `0x1f80` | `0x1fb0` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x18d6` | `0x1904` | **`+0x2e`** |
| `__DATA_CONST.__got` | `0xd78` | `0xd90` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x464` | `0x47c` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x750` | `0x758` | **`+0x8`** |
| `__TEXT.__swift5_fieldmd` | `0x12c8` | `0x12c0` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x1a0` | `0x1a8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x18c` | `0x194` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x190` | `0x198` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x3c` | `0x40` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-524.0.38.0.0
+524.0.56.0.0

-  Functions: 2448
-  Symbols:   1261
-  CStrings:  1405
+  Functions: 2472
+  Symbols:   1264
+  CStrings:  1409
Symbols:
+ _$s17CompanionSetupKit16CSKStepPreflightC5EventO18wifi5GHzConsentAskyAESS_tcAEmFWC
+ _$s17CompanionSetupKit16CSKStepPreflightC7CommandO21wifi5GHzConsentAnsweryAESb_tcAEmFWC
+ _$s17CompanionSetupKit21CSKSetupAppleTVClientC7UIStateC5PhaseO15wifi5GHzConsentyAGSS_tcAGmFWC
CStrings:
+ "WIFI_ALLOW_5GHZ_ALLOW"
+ "WIFI_ALLOW_5GHZ_DETAIL"
+ "WIFI_ALLOW_5GHZ_TITLE"
+ "WIFI_ALLOW_5GHZ_USE_6GHZ_ONLY"
```
