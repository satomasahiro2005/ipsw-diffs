## linkd

> `/usr/libexec/linkd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0xa070` | `0x9b20` | **`-0x550`** |
| `__TEXT.__text` | `0xca3f4` | `0xc9f8c` | **`-0x468`** |
| `__TEXT.__swift5_capture` | `0x3148` | `0x2f30` | **`-0x218`** |
| `__TEXT.__oslogstring` | `0x4e23` | `0x4ef6` | **`+0xd3`** |
| `__TEXT.__cstring` | `0x1c15` | `0x1c80` | **`+0x6b`** |
| `__TEXT.__swift5_reflstr` | `0x12d7` | `0x1325` | **`+0x4e`** |
| `__DATA_CONST.__auth_ptr` | `0x13d8` | `0x1420` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0xa328` | `0xa370` | **`+0x48`** |
| `__TEXT.__const` | `0x5c76` | `0x5c3c` | **`-0x3a`** |
| `__DATA.__data` | `0x3b58` | `0x3b90` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x16d0` | `0x16e8` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x91e` | `0x90c` | **`-0x12`** |
| `__TEXT.__objc_methname` | `0x3fbd` | `0x3fcd` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3d08` | `0x3d00` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x1887` | `0x188b` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x754` | `0x758` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x590` | `0x594` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x55c` | `0x560` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-301.1.10.2.101
+301.1.15.0.0

-  Functions: 5602
-  Symbols:   1198
-  CStrings:  1232
+  Functions: 5593
+  Symbols:   1199
+  CStrings:  1235
Symbols:
+ _$s15AppIntentsIndex08MetadataC0V020processedBundlesWithA9ShortcutsSaySSGyKF
+ _$s15AppIntentsIndex08MetadataC0V23appShortcutsUnprocessed3forSbSS_tKF
- _$s15AppIntentsIndex08MetadataC0V21appShortcutsProcessedySbSSKF
CStrings:
+ "AppShortcuts for %{public}s does not need processing, unblocking"
+ "Emitting adoption summary: indexedBundles=%ld appShortcutBundles=%ld thirdPartyIndexedBundles=%ld thirdPartyAppShortcutBundles=%ld"
+ "EntitlementAudit: %{public}s (pid %{public}d) lacks both %{public}s and %{public}s, would be REJECTED (enforcement off)"
+ "thirdPartyAppShortcutBundleCount"
+ "thirdPartyIndexedBundleCount"
- "AppShortcuts for %{public}s appear processed, unblocking"
- "Emitting adoption summary: indexedBundles=%ld appShortcutBundles=%ld"
```
