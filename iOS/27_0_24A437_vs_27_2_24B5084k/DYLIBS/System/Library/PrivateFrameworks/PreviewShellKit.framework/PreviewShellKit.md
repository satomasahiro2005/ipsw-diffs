## PreviewShellKit

> `/System/Library/PrivateFrameworks/PreviewShellKit.framework/PreviewShellKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfd51c` | `0x100d18` | **`+0x37fc`** |
| `__TEXT.__eh_frame` | `0x9948` | `0x9d50` | **`+0x408`** |
| `__TEXT.__const` | `0xb464` | `0xb684` | **`+0x220`** |
| `__AUTH.__data` | `0x2538` | `0x2700` | **`+0x1c8`** |
| `__TEXT.__cstring` | `0x4a6c` | `0x4bcc` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x3f58` | `0x4070` | **`+0x118`** |
| `__AUTH_CONST.__const` | `0x6e10` | `0x6d20` | **`-0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x31d0` | `0x32a8` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x2c4b` | `0x2cfc` | **`+0xb1`** |
| `__TEXT.__constg_swiftt` | `0x2f80` | `0x2fe4` | **`+0x64`** |
| `__DATA.__data` | `0x3760` | `0x37c0` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x1892` | `0x18e2` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x231c` | `0x235c` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xc98` | `0xcd0` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x50ce` | `0x50fc` | **`+0x2e`** |
| `__AUTH_CONST.__auth_got` | `0x2060` | `0x2088` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x720` | `0x748` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x314` | `0x338` | **`+0x24`** |
| `__TEXT.__swift_as_ret` | `0x348` | `0x360` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x1928` | `0x1934` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xc8` | `0xd0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x310` | `0x314` | **`+0x4`** |

### Other Changes

```diff

-24.0.45.1.0
+24.20.6.0.0

-  Functions: 4676
-  Symbols:   1836
-  CStrings:  492
+  Functions: 4743
+  Symbols:   1837
+  CStrings:  499
Symbols:
+ __DATA__TtC15PreviewShellKit21JITProductSeedTracker
+ __IVARS__TtC15PreviewShellKit21JITProductSeedTracker
+ __METACLASS_DATA__TtC15PreviewShellKit21JITProductSeedTracker
+ ___unnamed_28
+ _symbolic Say_____G 19PreviewsMessagingOS17ArchivingStrategyV
+ _symbolic _____ 15PreviewShellKit21JITProductSeedTrackerC
+ _symbolic _____ 19PreviewsMessagingOS17ArchivingStrategyV
+ _symbolic _____ 20PreviewsFoundationOS16AsyncSerialQueueC
+ _symbolic _____Sg 19PreviewsMessagingOS17ArchivingStrategyV
+ _symbolic ______p 15PreviewShellKit0aB11SceneBinderP
+ _symbolic ______p 15PreviewShellKit0aB17SceneConfiguratorP
+ _symbolic _____ySDy__________GG 2os21OSAllocatedUnfairLockV 19PreviewsMessagingOS22PreviewProductIdentityV AD0hI4SeedV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 19PreviewsMessagingOS17ArchivingStrategyV
+ _symbolic _____y_____SgG 20PreviewsFoundationOS6FutureC So6CGSizeV
- ___swift_closure_destructor.62Tm
- ___swift_memcpy96_8
- ___unnamed_27
- _get_enum_tag_for_layout_string 15PreviewShellKit0aB11SceneBinder_pSg
- _get_enum_tag_for_layout_string 15PreviewShellKit0aB17SceneConfigurator_pSg
- _swift_release_x11
- _symbolic Say_____G 19PreviewsMessagingOS15ContentOverrideV
- _symbolic _____Sg 19PreviewsMessagingOS15ContentOverrideV
- _symbolic _____Sg_ABt 19PreviewsMessagingOS15ContentOverrideV
- _symbolic ___________t 19PreviewsMessagingOS22PreviewProductIdentityV AA0dE4SeedV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 19PreviewsMessagingOS15ContentOverrideV
- _type_layout_string 15PreviewShellKit0aB14PluginRegistryV
- _type_layout_string 15PreviewShellKit23ContentProviderRegistryV
CStrings:
+ " the host requested these archiving strategies: "
+ ", but the OS supports only: "
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Process Management/JITProductSeedTracker.swift"
+ "Providing archiving strategy for %{public}s"
+ "Skipping plugin bundles in '%{public}s'; using the builtin plugin only"
+ "This platform does not support this type of preview."
+ "This type of preview is not supported by this version of your development tools."
+ "apply(_:load:)"
+ "no provider for requested strategies %{public}s in %{public}s; falling back to .default"
+ "preferredSize()"
- " the OS only supports these content overrides \n(and not the default override): "
- "Providing content override for %{public}s)"
- "This type of preview requires a newer Xcode version."
```
