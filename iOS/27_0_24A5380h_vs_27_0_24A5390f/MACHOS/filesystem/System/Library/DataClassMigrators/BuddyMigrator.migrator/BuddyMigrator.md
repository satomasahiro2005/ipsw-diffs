## BuddyMigrator

> `/System/Library/DataClassMigrators/BuddyMigrator.migrator/BuddyMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x284c0` | `0x27edc` | **`-0x5e4`** |
| `__DATA.__objc_const` | `0x38b8` | `0x3748` | **`-0x170`** |
| `__TEXT.__objc_methname` | `0x4aad` | `0x4985` | **`-0x128`** |
| `__DATA.__objc_data` | `0x1828` | `0x1738` | **`-0xf0`** |
| `__DATA.__data` | `0x10c0` | `0x1018` | **`-0xa8`** |
| `__TEXT.__objc_methlist` | `0x1b08` | `0x1a70` | **`-0x98`** |
| `__TEXT.__const` | `0xd78` | `0xce8` | **`-0x90`** |
| `__TEXT.__objc_classname` | `0xd7a` | `0xcea` | **`-0x90`** |
| `__TEXT.__swift5_typeref` | `0xb4e` | `0xac0` | **`-0x8e`** |
| `__TEXT.__oslogstring` | `0x2c8d` | `0x2c11` | **`-0x7c`** |
| `__TEXT.__constg_swiftt` | `0xa0c` | `0x998` | **`-0x74`** |
| `__TEXT.__objc_stubs` | `0x2fe0` | `0x2f80` | **`-0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x5d8` | `0x578` | **`-0x60`** |
| `__TEXT.__objc_methtype` | `0xc96` | `0xcd4` | **`+0x3e`** |
| `__TEXT.__swift5_reflstr` | `0x4ba` | `0x486` | **`-0x34`** |
| `__DATA.__objc_selrefs` | `0x10a8` | `0x1078` | **`-0x30`** |
| `__TEXT.__cstring` | `0xfeb` | `0xfc5` | **`-0x26`** |
| `__TEXT.__auth_stubs` | `0x10c0` | `0x10a0` | **`-0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x140` | `0x128` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0xbe0` | `0xbc8` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x870` | `0x860` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x190` | `0x180` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x1078` | `0x1068` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0xc0` | `0xb0` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x150` | `0x148` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x3c` | `0x38` | **`-0x4`** |
| `__TEXT.__swift5_protos` | `0x10` | `0xc` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x7c` | `0x78` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5407.0.0.0.0
+5409.0.0.0.0

-  - /System/Library/PrivateFrameworks/SetupAssistantSupportUI.framework/SetupAssistantSupportUI

-  Functions: 918
+  Functions: 906

-  CStrings:  1254
+  CStrings:  1239
CStrings:
+ "firstSupportedOSReleaseVersionForThisDevice"
- "BYRunState"
- "BuddyMigrator.NewFeaturesFlowManager"
- "BuddyMigrator: Queueing mini-buddy to show new features"
- "New Feature video was skipped, updating chronicle record."
- "_TtC13BuddyMigrator22NewFeaturesFlowManager"
- "_TtP13BuddyMigrator26NewFeaturesFlowManagerType_"
- "_shouldLaunchForNewFeaturesUpsell"
- "hasCompletedInitialRun"
- "initWithChronicle:runState:"
- "lastSeenVersion"
- "needsToRun"
- "newFeaturesFlowHandler"
- "recordFlowWasSkippedIfNeeded"
- "runState"
- "setProductVersion:forFeature:"
- "updatePresentedKey:"
```
