## MusicKitUI

> `/System/Library/CoreServices/MusicKitUI.app/MusicKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18244` | `0x19058` | **`+0xe14`** |
| `__TEXT.__objc_stubs` | `0x800` | `0x8e0` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x79a` | `0x87a` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x1a2f` | `0x1adf` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x8b2` | `0x934` | **`+0x82`** |
| `__DATA.__data` | `0xfb8` | `0x1008` | **`+0x50`** |
| `__TEXT.__const` | `0xc94` | `0xcd4` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x5c8` | `0x600` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x760` | `0x798` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x12d0` | `0x1300` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x1ac` | `0x1dc` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x730` | `0x760` | **`+0x30`** |
| `__DATA.__common` | `0x40` | `0x58` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x970` | `0x988` | **`+0x18`** |
| `__DATA.__objc_data` | `0x748` | `0x758` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2a0` | `0x2b0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x714` | `0x724` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x390` | `0x398` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.110.78.1.0
+4026.100.85.0.0

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 613
-  Symbols:   517
-  CStrings:  423
+  Functions: 629
+  Symbols:   523
+  CStrings:  433
Symbols:
+ _$s17_MusicKit_SwiftUI01_A6PickerV01_ab9Internal_cD0E17MainViewContainerV11isPresented12selectedItem0L5Items0j17SelectingMultipleN06reason5title9angelHost17completionHandlerAFy_xG0cD07BindingVySbG_ARyxSgGARySayxGGSbAD0aE0V6ReasonOSgSSSgAF05AngelT0Vy_x_GSgyAVYacSgtcfC
+ _$s17_MusicKit_SwiftUI01_A6PickerV01_ab9Internal_cD0E17MainViewContainerV9AngelHostV19updateSelectedItems9onDismiss0o3CanP6ChangeAHy_x_GySayxGYbKcSg_yyYbcSgySbYbcSgtcfC
+ _$s17_MusicKit_SwiftUI01_A6PickerV01_ab9Internal_cD0E17MainViewContainerV9AngelHostVMn
+ _$sSh8IteratorV6_cocoaAByx_Gs10__CocoaSetVAACn_tcfC
+ _OBJC_CLASS_$_UIApplication
+ _TCCAccessPreflightWithAuditToken
+ _kTCCServiceMediaLibrary
- _$s17_MusicKit_SwiftUI01_A6PickerV01_ab9Internal_cD0E17MainViewContainerV11isPresented12selectedItem0L5Items0j17SelectingMultipleN06reason5title014updateSelectedN09onDismiss17completionHandlerAFy_xG0cD07BindingVySbG_ASyxSgGASySayxGGSbAD0aE0V6ReasonOSgSSSgyAWKcSgyycSgyAWYacSgtcfC
CStrings:
+ "Allowed request from %{public}s: %{bool,public}d."
+ "Refusing request from %{public}s due to missing kTCCServiceMediaLibrary grant."
+ "Refusing request from %{public}s due to no audit token on scene."
+ "_FBSScene"
+ "auditToken"
+ "hostHandle"
+ "invalidate"
+ "requestSceneSessionDestruction:options:errorHandler:"
+ "setModalInPresentation:"
+ "sharedApplication"
```
