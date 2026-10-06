## Weather

> `/private/var/staged_system_apps/Weather.app/Weather`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xba46a8` | `0xba48f4` | **`+0x24c`** |
| `__DATA.__bss` | `0xc5258` | `0xc5458` | **`+0x200`** |
| `__TEXT.__unwind_info` | `0x22578` | `0x22670` | **`+0xf8`** |
| `__TEXT.__const` | `0x991b4` | `0x992a4` | **`+0xf0`** |
| `__DATA.__data` | `0x5e2f0` | `0x5e3b0` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x293a0` | `0x2941c` | **`+0x7c`** |
| `__TEXT.__swift5_typeref` | `0xb29b8` | `0xb29f8` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x28ab0` | `0x28ae8` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x16e70` | `0x16ea0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2b343` | `0x2b313` | **`-0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x8310` | `0x8330` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xb740` | `0xb758` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x4d2c8` | `0x4d2e0` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x65b0` | `0x65c8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x6330` | `0x6340` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x6a24` | `0x6a34` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x24cd6` | `0x24ce6` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x1e9b0` | `0x1e9a8` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x2d0c` | `0x2d14` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1470.0.0.0.0
+1474.0.0.0.0

-  Functions: 61793
-  Symbols:   10279
-  CStrings:  5977
+  Functions: 61838
+  Symbols:   10284
+  CStrings:  5975
Symbols:
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s17WeatherAppSupport18LocationHeaderViewV4DataV12locationName14secondaryLabel20localizedTemperature0lM4Unit0L9Condition0L4High0L3Low24accessibilityDescription15useVerticalText26requiresAdditionalContrast012nonProminentS00z9ProminentS8MarkdownAESS_AE09SecondaryK0OS2SSgS4SS2bA2TtcfC
+ _$s7SwiftUI15CoordinateSpaceO5localyA2CmFWC
+ _$s7SwiftUI4ViewPAAE12onTapGesture5count15coordinateSpace7performQrSi_AA010CoordinateI0OySo7CGPointVctF
+ _$s7SwiftUI4ViewPAAE12onTapGesture5count15coordinateSpace7performQrSi_AA010CoordinateI0OySo7CGPointVctFQOMQ
- _$s17WeatherAppSupport18LocationHeaderViewV4DataV12locationName14secondaryLabel20localizedTemperature0lM4Unit0L9Condition0L4High0L3Low15useVerticalText26requiresAdditionalContrast23nonProminentDescription0xyZ8MarkdownAESS_AE09SecondaryK0OS2SSgS3SS2bA2StcfC
CStrings:
+ "c3d7f4939db4a2506f47d921e644ce31"
- "b5f331874ccde79ebc846018e23b1efa"
- "kind location "
- "longestPrecipitationAmount"
```
