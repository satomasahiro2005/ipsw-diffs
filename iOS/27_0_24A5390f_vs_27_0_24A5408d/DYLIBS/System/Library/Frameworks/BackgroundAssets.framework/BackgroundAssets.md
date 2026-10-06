## BackgroundAssets

> `/System/Library/Frameworks/BackgroundAssets.framework/BackgroundAssets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9b700` | `0xa10e4` | **`+0x59e4`** |
| `__TEXT.__oslogstring` | `0x5228` | `0x5858` | **`+0x630`** |
| `__TEXT.__eh_frame` | `0x47c0` | `0x4a98` | **`+0x2d8`** |
| `__AUTH_CONST.__objc_const` | `0x2b28` | `0x2d10` | **`+0x1e8`** |
| `__TEXT.__objc_methlist` | `0x1450` | `0x15a0` | **`+0x150`** |
| `__DATA.__data` | `0x1308` | `0x1408` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x1c80` | `0x1d80` | **`+0x100`** |
| `__AUTH.__objc_data` | `0x1b0` | `0x278` | **`+0xc8`** |
| `__DATA_CONST.__objc_selrefs` | `0xae8` | `0xba8` | **`+0xc0`** |
| `__TEXT.__const` | `0x30d8` | `0x3188` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x12a5` | `0x132d` | **`+0x88`** |
| `__AUTH_CONST.__auth_got` | `0x1070` | `0x10e0` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0x2040` | `0x2090` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x678` | `0x6c8` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0xc98` | `0xcd8` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x929` | `0x969` | **`+0x40`** |
| `__AUTH.__data` | `0x310` | `0x340` | **`+0x30`** |
| `__TEXT.__cstring` | `0x434a` | `0x437a` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x948` | `0x970` | **`+0x28`** |
| `__DATA.__bss` | `0x3c60` | `0x3c80` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0xa00` | `0xa20` | **`+0x20`** |
| `__DATA.__common` | `0x8` | `0x18` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0xb8` | `0xc8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x284` | `0x294` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x804` | `0x7f8` | **`-0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x100` | `0x108` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xbc` | `0xc0` | **`+0x4`** |

### Other Changes

```diff

-279.0.1.0.0
+279.0.5.0.0

