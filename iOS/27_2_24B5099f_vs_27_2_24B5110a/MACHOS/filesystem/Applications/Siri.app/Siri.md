## Siri

> `/Applications/Siri.app/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf2f64` | `0xf3384` | **`+0x420`** |
| `__TEXT.__objc_methname` | `0x2ba7f` | `0x2bb2f` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0xdca4` | `0xdd04` | **`+0x60`** |
| `__DATA.__data` | `0x4810` | `0x4840` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1858` | `0x1880` | **`+0x28`** |
| `__DATA.__objc_const` | `0x10f38` | `0x10f58` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1b880` | `0x1b8a0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3988` | `0x39a0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x90c8` | `0x90d8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xe4b0` | `0xe4c0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xb101` | `0xb111` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x8dc` | `0x8e0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3605.30.1.0.0
+3605.31.1.11.2

-  Functions: 5216
-  Symbols:   1867
-  CStrings:  9100
+  Functions: 5224
+  Symbols:   1872
+  CStrings:  9105
Symbols:
+ _$s7SwiftUI12_FrameLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI12_FrameLayoutVN
+ _$s7SwiftUI12_ScaleEffectVAA12ViewModifierAAMc
+ _$s7SwiftUI12_ScaleEffectVN
+ _$s7SwiftUI14_OpacityEffectVAA12ViewModifierAAMc
+ _$s7SwiftUI14_OpacityEffectVN
+ _$s7SwiftUI4TextVAA4ViewAAMc
+ _$s7SwiftUI4TextVN
+ _$s7SwiftUI5ColorVAA4ViewAAMc
+ _$s7SwiftUI9EmptyViewVAA0D0AAMc
+ _$ss5NeverO7SwiftUI4ViewACMc
+ _$ss5NeverON
- _$s7SwiftUI12_FrameLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI12_ScaleEffectVAA12ViewModifierAAWP
- _$s7SwiftUI14_OpacityEffectVAA12ViewModifierAAWP
- _$s7SwiftUI4TextVAA4ViewAAWP
- _$s7SwiftUI5ColorVAA4ViewAAWP
- _$s7SwiftUI9EmptyViewVAA0D0AAWP
- _$ss5NeverO7SwiftUI4ViewACWP
CStrings:
+ "%s #tts #tv Allowing listening after speaking on AppleTV for a confirmation dialog phase"
+ "B40@0:8@16@24B32B36"
+ "_listenAfterSpeakingForConfirmationPhase"
+ "_shouldWakeDisplayForAppPunchOutWithRefId:requestOptions:isAppleTV:displayIsAsleep:"
+ "isOdeonProxyVoiceTrigger"
```
