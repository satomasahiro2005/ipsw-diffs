## Enhanced Logging

> `/Applications/Enhanced Logging.app/Enhanced Logging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78128` | `0x783cc` | **`+0x2a4`** |
| `__DATA.__data` | `0x2fb0` | `0x2ff0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x840` | `0x870` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1958` | `0x1978` | **`+0x20`** |
| `__TEXT.__const` | `0x41b4` | `0x41a4` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-277.40.10.0.0
+277.42.1.0.0

-  Functions: 2047
-  Symbols:   1135
+  Functions: 2054
+  Symbols:   1141
Symbols:
+ _$s15EnhancedLogging12TargetDeviceV0D4TypeO13homeAccessoryyA2EmFWC
+ _$s7SwiftUI14_PaddingLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI14_PaddingLayoutVN
+ _$s7SwiftUI16_FlexFrameLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI16_FlexFrameLayoutVN
+ _$s7SwiftUI22HierarchicalShapeStyleVAA0dE0AAMc
+ _$s7SwiftUI30_SafeAreaRegionsIgnoringLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI30_SafeAreaRegionsIgnoringLayoutVN
+ _$s7SwiftUI4TextVAA4ViewAAMc
+ _$s7SwiftUI5ImageVAA4ViewAAMc
+ _$s7SwiftUI9EmptyViewVAA0D0AAMc
+ _$s7SwiftUI9EmptyViewVN
+ _$ss5NeverO7SwiftUI4ViewACMc
+ _$ss5NeverON
- _$s7SwiftUI14_PaddingLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI16_FlexFrameLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI22HierarchicalShapeStyleVAA0dE0AAWP
- _$s7SwiftUI30_SafeAreaRegionsIgnoringLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI4TextVAA4ViewAAWP
- _$s7SwiftUI5ImageVAA4ViewAAWP
- _$s7SwiftUI9EmptyViewVAA0D0AAWP
- _$ss5NeverO7SwiftUI4ViewACWP
```
