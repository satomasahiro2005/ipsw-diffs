## VisualVoicemail

> `/System/Library/PrivateFrameworks/VisualVoicemail.framework/VisualVoicemail`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1abfc` | `0x1b554` | **`+0x958`** |
| `__TEXT.__oslogstring` | `0x21e0` | `0x2297` | **`+0xb7`** |
| `__DATA_CONST.__const` | `0xa70` | `0xb10` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xf9f` | `0x101b` | **`+0x7c`** |
| `__TEXT.__objc_methlist` | `0x1fc0` | `0x2010` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x514` | `0x554` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1348` | `0x1378` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x918` | `0x948` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x220` | `0x240` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x3b78` | `0x3b90` | **`+0x18`** |

### Other Changes

```diff

-954.0.0.0.0
+956.0.0.0.0

-  Functions: 778
-  Symbols:   1345
-  CStrings:  352
+  Functions: 790
+  Symbols:   1358
+  CStrings:  359
Symbols:
+ -[VMVoicemailManager getQuickSwitchDataCache:]
+ -[VMVoicemailManager getQuickSwitchModeParameterForAccountUUID:error:]
+ -[VMVoicemailManager getQuickSwitchParametersForAccountUUID:error:]
+ GCC_except_table185
+ GCC_except_table188
+ GCC_except_table191
+ GCC_except_table196
+ GCC_except_table210
+ GCC_except_table216
+ GCC_except_table222
+ GCC_except_table226
+ GCC_except_table229
+ GCC_except_table240
+ GCC_except_table252
+ GCC_except_table255
+ ___46-[VMVoicemailManager getQuickSwitchDataCache:]_block_invoke
+ ___67-[VMVoicemailManager getQuickSwitchParametersForAccountUUID:error:]_block_invoke
+ ___70-[VMVoicemailManager getQuickSwitchModeParameterForAccountUUID:error:]_block_invoke
+ ___block_descriptor_48_e8_32r40r_e20_v20?0"NSArray"8B16lr32l8r40l8
+ ___block_descriptor_48_e8_32r40r_e23_v28?0B8Q12"NSError"20lr32l8r40l8
+ ___block_descriptor_48_e8_32r40r_e32_v28?0B8"NSArray"12"NSError"20lr32l8r40l8
+ ___block_descriptor_48_e8_32r40r_e45_v24?0"VMQuickSwitchParameters"8"NSError"16lr32l8r40l8
- GCC_except_table187
- GCC_except_table192
- GCC_except_table195
- GCC_except_table198
- GCC_except_table217
- GCC_except_table220
- GCC_except_table231
- GCC_except_table237
- GCC_except_table243
CStrings:
+ "Could not get QuickSwitch data cache due to error %@"
+ "Could not get QuickSwitch mode for account %@ due to error %@"
+ "Could not get QuickSwitch parameters for account %@ due to error %@"
+ "v20@?0@\"NSArray\"8B16"
+ "v24@?0@\"VMQuickSwitchParameters\"8@\"NSError\"16"
+ "v28@?0B8@\"NSArray\"12@\"NSError\"20"
+ "v28@?0B8Q12@\"NSError\"20"
```
