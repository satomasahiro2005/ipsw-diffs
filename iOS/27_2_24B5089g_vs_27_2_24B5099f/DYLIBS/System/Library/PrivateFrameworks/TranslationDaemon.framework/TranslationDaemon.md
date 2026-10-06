## TranslationDaemon

> `/System/Library/PrivateFrameworks/TranslationDaemon.framework/TranslationDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1abfac` | `0x1ac85c` | **`+0x8b0`** |
| `__TEXT.__oslogstring` | `0xdbb0` | `0xddd0` | **`+0x220`** |
| `__AUTH_CONST.__objc_const` | `0x2d2c8` | `0x2d410` | **`+0x148`** |
| `__TEXT.__objc_methlist` | `0x1a568` | `0x1a628` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x1b588` | `0x1b4f8` | **`-0x90`** |
| `__DATA_DIRTY.__objc_data` | `0x10e0` | `0x1130` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x6cb8` | `0x6d00` | **`+0x48`** |
| `__TEXT.__cstring` | `0x633b` | `0x637b` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x280` | `0x2b8` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x4648` | `0x4618` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0x7f20` | `0x7f40` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x2f0` | `0x310` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xfb20` | `0xfb40` | **`+0x20`** |
| `__DATA.__data` | `0xd78` | `0xd60` | **`-0x18`** |
| `__DATA.__bss` | `0x6d0` | `0x6c0` | **`-0x10`** |
| `__TEXT.__const` | `0x9a0` | `0x990` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x11fc` | `0x1204` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x11d8` | `0x11e0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1128` | `0x1130` | **`+0x8`** |

### Other Changes

```diff

-393.1.0.0.0
+396.0.0.0.0

