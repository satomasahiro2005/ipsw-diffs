## Calculator

> `/private/var/staged_system_apps/Calculator.app/Calculator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf1630` | `0xf1e54` | **`+0x824`** |
| `__TEXT.__swift5_typeref` | `0x1abb6` | `0x1ac18` | **`+0x62`** |
| `__TEXT.__const` | `0xa944` | `0xa974` | **`+0x30`** |
| `__DATA.__data` | `0x6450` | `0x6468` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x4e40` | `0x4e50` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2d48` | `0x2d58` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2728` | `0x2730` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-138.0.0.0.0
+138.1.0.0.0

-  - /System/Library/PrivateFrameworks/AXCoreUtilities.framework/AXCoreUtilities

-  Functions: 4484
-  Symbols:   2258
+  Functions: 4487
+  Symbols:   2259
Symbols:
+ _$s10Foundation6LocaleV15localizedString13forRegionCodeSSSgSS_tF
+ _$s10Foundation6LocaleV6RegionV10identifierSSvg
+ _$s7SwiftUI6PickerV9selection5label7contentACyxq_q0_GAA7BindingVyq_G_xq0_yXEtcfC
- _$s10Foundation6LocaleV6RegionV15AXCoreUtilitiesE14icuDisplayNameSSSgvg
- _$s7SwiftUI6PickerVA2A4TextVRszrlE_9selection7contentACyAEq_q0_GAA18LocalizedStringKeyV_AA7BindingVyq_Gq0_yXEtcfC
```
