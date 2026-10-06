## promotedcontentd

> `/usr/libexec/promotedcontentd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d8ec4` | `0x3dd98c` | **`+0x4ac8`** |
| `__DATA_CONST.__const` | `0x1c6c8` | `0x1c908` | **`+0x240`** |
| `__TEXT.__const` | `0x2b1da` | `0x2b3aa` | **`+0x1d0`** |
| `__TEXT.__auth_stubs` | `0x5bc0` | `0x5ce0` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x10edc` | `0x10fdc` | **`+0x100`** |
| `__TEXT.__cstring` | `0x15ce5` | `0x15dd5` | **`+0xf0`** |
| `__TEXT.__swift5_reflstr` | `0x3636` | `0x3726` | **`+0xf0`** |
| `__DATA.__objc_const` | `0x2b388` | `0x2b448` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x4970` | `0x4a24` | **`+0xb4`** |
| `__DATA.__data` | `0xe618` | `0xe6c8` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x42f4` | `0x43a0` | **`+0xac`** |
| `__TEXT.__objc_methname` | `0x26fed` | `0x2708d` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0x2df0` | `0x2e80` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x6400` | `0x6488` | **`+0x88`** |
| `__DATA.__bss` | `0xde40` | `0xdec0` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x1850` | `0x18b8` | **`+0x68`** |
| `__DATA_CONST.__auth_ptr` | `0x15c0` | `0x1608` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x1288` | `0x12bc` | **`+0x34`** |
| `__TEXT.__unwind_info` | `0x7148` | `0x7178` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0xf800` | `0xf7e0` | **`-0x20`** |
| `__TEXT.__swift5_builtin` | `0x154` | `0x168` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x5c0` | `0x5cc` | **`+0xc`** |
| `__DATA.__objc_data` | `0x9840` | `0x9848` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x848` | `0x850` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x120` | `0x124` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-557.1.24.0.0
+557.1.26.0.0

-  Functions: 11788
-  Symbols:   2298
-  CStrings:  11649
+  Functions: 11808
+  Symbols:   2297
+  CStrings:  11663
Symbols:
- _objc_retain_x10
CStrings:
+ "Attaching pageLayoutFinal %{public}@ to %{public}@ for content %{public}@"
+ "Attribution request received with nil timestamp (intervalId: %{public}llu); proceeding without it."
+ "DELETE FROM Tokens"
+ "Off"
+ "On"
+ "SELECT SUM(val) FROM (SELECT (slotVisibleAdCount + slotVisibleNoAdCount + impressionCount + clickCount + downloadCount + redownloadCount + preOrderPlacedCount + viewDownloadCount + viewRedownloadCount + viewPreorderPlacedCount) AS val FROM APDBExperimentationReport WHERE triggerRowId = ? AND source = ? AND adType = ? AND day IN (SELECT e.value FROM json_each('%@') e)%@)"
+ "Sending CoreAnalytics event '%s' with payload: %s"
+ "Stored attribution token does not match its key. Purging all stored tokens."
+ "account"
+ "actualBirthYearAvailable"
+ "applicationDiagnostics"
+ "com.apple.adplatforms.agenoising.application"
+ "initWithError:outcome:"
+ "initWithToken:tokenKey:outcome:"
+ "noisedBirthYearAvailable"
+ "retryDiagnostics"
+ "storefrontIDSource"
+ "userAgeNoisingStoreDiagnosticsDepot"
- "SELECT SUM(val) FROM (SELECT (slotVisibleAdCount + impressionCount + clickCount + downloadCount + redownloadCount + preOrderPlacedCount + viewDownloadCount + viewRedownloadCount + viewPreorderPlacedCount) AS val FROM APDBExperimentationReport WHERE triggerRowId = ? AND source = ? AND adType = ? AND day IN (SELECT e.value FROM json_each('%@') e)%@)"
- "attribution.timings"
- "initWithError:"
- "initWithToken:tokenKey:source:"
```
