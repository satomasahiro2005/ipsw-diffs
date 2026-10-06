## SiriSetupBridgeBundle

> `/System/Library/NanoPreferenceBundles/SetupBundles/SiriSetupBridgeBundle.bundle/SiriSetupBridgeBundle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4808` | `0x4018` | **`-0x7f0`** |
| `__TEXT.__objc_methname` | `0x7f7` | `0x6e7` | **`-0x110`** |
| `__DATA_CONST.__cfstring` | `0xe0` | `—` | **`-0xe0`** |
| `__TEXT.__objc_stubs` | `0x4a0` | `0x3c0` | **`-0xe0`** |
| `__TEXT.__oslogstring` | `0x4fd` | `0x41d` | **`-0xe0`** |
| `__DATA.__objc_const` | `0x408` | `0x340` | **`-0xc8`** |
| `__TEXT.__objc_methlist` | `0x2f4` | `0x24c` | **`-0xa8`** |
| `__TEXT.__cstring` | `0x247` | `0x1b7` | **`-0x90`** |
| `__TEXT.__auth_stubs` | `0x660` | `0x5e0` | **`-0x80`** |
| `__DATA.__objc_selrefs` | `0x260` | `0x200` | **`-0x60`** |
| `__DATA_CONST.__auth_got` | `0x338` | `0x2f8` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x2a0` | `0x260` | **`-0x40`** |
| `__DATA.__objc_data` | `0x288` | `0x258` | **`-0x30`** |
| `__TEXT.__objc_classname` | `0x108` | `0xd8` | **`-0x30`** |
| `__TEXT.__objc_methtype` | `0x21a` | `0x1ea` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x190` | `0x168` | **`-0x28`** |
| `__TEXT.__constg_swiftt` | `0x108` | `0x120` | **`+0x18`** |
| `__DATA.__bss` | `0x1a0` | `0x190` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xb8` | `0xa8` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x60` | `0x6c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x20` | `0x18` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x8` | `—` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x4` | `—` | **`-0x4`** |
| `__TEXT.__swift5_typeref` | `0x104` | `0x108` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1359.3.0.0.0
+1359.7.0.0.0

-  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  Functions: 101
-  Symbols:   133
-  CStrings:  162
+  Functions: 87
+  Symbols:   118
+  CStrings:  133
Symbols:
- _OBJC_CLASS_$_BPSVideoControllingBuilder
- _OBJC_CLASS_$_BPSWelcomeOptinViewController
- _OBJC_CLASS_$_NSString
- _OBJC_CLASS_$_SiriSetupSuccessViewController
- _OBJC_METACLASS_$_BPSWelcomeOptinViewController
- _OBJC_METACLASS_$_SiriSetupSuccessViewController
- ___CFConstantStringClassReference
- _dispatch_once
- _objc_destroyWeak
- _objc_loadWeakRetained
- _objc_release_x1
- _objc_retainAutoreleaseReturnValue
- _objc_storeWeak
- _os_log_create
- _swift_dynamicCastClass
CStrings:
+ "Flow already finished; ignoring duplicate buddyControllerDone"
+ "Voice-training step complete (Not Now); advancing to next setup topic"
+ "didFinish"
- "@\"<BPSSetupMiniFlowControllerDelegate>\""
- "Calling buddyControllerDone to continue flow (no success screen)"
- "DeviceAssets/%@"
- "Done"
- "Done button tapped"
- "Failed to create SiriSetupSuccessViewController"
- "Flow completed for SiriSetupSuccessViewController"
- "Initialized SiriSetupSuccessViewController"
- "Missing navigation controller"
- "Not Now tapped - skipping voice training"
- "Screen-Siri-v3"
- "Screen-Video-Siri"
- "Showing custom success screen"
- "Siri Is Ready"
- "SiriSetupSuccessViewController"
- "T@\"<BPSSetupMiniFlowControllerDelegate>\",W,N,VminiFlowDelegate"
- "You can now use Hey Siri! on your Apple Watch."
- "contentLayout"
- "detailString"
- "imageResource"
- "mov"
- "navigationController"
- "pushController:animated:"
- "setStyle:"
- "setupflow"
- "stringWithFormat:"
- "suggestedButtonPressed:"
- "suggestedButtonTitle"
- "titleString"
- "v8@?0"
- "videoController"
- "videoControllerWithFileName:fileExtension:bundle:autoPlay:startDelay:shouldLoop:volume:"
```
