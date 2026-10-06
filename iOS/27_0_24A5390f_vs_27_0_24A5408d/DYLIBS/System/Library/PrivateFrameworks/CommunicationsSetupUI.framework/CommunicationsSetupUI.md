## CommunicationsSetupUI

> `/System/Library/PrivateFrameworks/CommunicationsSetupUI.framework/CommunicationsSetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8eafc` | `0x8f1ec` | **`+0x6f0`** |
| `__TEXT.__cstring` | `0xc647` | `0xc747` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0xbac0` | `0xbb40` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1490` | `0x14e0` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x64ed` | `0x653a` | **`+0x4d`** |
| `__TEXT.__gcc_except_tab` | `0x42cc` | `0x4314` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x8a74` | `0x8aac` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x5ba0` | `0x5bd0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x29a8` | `0x29d0` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0xd8a0` | `0xd8c0` | **`+0x20`** |

### Other Changes

```diff

-1568.100.1.0.0
+1570.100.1.0.0

-  Functions: 3061
-  Symbols:   5186
-  CStrings:  1789
+  Functions: 3067
+  Symbols:   5196
+  CStrings:  1794
Symbols:
+ -[CKSettingsMessagesController _applyMadridEnabled:specifier:]
+ -[CNFRegListController _showQuickSwitchDisableConfirmationWithHandler:]
+ -[CNFRegSettingsController _disableFaceTimeServiceAnimated:]
+ GCC_except_table108
+ GCC_except_table113
+ GCC_except_table125
+ GCC_except_table128
+ GCC_except_table129
+ GCC_except_table134
+ GCC_except_table145
+ GCC_except_table146
+ GCC_except_table158
+ GCC_except_table165
+ GCC_except_table168
+ GCC_except_table173
+ GCC_except_table179
+ GCC_except_table180
+ GCC_except_table184
+ GCC_except_table189
+ GCC_except_table192
+ GCC_except_table200
+ GCC_except_table210
+ GCC_except_table223
+ GCC_except_table226
+ GCC_except_table229
+ GCC_except_table232
+ GCC_except_table238
+ GCC_except_table242
+ GCC_except_table248
+ GCC_except_table262
+ GCC_except_table79
+ GCC_except_table80
+ GCC_except_table84
+ _CNFRegIsQuickSwitchActive
+ ___59-[CKSettingsMessagesController setMadridEnabled:specifier:]_block_invoke
+ ___66-[CNFRegSettingsController setFaceTimeEnabled:specifier:animated:]_block_invoke
+ ___71-[CNFRegListController _showQuickSwitchDisableConfirmationWithHandler:]_block_invoke
+ ___block_descriptor_41_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_56_e8_32s40s48s_e49_v24?0"CTQuickSwitchCarrierContext"8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_57_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- GCC_except_table101
- GCC_except_table109
- GCC_except_table126
- GCC_except_table132
- GCC_except_table143
- GCC_except_table144
- GCC_except_table149
- GCC_except_table163
- GCC_except_table167
- GCC_except_table171
- GCC_except_table176
- GCC_except_table181
- GCC_except_table182
- GCC_except_table187
- GCC_except_table190
- GCC_except_table199
- GCC_except_table209
- GCC_except_table221
- GCC_except_table225
- GCC_except_table228
- GCC_except_table231
- GCC_except_table235
- GCC_except_table236
- GCC_except_table241
- GCC_except_table244
- GCC_except_table259
- GCC_except_table82
- GCC_except_table85
- ___63-[CNFRegSettingsController _showRemoveAlertForAlias:specifier:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48s_e39_v24?0"CTQuickSwitchInfo"8"NSError"16ls32l8s40l8s48l8
CStrings:
+ "FACETIME_DISABLE_ALERT_QUICK_SWITCH_MESSAGE"
+ "FACETIME_DISABLE_ALERT_QUICK_SWITCH_TITLE"
+ "FACETIME_DISABLE_ALERT_QUICK_SWITCH_TURN_OFF"
+ "QuickSwitch remove gate for alias %@: role %ld, enrolled line %@ (error: %@)"
+ "v24@?0@\"CTQuickSwitchCarrierContext\"8@\"NSError\"16"
```
