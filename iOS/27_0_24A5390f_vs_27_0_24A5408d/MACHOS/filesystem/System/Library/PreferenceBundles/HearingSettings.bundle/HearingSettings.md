## HearingSettings

> `/System/Library/PreferenceBundles/HearingSettings.bundle/HearingSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39b6c` | `0x3a968` | **`+0xdfc`** |
| `__TEXT.__objc_stubs` | `0x7740` | `0x7a00` | **`+0x2c0`** |
| `__TEXT.__objc_methname` | `0x92dc` | `0x9597` | **`+0x2bb`** |
| `__TEXT.__objc_methlist` | `0x2f24` | `0x3034` | **`+0x110`** |
| `__DATA.__objc_selrefs` | `0x2870` | `0x2930` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x3da8` | `0x3e38` | **`+0x90`** |
| `__TEXT.__objc_methtype` | `0x1644` | `0x16a3` | **`+0x5f`** |
| `__TEXT.__unwind_info` | `0xe00` | `0xe30` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1048` | `0x1070` | **`+0x28`** |
| `__TEXT.__cstring` | `0x331f` | `0x3307` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0xf10` | `0xf00` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x248` | `0x254` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x798` | `0x790` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x6e0` | `0x6e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-536.0.0.0.0
+539.1.0.0.0

-  Functions: 1202
+  Functions: 1225

-  CStrings:  2325
+  CStrings:  2359
Symbols:
+ _CGRectGetHeight
+ _CGRectGetMaxY
+ _NSFontAttributeName
+ _UIFontTextStyleFootnote
- _PSDefaultValueKey
- _dispatch_async
- _dispatch_queue_attr_make_with_qos_class
- _dispatch_queue_create
CStrings:
+ "TB,N,V_adjustingSlider"
+ "TB,N,V_pendingReloadSpecifiers"
+ "TB,N,V_pendingUpdateView"
+ "Tq,N,V_sliderAdjustmentCount"
+ "_adjustingSlider"
+ "_beginSliderAdjustIfNeeded"
+ "_endSliderAdjustIfNeeded"
+ "_isAdjustingSlider"
+ "_pendingReloadSpecifiers"
+ "_pendingUpdateView"
+ "_sliderAdjustmentController"
+ "_sliderAdjustmentCount"
+ "adjustingSlider"
+ "ax_availabilityColumnWidth:"
+ "ax_availabilityRowAtY:width:margins:ltr:"
+ "ax_layoutStacked:margins:ltr:"
+ "ax_modelText:"
+ "ax_placeGroup:indicator:edge:top:height:ltr:"
+ "beginSliderAdjustment"
+ "boundingRectWithSize:options:attributes:context:"
+ "d32@0:8@16d24"
+ "d60@0:8@16@24d32d40d48B56"
+ "endSliderAdjustment"
+ "heightRequiredForDevice:width:"
+ "lineHeight"
+ "pendingReloadSpecifiers"
+ "pendingUpdateView"
+ "q"
+ "reloadSpecifiersIfPossible"
+ "setAdjustingSlider:"
+ "setAdjustsFontForContentSizeCategory:"
+ "setPendingReloadSpecifiers:"
+ "setPendingUpdateView:"
+ "setSliderAdjustmentCount:"
+ "setupSlider"
+ "sizeWithAttributes:"
+ "sliderAdjustmentCount"
+ "sliderDidBeginTracking:"
+ "sliderDidEndTracking:"
+ "target"
+ "updateViewIfPossible"
+ "v24@0:8q16"
+ "v60@0:8d16{UIEdgeInsets=dddd}24B56"
+ "v68@0:8d16d24{UIEdgeInsets=dddd}32B64"
- "@\"NSObject<OS_dispatch_queue>\""
- "T@\"NSObject<OS_dispatch_queue>\",&,N,V_valueUpdateQueue"
- "_legacy_sizeWithFont:minFontSize:actualFontSize:forWidth:lineBreakMode:"
- "_valueUpdateQueue"
- "boldSystemFontOfSize:"
- "hearing_slider_queue"
- "lineBreakMode"
- "numberOfLines"
- "setValueUpdateQueue:"
- "valueUpdateQueue"
```
