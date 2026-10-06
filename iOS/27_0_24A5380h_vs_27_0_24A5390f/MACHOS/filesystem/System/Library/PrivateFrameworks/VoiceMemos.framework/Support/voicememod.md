## voicememod

> `/System/Library/PrivateFrameworks/VoiceMemos.framework/Support/voicememod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49920` | `0x454cc` | **`-0x4454`** |
| `__TEXT.__eh_frame` | `0x1b10` | `0x1910` | **`-0x200`** |
| `__TEXT.__oslogstring` | `0x32d8` | `0x31c8` | **`-0x110`** |
| `__TEXT.__unwind_info` | `0x1278` | `0x1218` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x25a0` | `0x2550` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0x1720` | `0x16d0` | **`-0x50`** |
| `__TEXT.__const` | `0xfe0` | `0xfa0` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x6bc8` | `0x6b88` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0x5e80` | `0x5e40` | **`-0x40`** |
| `__TEXT.__swift5_capture` | `0x428` | `0x3fc` | **`-0x2c`** |
| `__DATA_CONST.__auth_got` | `0xba0` | `0xb78` | **`-0x28`** |
| `__TEXT.__swift_as_cont` | `0xf4` | `0xd0` | **`-0x24`** |
| `__DATA.__data` | `0xc00` | `0xbf0` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1ae8` | `0x1ad8` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x687` | `0x67b` | **`-0xc`** |
| `__TEXT.__swift_as_ret` | `0x8c` | `0x80` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x798` | `0x790` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x88` | `0x80` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1433.0.0.0.0
+1435.0.0.0.0

-  Functions: 1341
-  Symbols:   720
-  CStrings:  1735
+  Functions: 1321
+  Symbols:   714
+  CStrings:  1726
Symbols:
- _$s10Foundation3URLVSQAAMc
- _$sSo13os_log_type_ta0A0E4infoABvgZ
- _RCApplicationAssetRecoveryDirectoryURL
- _RCApplicationAssetsDirectoryURL
- _RCMixDownRecoveryDirectoryURL
- _swift_bridgeObjectRelease_n
CStrings:
+ "+[RCComposition(OrphanHandling) _compositionByMergingInterruptedCapture:contentUpdated:]"
+ "moveOrphanedCaptureAssetsToRecoveryLocationsWithCompletionHandler:"
- "%s Failed to remove item at %s error - %@"
- "Failed to decode asset bundle -- error: %@"
- "Failed to mix down %s: %@"
- "Failed to resume interrupted mix downs"
- "Mixed down recovered assets for recording %s"
- "Recovered assets did not need mixing down"
- "compositionMetadataURLForBundleURL:"
- "contentsEqualAtPath:andPath:"
- "mixDown(recoveredAssetBundleURLs:)"
- "moveOrphanedApplicationAssetsToRecoveryLocationsWithCompletionHandler:"
- "submittedCompositionMetadata.plist"
```