-  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 10457
-  Symbols:   18832
-  CStrings:  2276
+  Functions: 10473
+  Symbols:   18854
+  CStrings:  2285
Symbols:
+ +[_LTHotfixManager _selectHotfixAssetFromEntries:minimumFormatVersion:maximumFormatVersion:]
+ +[_LTSpeechTranslationAssetInfo _phrasebookHasContentAtLocalFileURL:]
+ +[_LTTranslationServer _canReuseAIAdapterEngine:forContext:]
+ -[_LTAIAdapterTranslationEngine matchesInferenceLocationForLocalePair:aiInferenceLocation:]
+ -[_LTHotfixAssetMetadata .cxx_destruct]
+ -[_LTHotfixAssetMetadata description]
+ -[_LTHotfixAssetMetadata formatVersion]
+ -[_LTHotfixAssetMetadata initWithName:version:formatVersion:]
+ -[_LTHotfixAssetMetadata name]
+ -[_LTHotfixAssetMetadata version]
+ -[_LTHotfixManager _attemptHotfixRefresh:]
+ -[_LTHotfixManager _downloadHotfixAsset:completion:]
+ -[_LTHotfixManager _extractArchive:forAsset:]
+ -[_LTHotfixManager _installHotfixAsset:archive:completion:]
+ -[_LTHotfixManager _installedHotfixDirectoryForAsset:]
+ -[_LTHotfixManager _replaceHotfixOnInternalQueue:completion:]
+ -[_LTHotfixManager _resolveAvailableHotfix:]
+ _OBJC_CLASS_$__LTHotfixAssetMetadata
+ _OBJC_IVAR_$__LTHotfixAssetMetadata._formatVersion
+ _OBJC_IVAR_$__LTHotfixAssetMetadata._name
+ _OBJC_IVAR_$__LTHotfixAssetMetadata._version
+ _OBJC_METACLASS_$__LTHotfixAssetMetadata
+ __CLASS_METHODS__LTAIAdapterImplementation
+ __OBJC_$_CLASS_METHODS__LTTranslationServer
+ __OBJC_$_INSTANCE_METHODS__LTHotfixAssetMetadata
+ __OBJC_$_INSTANCE_VARIABLES__LTHotfixAssetMetadata
+ __OBJC_$_PROP_LIST__LTHotfixAssetMetadata
+ __OBJC_CLASS_RO_$__LTHotfixAssetMetadata
+ __OBJC_METACLASS_RO_$__LTHotfixAssetMetadata
+ ___42-[_LTHotfixManager _attemptHotfixRefresh:]_block_invoke
+ ___44-[_LTHotfixManager _resolveAvailableHotfix:]_block_invoke
+ ___46-[_LTHotfixManager _replaceHotfix:completion:]_block_invoke
+ ___52-[_LTHotfixManager _downloadHotfixAsset:completion:]_block_invoke
+ ___52-[_LTHotfixManager _downloadWithRequest:completion:]_block_invoke_2
+ ___59-[_LTHotfixManager _installHotfixAsset:archive:completion:]_block_invoke
+ ___59-[_LTHotfixManager _installHotfixAsset:archive:completion:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40bs_e44_v24?0"_LTHotfixAssetMetadata"8"NSError"16ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e28_v24?0"NSData"8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_56_e8_32s40s48bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24ls32l8s40l8s48l8
+ _hotfixDirectory
+ _isCompleteHotfixDirectory
- +[_LTHotfixManager _hotfixDirectoryNameForEntry:]
- +[_LTHotfixManager _selectHotfixEntryFromMapping:minimumFormatVersion:maximumFormatVersion:]
- -[_LTAIAdapterTranslationEngine aiInferenceLocation]
- -[_LTHotfixManager _downloadHotfix:completion:]
- -[_LTHotfixManager _installNewestSupportedHotfix:]
- -[_LTHotfixManager updateHotfix:]
- _OBJC_IVAR_$__LTAIAdapterTranslationEngine._aiInferenceLocation
- ___33-[_LTHotfixManager updateHotfix:]_block_invoke
- ___34-[_LTHotfixManager refreshHotfix:]_block_invoke_2
- ___47-[_LTHotfixManager _downloadHotfix:completion:]_block_invoke
- ___47-[_LTHotfixManager _downloadHotfix:completion:]_block_invoke_2
- ___50-[_LTHotfixManager _installNewestSupportedHotfix:]_block_invoke
- ___block_descriptor_48_e8_32bs40w_e17_v16?0"NSError"8lw40l8s32l8
- ___block_descriptor_48_e8_32bs40w_e34_v24?0"NSDictionary"8"NSError"16lw40l8s32l8
- ___block_descriptor_48_e8_32s40bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24ls32l8s40l8
- ___block_descriptor_64_e8_32s40s48bs56w_e28_v24?0"NSData"8"NSError"16lw56l8s48l8s32l8s40l8
- ___block_descriptor_72_e8_32s40s48s56bs64w_e5_v8?0lw64l8s32l8s56l8s40l8s48l8
- __swift_FORCE_LOAD_$_swiftNaturalLanguage
- __swift_FORCE_LOAD_$_swiftNaturalLanguage_$_TranslationDaemon
- _parseHotfixEntryVersions
CStrings:
+ "%@ (%d-%d)"
+ "Abandoning refresh of %{public}@ after download failure, installed hotfix left in place"
+ "Can't reuse AI adapter engine: its session runs %{public}@ inference, but %{public}@ under %{public}@ resolves to %{public}@"
+ "Download hotfix: %{public}@"
+ "Extracted hotfix %@ holds no %@"
+ "Extracted hotfix completeness check failed: %@"
+ "Failed to download hotfix archive %{public}@, error code %{public}ld: %@"
+ "Failed to find compatible hotfix between versions %d-%d, out of %lu mapping entries"
+ "Found existing hotfix, no need to install"
+ "Hotfix install prepare failure: %@"
+ "Installed hotfix %{public}@"
+ "Resolved available hotfix %{public}@"
+ "Reusing existing AI adapter engine since it supports this locale pair and its inference session config hasn't changed"
+ "Skipping phrasebook symlink for %{public}@: no files in %{public}@/PB"
+ "Successfully downloaded hotfix archive %{public}@"
+ "Treating hotfix %{public}@ as not installed, its directory couldn't be read: %@"
+ "ai_ifp_speech_to_speech"
+ "v24@?0@\"_LTHotfixAssetMetadata\"8@\"NSError\"16"
- "Found existing hotfix"
- "Hotfix asset refresh prepare failure: %@"
- "Hotfix asset refresh update failure: %@"
- "Hotfix entry does not name a version to install"
- "Refusing to install a hotfix entry that names no version: %@"
- "Remove folder failed: %@"
- "Reusing existing AI adapter engine since it supports this locale pair and the task hint and process identifier haven't changed"
- "Select hotfix: %@"
- "Update of hotfix assets failed: %@"
```
