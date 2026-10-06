## FaceTime

> `/private/var/staged_system_apps/FaceTime.app/FaceTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc61c8` | `0xc56b8` | **`-0xb10`** |
| `__TEXT.__oslogstring` | `0x52a6` | `0x5206` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x2f11` | `0x2e81` | **`-0x90`** |
| `__TEXT.__const` | `0x3374` | `0x3304` | **`-0x70`** |
| `__TEXT.__swift5_typeref` | `0x1c28` | `0x1bde` | **`-0x4a`** |
| `__TEXT.__auth_stubs` | `0x2fe0` | `0x2fc0` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x2e60` | `0x2e40` | **`-0x20`** |
| `__DATA.__common` | `0x1b0` | `0x198` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x1800` | `0x17f0` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x8a0` | `0x898` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xf00` | `0xf08` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3064.100.8.0.0
+3066.100.3.0.0

-  Functions: 3698
-  Symbols:   1500
-  CStrings:  3772
+  Functions: 3678
+  Symbols:   1494
+  CStrings:  3766
Symbols:
+ _$s15ConversationKit17ClarityUIRootViewV7SwiftUI0E0AAMc
+ _$s15ConversationKit17ClarityUIRootViewVACycfC
+ _$s15ConversationKit17ClarityUIRootViewVMa
+ _$s15ConversationKit17ClarityUIRootViewVMn
+ _$sScMs11GlobalActorsMc
- _$s7SwiftUI12SceneBuilderV10buildBlockyxxAA0C0RzlFZ
- _$s7SwiftUI4ViewMp
- _$s7SwiftUI7AnyViewVAA0D0AAWP
- _$s7SwiftUI7AnyViewVMn
- _$s7SwiftUI7AnyViewVN
- _$s7SwiftUI7AnyViewVyACxcAA0D0RzlufC
- _$s7SwiftUI9EmptyViewVAA0D0AAWP
- _$s7SwiftUI9EmptyViewVN
- _$sSS7cStringSSSPys4Int8VG_tcfC
- _dlopen
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "PHClarityUISceneDelegate"
- "/System/Library/PrivateFrameworks/ConversationKit.framework/ConversationKit"
- "CNKClarityUISceneDelegate"
- "Failed to load ConversationKit.framework:%s"
- "No function clarityUIRootView_generic in ConversationKit."
- "Successfully soft linked ConversationKit!"
- "clarityUIRootView_generic"
- "com.apple.calls.incallservice"
```
