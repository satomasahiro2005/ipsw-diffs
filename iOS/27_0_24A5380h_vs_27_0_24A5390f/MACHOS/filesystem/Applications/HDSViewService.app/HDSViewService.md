## HDSViewService

> `/Applications/HDSViewService.app/HDSViewService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbdf90` | `0xbee58` | **`+0xec8`** |
| `__TEXT.__cstring` | `0x6c99` | `0x6cd9` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x6020` | `0x6040` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x7285` | `0x72a5` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x2914` | `0x2934` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x18d8` | `0x18f0` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x1aa0` | `0x1ab0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0xa675` | `0xa685` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1f94` | `0x1fa0` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x24a8` | `0x24b0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xd60` | `0xd68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-405.0.3.0.0
+405.0.7.0.0

-  Functions: 2507
-  Symbols:   843
-  CStrings:  3153
+  Functions: 2511
+  Symbols:   844
+  CStrings:  3157
Symbols:
+ _swift_retain_x27
CStrings:
+ "HomePodBackgroundImageViewController: no background image in viewModel, skipping setup"
+ "HomePodSetupViewModel createStereoPairImages: model.assetBundle.deviceAssetAdjustmentsURL == nil"
+ "HomePodSetupViewModel createStereoPairImages: stereoPairUnitImage(in: model.assetBundle) == nil"
+ "ProxCard_StereoPair"
+ "ProxCard_adjustments.plist"
+ "sendSubviewToBack:"
- "HomePodSetupViewModel createStereoPairImages: UIImage(named: ProxCard_StereoPairUnit, in: model.assetBundle) == nil"
- "HomePodSetupViewModel createStereoPairImages: model.assetBundle.url(forResource: SFDeviceAssetNameAdjustments, withExtension: nil) == nil"
```
