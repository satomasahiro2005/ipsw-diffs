## Enhanced Logging

> `/Applications/Enhanced Logging.app/Enhanced Logging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e1a0` | `0x6ed84` | **`+0xbe4`** |
| `__DATA_CONST.__const` | `0x37d8` | `0x3918` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x2aca` | `0x2be2` | **`+0x118`** |
| `__TEXT.__objc_stubs` | `0x21c0` | `0x2100` | **`-0xc0`** |
| `__TEXT.__objc_methname` | `0x49ad` | `0x491d` | **`-0x90`** |
| `__TEXT.__oslogstring` | `0x749` | `0x7d9` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0xcd8` | `0xd58` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x28d0` | `0x2920` | **`+0x50`** |
| `__DATA.__data` | `0x2c40` | `0x2c80` | **`+0x40`** |
| `__TEXT.__const` | `0x4064` | `0x40a4` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xfb8` | `0xf88` | **`-0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x958` | `0x988` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x1cc8` | `0x1cf8` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1470` | `0x1498` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x800` | `0x828` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x214c` | `0x2164` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1f2d` | `0x1f1d` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x18c8` | `0x18d8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x134` | `0x138` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-225.0.0.0.0
+236.0.0.0.0

-  - /System/Library/PrivateFrameworks/DiagnosticsSupport.framework/DiagnosticsSupport

-  Functions: 2051
-  Symbols:   1111
-  CStrings:  1080
+  Functions: 2062
+  Symbols:   1125
+  CStrings:  1077
Symbols:
+ _$s10Foundation3URLV14pathComponentsSaySSGvg
+ _$s10Foundation3URLV6schemeSSSgvg
+ _$s7SwiftUI11ToolbarItemVAAytRszrlE9placement7contentACyytq_GAA0cD9PlacementV_q_yXEtcfC
+ _$s7SwiftUI11ToolbarItemVMn
+ _$s7SwiftUI11ToolbarItemVyxq_GAA0C7ContentAAMc
+ _$s7SwiftUI17NavigationBarItemV16TitleDisplayModeO6inlineyA2EmFWC
+ _$s7SwiftUI17NavigationBarItemV16TitleDisplayModeOMa
+ _$s7SwiftUI20ToolbarItemPlacementV14topBarTrailingACvgZ
+ _$s7SwiftUI21DefaultShareLinkLabelVMn
+ _$s7SwiftUI4ViewPAAE15navigationTitleyQrqd__SyRd__lF
+ _$s7SwiftUI4ViewPAAE15navigationTitleyQrqd__SyRd__lFQOMQ
+ _$s7SwiftUI4ViewPAAE29navigationBarTitleDisplayModeyQrAA010NavigationE4ItemV0fgH0OF
+ _$s7SwiftUI4ViewPAAE29navigationBarTitleDisplayModeyQrAA010NavigationE4ItemV0fgH0OFQOMQ
+ _$s7SwiftUI9ShareLinkVAAs5NeverORs_AERs0_AA07DefaultcD5LabelVRs1_rlE4item7subject7messageACys15CollectionOfOneVy10Foundation3URLVGA2eGGAO_AA4TextVSgATtcAPRszrlufC
+ _$s7SwiftUI9ShareLinkVMn
+ _$s7SwiftUI9ShareLinkVyxq_q0_q1_GAA4ViewAAMc
+ _$sSiN
+ _$sSis23CustomStringConvertiblesWP
+ _$ss15CollectionOfOneVMn
+ _$sxSg7SwiftUI14ToolbarContentA2bCRzlMc
+ _CGContextScaleCTM
- _$s10Foundation3URLV21deletingPathExtensionACyF
- _$s10Foundation3URLV25deletingLastPathComponentACyF
- _$s2os0A4_log_3dso0B04type_ys12StaticStringV_SVSgSo03OS_a1_B0CSo0a1_b1_D2_tas7CVarArg_pdtF
- _$sSo9OS_os_logC0B0E7defaultABvgZ
- _OBJC_CLASS_$_DSMutableArchive
- _OBJC_CLASS_$_NSDateComponentsFormatter
- _OBJC_CLASS_$_OS_os_log
CStrings:
+ "Enhanced_Logging/UploadConsentFileView.swift"
+ "Failed to get device image with error: %@"
+ "File %s does not exist on this device"
+ "Parsed ticket number %s from universal link %s"
- "Failed to delete tar from extracted cosysdiagnose"
- "extractArchive:toDirectory:"
- "removeItemAtURL:error:"
- "setCollapsesLargestUnit:"
- "setMaximumUnitCount:"
- "setUnitsStyle:"
- "stringFromTimeInterval:"
```
