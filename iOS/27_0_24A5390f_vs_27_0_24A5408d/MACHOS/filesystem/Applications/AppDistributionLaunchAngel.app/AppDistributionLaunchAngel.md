## AppDistributionLaunchAngel

> `/Applications/AppDistributionLaunchAngel.app/AppDistributionLaunchAngel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c82c` | `0x4d6c0` | **`+0xe94`** |
| `__DATA_CONST.__const` | `0x1ae8` | `0x1bd8` | **`+0xf0`** |
| `__TEXT.__const` | `0x1a34` | `0x1ab4` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x33a9` | `0x3429` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x654` | `0x6c8` | **`+0x74`** |
| `__TEXT.__eh_frame` | `0x1e60` | `0x1eb0` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x1780` | `0x17c0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xec8` | `0xf00` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0xb84` | `0xbaa` | **`+0x26`** |
| `__DATA.__objc_selrefs` | `0xb60` | `0xb70` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2180` | `0x2190` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x1b50` | `0x1b40` | **`-0x10`** |
| `__DATA.__data` | `0x1d08` | `0x1d10` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x10d0` | `0x10d8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x608` | `0x600` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x8c` | `0x94` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x1a4` | `0x1a8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xbc` | `0xc0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-4.0.39.0.0
+4.0.44.0.0

-  Functions: 1101
-  Symbols:   889
-  CStrings:  856
+  Functions: 1123
+  Symbols:   891
+  CStrings:  858
Symbols:
+ _$s14MarketplaceKit45ConfirmationSheetInstallProgressConfigurationV16resumeButtonTextSSvg
+ _$sBbWV
CStrings:
+ "Primary button pressed again, toggling pause/resume of app install progress"
+ "[%s] Can not pause/resume app install progress because app or progress not found"
+ "[%s] Pause/resume requested but no action can be taken"
+ "installProgressKVOTokens"
+ "performWithoutAnimation:"
+ "resumeMetadata:"
- "Primary button pressed again, but can not pause/resume app install progress because app or progress not found"
- "Primary button pressed again, pausing/resuming app install progress"
- "[%s] Progress button pressed but no action can be taken"
- "installProgressKVOToken"
```
