## Enhanced Logging

> `/Applications/Enhanced Logging.app/Enhanced Logging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ed10` | `0x6fe24` | **`+0x1114`** |
| `__TEXT.__const` | `0x40a4` | `0x3f24` | **`-0x180`** |
| `__TEXT.__swift5_typeref` | `0x2be2` | `0x2cda` | **`+0xf8`** |
| `__TEXT.__eh_frame` | `0x1cf8` | `0x1c60` | **`-0x98`** |
| `__DATA_CONST.__const` | `0x3918` | `0x39a8` | **`+0x90`** |
| `__DATA.__objc_const` | `0x28a8` | `0x2908` | **`+0x60`** |
| `__TEXT.__cstring` | `0x1f1d` | `0x1f7d` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x16be` | `0x171e` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x1518` | `0x1570` | **`+0x58`** |
| `__DATA.__data` | `0x2c80` | `0x2cd0` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x491d` | `0x495d` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x7d9` | `0x819` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x828` | `0x858` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x2920` | `0x2940` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2100` | `0x2120` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x18d8` | `0x18b8` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x2164` | `0x2180` | **`+0x1c`** |
| `__DATA.__bss` | `0x2d20` | `0x2d30` | **`+0x10`** |
| `__DATA.__common` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1498` | `0x14a8` | **`+0x10`** |
| `__DATA.__objc_data` | `0x23d0` | `0x23d8` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xf88` | `0xf90` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x138` | `0x130` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x8c` | `0x84` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0xd58` | `0xd54` | **`-0x4`** |
| `__TEXT.__swift5_proto` | `0x180` | `0x184` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x170` | `0x174` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-240.0.0.502.1
+251.0.0.0.0

-  Functions: 2062
-  Symbols:   1125
-  CStrings:  1077
+  Functions: 2059
+  Symbols:   1132
+  CStrings:  1085
Symbols:
+ _$s15EnhancedLogging14SessionManagerC9reconnectAA0C0CSgyF
+ _$s15EnhancedLogging7SessionC2idSSvg
+ _$s15EnhancedLogging7SessionCMn
+ _$s7Combine18PassthroughSubjectCyxq_GAA0C0AAMc
+ _$s7Combine7SubjectPAAyt6OutputRtzrlE4sendyyF
+ _$s7SwiftUI31AccessibilityAttachmentModifierVAA04ViewE0AAMc
+ _$s7SwiftUI31AccessibilityAttachmentModifierVMa
+ _$s7SwiftUI31AccessibilityAttachmentModifierVMn
+ _$s7SwiftUI4MenuV7content5labelACyxq_Gq_yXE_xyXEtcfC
+ _$s7SwiftUI4MenuVMn
+ _$s7SwiftUI4MenuVyxq_GAA4ViewAAMc
+ _$s7SwiftUI4ViewPAAE18accessibilityLabelyAA15ModifiedContentVyxAA31AccessibilityAttachmentModifierVGAA4TextVF
+ _$s7SwiftUI5ImageV10systemNameACSS_tcfC
+ _$s7SwiftUI5ImageVAA4ViewAAWP
+ _$s7SwiftUI5ImageVN
+ _NSCocoaErrorDomain
+ _OBJC_CLASS_$_NSError
- _$s15EnhancedLogging12LaunchSchemeO4logsyA2CmFWC
- _$s15EnhancedLogging12LaunchSchemeOMa
- _$s15EnhancedLogging14SessionManagerC8delegateAA0cD8Delegate_pSgvs
- _$s15EnhancedLogging22SessionManagerDelegateMp
- _$s15EnhancedLogging22SessionManagerDelegateP07sessionD0_0F5EndedyAA0cD0C_SStFTq
- _$s15EnhancedLogging22SessionManagerDelegateP07sessionD0_0F7CreatedyAA0cD0C_SStFTq
- _$s15EnhancedLogging7SessionC15setLaunchSchemeyyAA0eF0OF
- _$s7SwiftUI18DefaultButtonLabelVMn
- _$s7SwiftUI20ToolbarItemPlacementV18cancellationActionACvgZ
- _$s7SwiftUI6ButtonVA2A07DefaultC5LabelVRszrlE4role6actionACyAEGAA0C4RoleV_yyctcfC
CStrings:
+ "CANCEL_COLLECTION"
+ "Enhanced_Logging/SessionToolbarGroup.swift"
+ "Host is not long enough to parse any ticket number."
+ "SESSION_CANCELED_BODY"
+ "SESSION_CANCELED_TITLE"
+ "domain"
+ "objectForKey:"
+ "outcome"
+ "sessionCancelled"
+ "sessionFailed"
+ "wasCancelled"
- "Enhanced_Logging/CancelToolbarItemGroup.swift"
- "boolForKey:"
- "sessionEnded"
```
