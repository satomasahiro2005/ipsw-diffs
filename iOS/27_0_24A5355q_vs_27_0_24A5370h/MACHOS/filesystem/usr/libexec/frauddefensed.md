## frauddefensed

> `/usr/libexec/frauddefensed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd472c` | `0xd2bac` | **`-0x1b80`** |
| `__DATA_CONST.__const` | `0x5e60` | `0x5f68` | **`+0x108`** |
| `__TEXT.__eh_frame` | `0xa640` | `0xa540` | **`-0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x2868` | `0x295c` | **`+0xf4`** |
| `__TEXT.__const` | `0x78b4` | `0x799c` | **`+0xe8`** |
| `__TEXT.__auth_stubs` | `0x2450` | `0x2530` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x2390` | `0x2458` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0x3628` | `0x3598` | **`-0x90`** |
| `__DATA.__bss` | `0x8030` | `0x80b0` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0x1230` | `0x12a0` | **`+0x70`** |
| `__TEXT.__cstring` | `0x9e2b` | `0x9e9b` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0xa20` | `0x9b8` | **`-0x68`** |
| `__DATA.__data` | `0x4448` | `0x4488` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x4e8` | `0x4b8` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1ef3` | `0x1f21` | **`+0x2e`** |
| `__TEXT.__swift_as_entry` | `0x304` | `0x2d8` | **`-0x2c`** |
| `__DATA.__objc_const` | `0x1f60` | `0x1f80` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x620` | `0x640` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x738` | `0x750` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x78` | `0x8c` | **`+0x14`** |
| `__TEXT.__swift5_typeref` | `0x1d44` | `0x1d30` | **`-0x14`** |
| `__TEXT.__swift_as_cont` | `0x9b0` | `0x99c` | **`-0x14`** |
| `__TEXT.__objc_methname` | `0x1672` | `0x1662` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x474` | `0x480` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x290` | `0x29c` | **`+0xc`** |
| `__TEXT.__swift5_protos` | `0x60` | `0x64` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-89.0.0.0.0
+92.0.0.0.0

-  Functions: 3411
-  Symbols:   910
-  CStrings:  1043
+  Functions: 3371
+  Symbols:   928
+  CStrings:  1044
Symbols:
+ _$s27IntelligencePlatformLibrary0C0O7StreamsO8TrustKitO11DecisioningO30TKWalletOrderExtractionDomainsOAA14StreamResourceAAMc
+ _$s27IntelligencePlatformLibrary0C0O7StreamsO8TrustKitO11DecisioningO30TKWalletOrderExtractionDomainsOMa
+ _$s27IntelligencePlatformLibrary38TrustKitTKWalletOrderExtractionDomainsV10recordZoneSSSgvs
+ _$s27IntelligencePlatformLibrary38TrustKitTKWalletOrderExtractionDomainsV10uafVersionSSSgvs
+ _$s27IntelligencePlatformLibrary38TrustKitTKWalletOrderExtractionDomainsV11matchStatusSSvs
+ _$s27IntelligencePlatformLibrary38TrustKitTKWalletOrderExtractionDomainsV13recordVersionSSSgvs
+ _$s27IntelligencePlatformLibrary38TrustKitTKWalletOrderExtractionDomainsV14deviceLanguageSSvs
+ _$s27IntelligencePlatformLibrary38TrustKitTKWalletOrderExtractionDomainsV6domainSSvs
+ _$s27IntelligencePlatformLibrary38TrustKitTKWalletOrderExtractionDomainsV6localeSSvs
+ _$s27IntelligencePlatformLibrary38TrustKitTKWalletOrderExtractionDomainsV8recordIdSSSgvs
+ _$s27IntelligencePlatformLibrary38TrustKitTKWalletOrderExtractionDomainsVAA9BuildableAAWP
+ _$s27IntelligencePlatformLibrary38TrustKitTKWalletOrderExtractionDomainsVMa
+ _$s2os21OSAllocatedUnfairLockVMn
+ _$sSh11descriptionSSvg
+ _$sSy10FoundationE23removingPercentEncodingSSSgvg
+ _$ss13ManagedBufferCMn
+ _$ss5print_9separator10terminatoryypd_S2StF
+ _objc_retain_x10
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
- _objc_release_x9
- _objc_retain_x11
CStrings:
+ "Donated Biome event. { event="
+ "Failed to submit analytics event. { error="
+ "Message type may not contain decision info. { messageType="
+ "Skipping Biome analytics. { event="
+ "allowlist"
- "$__lazy_storage_$_allowlist"
- "$__lazy_storage_$_attestationManager"
- "Attempted to donate Biome event. { didSubmit="
- "Skipping Biome analytics."
```
