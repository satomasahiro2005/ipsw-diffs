## linkd

> `/usr/libexec/linkd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ac550` | `0x1ad0c4` | **`+0xb74`** |
| `__TEXT.__unwind_info` | `0x7f90` | `0x7bb0` | **`-0x3e0`** |
| `__DATA_CONST.__const` | `0x10b68` | `0x10c38` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x42af` | `0x436f` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x3870` | `0x3900` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x5a8f` | `0x5aff` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x159bc` | `0x15a1c` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x1c40` | `0x1c88` | **`+0x48`** |
| `__DATA.__data` | `0x6f30` | `0x6f70` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x5140` | `0x517c` | **`+0x3c`** |
| `__TEXT.__const` | `0xa160` | `0xa130` | **`-0x30`** |
| `__TEXT.__objc_methname` | `0x5aad` | `0x5acd` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x3a20` | `0x3a00` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x2710` | `0x2728` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x2298` | `0x22a8` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0xb1b` | `0xb2b` | **`+0x10`** |
| `__DATA.__common` | `0xf60` | `0xf58` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x13e8` | `0x13e0` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0xb60` | `0xb68` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x4a14` | `0x4a1a` | **`+0x6`** |
| `__TEXT.__swift_as_entry` | `0xa78` | `0xa7c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xa3c` | `0xa40` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-301.0.42.7.0
+301.0.43.6.0

-  Functions: 11045
-  Symbols:   1696
-  CStrings:  1788
+  Functions: 11054
+  Symbols:   1706
+  CStrings:  1794
Symbols:
+ _$s12LinkMetadata0aB7VersionO07currentC0SSvgZ
+ _$s12LinkMetadata17UniqueBundleCacheC3urlSo8NSBundleCSg10Foundation3URLV_tcig
+ _$s12LinkMetadata17UniqueBundleCacheC5labelACSS_tcfc
+ _$s12LinkMetadata17UniqueBundleCacheCMa
+ _$s12LinkMetadata17UniqueBundleCacheCMn
+ _$s15AppIntentsIndex08MetadataC0V011interpolateA22ShortcutsForNextBundle11bundleCacheSSSg04LinkD006UniqueiK0C_tKF
+ _$s15AppIntentsIndex08MetadataC0V07processD13ForNextBundle11bundleCache08prebuiltD8Providers6ResultOySSAA0H15IndexingFailureVGSg04LinkD006UniquehJ0C_AM08PrebuiltdL0_pSgtKF
+ _$s15AppIntentsIndex08MetadataC0V13releaseMemory3nowySb_tF
+ _$sSo18OS_dispatch_sourceC8DispatchE19MemoryPressureEventV7warningAEvgZ
+ _$sSo18OS_dispatch_sourceC8DispatchE19MemoryPressureEventV8criticalAEvgZ
+ _$sSo18OS_dispatch_sourceC8DispatchE19MemoryPressureEventVMa
+ _$sSo18OS_dispatch_sourceC8DispatchE19MemoryPressureEventVMn
+ _$sSo18OS_dispatch_sourceC8DispatchE19MemoryPressureEventVs10SetAlgebraACMc
+ _$sSo18OS_dispatch_sourceC8DispatchE24makeMemoryPressureSource9eventMask5queueSo0a1_b1_C15_memorypressure_pAbCE0fG5EventV_So0a1_b1_K0CSgtFZ
- _$s15AppIntentsIndex08MetadataC0V011interpolateA22ShortcutsForNextBundleSSSgyKF
- _$s15AppIntentsIndex08MetadataC0V07processD13ForNextBundle08prebuiltD8Providers6ResultOySSAA0H15IndexingFailureVGSg04LinkD008PrebuiltdJ0_pSg_tKF
- _kCFBundleVersionKey
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "DaemonMemoryPressure"
+ "DonateAppShortcutsForAllApplications"
+ "Received memory pressure event, releasing memory"
+ "Registry.refreshAutoShortcutSubstitution"
+ "Registry.registerBundle"
+ "Registry.unregisterBundle"
+ "Unable to map %{public}s to a LSBundleRecord"
+ "localizedStringForLocaleIdentifier:uniqueBundle:"
- "mainBundle"
- "objectForInfoDictionaryKey:"
```
