## toolkitd

> `/usr/libexec/toolkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa3138` | `0xa32e8` | **`+0x1b0`** |
| `__TEXT.__objc_stubs` | `0x1880` | `0x1a20` | **`+0x1a0`** |
| `__TEXT.__const` | `0x482c` | `0x46bc` | **`-0x170`** |
| `__TEXT.__objc_methname` | `0x11a8` | `0x12e8` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x4480` | `0x4350` | **`-0x130`** |
| `__TEXT.__oslogstring` | `0x17dc` | `0x18fc` | **`+0x120`** |
| `__DATA.__objc_const` | `0x7f0` | `0x738` | **`-0xb8`** |
| `__TEXT.__constg_swiftt` | `0xde8` | `0xd38` | **`-0xb0`** |
| `__DATA.__data` | `0x1d68` | `0x1cc0` | **`-0xa8`** |
| `__TEXT.__swift5_fieldmd` | `0x1158` | `0x10b4` | **`-0xa4`** |
| `__DATA.__bss` | `0x2520` | `0x24a0` | **`-0x80`** |
| `__DATA.__objc_selrefs` | `0x6b0` | `0x718` | **`+0x68`** |
| `__TEXT.__cstring` | `0x226d` | `0x221d` | **`-0x50`** |
| `__TEXT.__swift5_reflstr` | `0x10d3` | `0x1084` | **`-0x4f`** |
| `__TEXT.__eh_frame` | `0x5f48` | `0x5f00` | **`-0x48`** |
| `__DATA_CONST.__auth_ptr` | `0x798` | `0x758` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x1f20` | `0x1ee8` | **`-0x38`** |
| `__TEXT.__swift5_typeref` | `0x183d` | `0x1807` | **`-0x36`** |
| `__TEXT.__objc_classname` | `0x1ad` | `0x17d` | **`-0x30`** |
| `__DATA_CONST.__got` | `0xc00` | `0xc18` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x158` | `0x148` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x38` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x1cc` | `0x1c4` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x2c` | `0x28` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x410` | `0x40c` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x1e0` | `0x1dc` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x228` | `0x224` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-5037.109.0.0.0
+5110.0.8.0.0

-  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 2985
-  Symbols:   1277
-  CStrings:  580
+  Functions: 2966
+  Symbols:   1275
+  CStrings:  593
Symbols:
+ _$s10Foundation10NSNotFoundSivg
+ _$s10Foundation25NSFastEnumerationIteratorVStAAMc
+ _$s11WorkflowKit16ContainerIndexerC09IndexableC8MetadataO16bundleIdentifieryAESS_04ToolB00C10DefinitionV0C4TypeOSgSSSgtcAEmFWC
+ _$s7ToolKit0A8DatabaseC26checkpointWALAfterIndexingyyYaKF
+ _$s7ToolKit0A8DatabaseC26checkpointWALAfterIndexingyyYaKFTu
+ _$s7ToolKit12TypeInstanceO20collectionIfMultiple12isCollectionACSb_tF
+ _$sSa10FoundationE19_bridgeToObjectiveCSo7NSArrayCyF
+ _$sSo7NSArrayC10FoundationE12makeIteratorAC017NSFastEnumerationD0VyF
+ _$sSt4next7ElementQzSgyFTj
+ _$ss15_print_unlockedyyx_q_zts16TextOutputStreamR_r0_lF
+ _$ss26DefaultStringInterpolationVN
+ _$ss26DefaultStringInterpolationVs16TextOutputStreamsWP
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_WFLinkActionArrayParameterDefinition
+ _OBJC_CLASS_$_WFLinkDynamicOptionsEnumerationParameter
+ _swift_unknownObjectRelease_n
- _$s10Foundation3URLV19_bridgeToObjectiveCSo5NSURLCyF
- _$s11WorkflowKit16ContainerIndexerC09IndexableC8MetadataO16bundleIdentifieryAESS_04ToolB00C10DefinitionV0C4TypeOSgtcAEmFWC
- _$s15Synchronization5MutexVMn
- _$s7ToolKit0A8DatabaseC13checkpointWAL10maxRetries12waitIntervalySu_s8DurationVtYaKF
- _$s7ToolKit0A8DatabaseC13checkpointWAL10maxRetries12waitIntervalySu_s8DurationVtYaKFTu
- _$s7ToolKit0A8DatabaseC13checkpointWAL10maxRetries12waitIntervalySu_s8DurationVtYaKFfA0_
- _$s7ToolKit0A8DatabaseC13checkpointWAL10maxRetries12waitIntervalySu_s8DurationVtYaKFfA_
- _$s7ToolKit0A8DatabaseC8AccessorCMn
- _$sSD10FoundationE34_conditionallyBridgeFromObjectiveC_6resultSbSo12NSDictionaryC_SDyxq_GSgztFZ
- _$ss10_HashTableV8nextHole9atOrAfterAB6BucketVAF_tF
- _$ss23CustomStringConvertibleMp
- _$ss23CustomStringConvertibleP11descriptionSSvgTq
- _CFBundleCopyLocalizedStringTableForLocalization
- _OBJC_CLASS_$_LNArrayValueType
- _OBJC_CLASS_$_LNEntityValueType
- _OBJC_CLASS_$_NSDictionary
- __CFBundleCreateUnique
- _kCFAllocatorDefault
CStrings:
+ "Failed to build static default value for parameter %s on %s: %@"
+ "Failed to lift member of array default value for parameter %s into an LNValue. Member: %s, member value type: %@"
+ "Failed to resolve localization, falling back to default value / key: %s/%s"
+ "Lifted array default value for parameter %s is not a member of %@. Dropping the default value."
+ "Localization bundle cache: hits=%ld, misses=%ld"
+ "Unknown runtime platform; treating action %{public}s as not ignored"
+ "bundleCacheHitCount"
+ "bundleCacheMissCount"
+ "cacheAllLocales"
+ "initWithInteger:"
+ "isSubclassOfClass:"
+ "localize:pluralizationNumber:"
+ "localizedStringResource"
+ "localizedStringWithContext:pluralizationNumber:"
+ "memberParameterDefinition"
+ "parameterClass"
+ "resetBundleCache"
+ "setCacheAllLocales:"
+ "wf_parameterDefinitionWithParameterMetadata:actionIdentifier:"
- "Failed to load strings: %s"
- "Resource is missing bundleURL, falling back to default value / key!"
- "Table was not found, falling back to default value / key!"
- "Unknown runtime platform"
- "_TtC8toolkitd27SingleLocaleBundleLocalizer"
- "toolkitd/ActionAvailability.swift"
```
