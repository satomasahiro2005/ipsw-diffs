## VisionKitCore

> `/System/Library/PrivateFrameworks/VisionKitCore.framework/VisionKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe85f4` | `0xe6bd0` | **`-0x1a24`** |
| `__AUTH.__objc_data` | `0x4220` | `0x4d38` | **`+0xb18`** |
| `__DATA_DIRTY.__objc_data` | `0x1428` | `0x910` | **`-0xb18`** |
| `__TEXT.__eh_frame` | `0x600` | `0x4c8` | **`-0x138`** |
| `__AUTH_CONST.__const` | `0x1a68` | `0x19c0` | **`-0xa8`** |
| `__AUTH_CONST.__cfstring` | `0x6840` | `0x68c0` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x1100` | `0x1088` | **`-0x78`** |
| `__DATA_CONST.__got` | `0xf00` | `0xf70` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x74a` | `0x6f0` | **`-0x5a`** |
| `__TEXT.__unwind_info` | `0x43d0` | `0x4378` | **`-0x58`** |
| `__DATA.__bss` | `0x1460` | `0x14b0` | **`+0x50`** |
| `__TEXT.__const` | `0x1ec8` | `0x1e80` | **`-0x48`** |
| `__TEXT.__swift5_capture` | `0x17c` | `0x134` | **`-0x48`** |
| `__DATA.__data` | `0x2108` | `0x20d0` | **`-0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x9818` | `0x9850` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x10584` | `0x105bc` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x310f0` | `0x31120` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x3c88` | `0x3c58` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x4167` | `0x4137` | **`-0x30`** |
| `__DATA_DIRTY.__bss` | `0x100` | `0xd8` | **`-0x28`** |
| `__TEXT.__cstring` | `0x82bd` | `0x829d` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x24` | `0x18` | **`-0xc`** |
| `__TEXT.__gcc_except_tab` | `0x26e0` | `0x26dc` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x14` | `0x10` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x10` | `0xc` | **`-0x4`** |

### Other Changes

```diff

-338.0.0.0.0
+341.0.0.0.0

-  - /System/Library/PrivateFrameworks/AgentSessionKit.framework/AgentSessionKit

-  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 6784
-  Symbols:   10656
-  CStrings:  1621
+  Functions: 6769
+  Symbols:   10667
+  CStrings:  1618
Symbols:
+ +[VKCImageAnalyzer setViBundleIdentifier:]
+ +[VKCImageAnalyzer setViEntryType:]
+ +[VKCImageAnalyzer shouldShowEnhancedSiri]
+ +[VKCImageAnalyzer viBundleIdentifier]
+ +[VKCImageAnalyzer viEntryType]
+ -[NSData(VKDataExtensions) vk_temporaryFileDescriptorWithError:]
+ GCC_except_table238
+ _NSPOSIXErrorDomain
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSData_$_VKDataExtensions
+ ___42+[VKCImageAnalyzer shouldShowEnhancedSiri]_block_invoke
+ ___error
+ _close
+ _getVICVisualIntelligenceAnalyzerClass
+ _getVIUEntityResponseClass
+ _open
+ _sViBundleIdentifier
+ _sViBundleIdentifierLock
+ _sViBundleIdentifier_block_invoke.onceToken
+ _sViEntryType
+ _shouldShowEnhancedSiri.onceToken
+ _shouldShowEnhancedSiri.respondsToShouldShowEnhancedSiri
+ _strerror
+ _supportedAnalysisTypes.supportsNewVIAvailabilityApi
- -[NSData(VKDataExtensions) vk_saveToMediaStoreWithCompletion:]
- GCC_except_table237
- _VKCMaxPixelDimension_block_invoke.onceToken
- __OBJC_$_INSTANCE_METHODS_NSData(VKDataExtensions|VisionKitCore)
- ___block_descriptor_40_e8_32bs_e30_v24?0"NSString"8"NSError"16ls32l8
- __swift_FORCE_LOAD_$_swiftIntents
- __swift_FORCE_LOAD_$_swiftIntents_$_VisionKitCore
- _symbolic SSSg______pSgIeggg_ s5ErrorP
- _symbolic So6NSDataC
- _symbolic So8NSStringCSgSo7NSErrorCSgIeyByy_
- _symbolic _____Sg 10Foundation3URLV
- _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
CStrings:
+ "Failed to materialize HEIC file descriptor"
+ "Failed to open temp file: %s"
+ "No HEIC data from delegate"
+ "VI HEIC request: delegate returned no HEIC data"
+ "VI HEIC request: failed to materialize HEIC file descriptor: %@"
+ "tmp"
- "AgentMediaStoreHelper"
- "AgentMediaStoreTemp"
- "Beginning saving data to AMS"
- "Error saving heic data to AMS: %@"
- "Removing temporary AMS file."
- "Saving to AMS"
- "Writing to temporary file at %s"
- "com.apple.visionkit"
- "v24@?0@\"NSString\"8@\"NSError\"16"
```