-  Functions: 2043
-  Symbols:   1534
-  CStrings:  635
+  Functions: 2101
+  Symbols:   1562
+  CStrings:  650
Symbols:
+ GCC_except_table12
+ _OBJC_CLASS_$_NSFileCoordinator
+ _OBJC_CLASS_$_NSOperationQueue
+ _OBJC_CLASS_$__TtC16BackgroundAssets33LocalizedAssetPackDownloadTracker
+ _OBJC_METACLASS_$__TtC16BackgroundAssets33LocalizedAssetPackDownloadTracker
+ __DATA__TtC16BackgroundAssets33LocalizedAssetPackDownloadTracker
+ __INSTANCE_METHODS__TtC16BackgroundAssets33LocalizedAssetPackDownloadTracker
+ __IVARS__TtC16BackgroundAssets33LocalizedAssetPackDownloadTracker
+ __METACLASS_DATA__TtC16BackgroundAssets33LocalizedAssetPackDownloadTracker
+ __OBJC_$_PROP_LIST_NSFilePresenter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSFilePresenter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSFilePresenter
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSFilePresenter
+ __OBJC_$_PROTOCOL_REFS_NSFilePresenter
+ __OBJC_LABEL_PROTOCOL_$_NSFilePresenter
+ __OBJC_PROTOCOL_$_NSFilePresenter
+ __PROPERTIES__TtC16BackgroundAssets33LocalizedAssetPackDownloadTracker
+ __PROTOCOLS__TtC16BackgroundAssets33LocalizedAssetPackDownloadTracker
+ ___swift_closure_destructor.104Tm
+ ___swift_closure_destructor.108Tm
+ ___swift_closure_destructor.267Tm
+ ___swift_closure_destructor.70Tm
+ ___swift_closure_destructor.7Tm
+ ___swift_closure_destructor.82Tm
+ ___swift_closure_destructor.99Tm
+ _keypath_get_selector_identifier
+ _swift_getAtKeyPath
+ _swift_isEscapingClosureAtFileLocation
+ _symbolic SS_So10BADownloadCt
+ _symbolic ShySSGIgl_
+ _symbolic So16NSOperationQueueC
+ _symbolic _____ 16BackgroundAssets33LocalizedAssetPackDownloadTrackerC
+ _symbolic _____AAIgnn_ 10Foundation3URLV
+ _symbolic _____XDXMT 16BackgroundAssets33LocalizedAssetPackDownloadTrackerC
+ _symbolic _____ySSSo10BADownloadCG s18_DictionaryStorageC
+ _symbolic _____ySS_So10BADownloadCtG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s11_SetStorageC 10Foundation6LocaleV8LanguageV
- GCC_except_table10
- ___swift_closure_destructor.103Tm
- ___swift_closure_destructor.107Tm
- ___swift_closure_destructor.266Tm
- ___swift_closure_destructor.75Tm
- ___swift_closure_destructor.81Tm
- ___swift_closure_destructor.98Tm
- _symbolic SDySSypG
- _symbolic _____Sg 16BackgroundAssets16LanguageResolverC
CStrings:
+ "<Localized Asset Packs Lookup Descriptor | For current profile>"
+ "A directory couldn’t be created at “%{public}s”: %{public}@"
+ "Access to the file that keeps track of ongoing downloads of localized asset packs couldn’t be coordinated: %{public}@"
+ "Asset packs with download policy: %{public}s localized asset packs lookup descriptor: %{public}s"
+ "Checking for updates…"
+ "Default localized asset packs lookup descriptor"
+ "Downloading appropriately localized asset packs…"
+ "Downloads of localized asset packs couldn’t be added: %{public}@"
+ "Localized asset packs with download policy: %{public}s lookup descriptor: %{public}s"
+ "Localized asset packs with lookup descriptor: %{public}s"
+ "Locally available languages"
+ "Ongoing Localized Asset Pack Download IDs.plist"
+ "Preferred languages couldn’t be reconciled: %{public}@"
+ "Reading the set of IDs of ongoing downloads of localized asset packs from “%{public}s”…"
+ "Remove unnecessary localized asset packs following completion of: %{public}@"
+ "Report failed download with ID: %{public}s of asset pack with ID: %{public}s version: %lu error: %{public}@"
+ "Resolved language from: %{public}s profile-specific preferred languages: %{public}s"
+ "Resolved language profile-specific preferred languages: %{public}s"
+ "Scheduling the %{public}sasset pack with the ID “%{public}s” to be downloaded…"
+ "The Managed Background Assets support directory is unavailable."
+ "The asset pack with the ID “%{public}s” won’t be removed because its language, %{public}s, is equivalent to at least one profile’s resolved language."
+ "The available language%s %{public}s."
+ "The file that keeps track of ongoing downloads of localized asset packs is unavailable."
+ "The preferred language%s %{public}s."
+ "The set of IDs of ongoing downloads of localized asset packs couldn’t be loaded from “%{public}s”: %{public}@"
+ "The set of IDs of ongoing downloads of localized asset packs couldn’t be saved to “%{public}s”: %{public}@"
+ "The set of IDs of ongoing downloads of localized asset packs doesn’t yet exist at “%{public}s”."
+ "Unnecessary localized asset packs couldn’t be removed: %{public}@"
+ "With ongoing localized asset pack download IDs: %{public}s"
+ "Writing the set of IDs of ongoing downloads of localized asset packs to “%{public}s”…"
- "Asset packs with download policy: %{public}s"
- "Checking for asset-pack updates…"
- "Downloading asset packs that are localized for %{public}s…"
- "EXAppExtensionAttributes"
- "EXExtensionPointIdentifier"
- "Is running in downloader extension"
- "Localized asset packs couldn’t be added or reconciled: %{public}@"
- "Localized asset packs couldn’t be added: %{public}@"
- "Localized asset packs with download policy: %{public}s"
- "No cached manifest is available."
- "Report failed download of asset pack with ID: %{public}s version: %lu error: %{public}@"
- "Resolved language from: %{public}s"
- "Scheduling the %{public}s asset pack with the ID “%{public}s” to be downloaded…"
- "The available languages are %{public}s."
- "The preferred languages are %{public}s."
```
