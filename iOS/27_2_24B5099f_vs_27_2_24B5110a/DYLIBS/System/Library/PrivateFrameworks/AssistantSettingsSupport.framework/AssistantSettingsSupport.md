## AssistantSettingsSupport

> `/System/Library/PrivateFrameworks/AssistantSettingsSupport.framework/AssistantSettingsSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x84a24` | `0x854ec` | **`+0xac8`** |
| `__TEXT.__cstring` | `0x6e98` | `0x7078` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x201e` | `0x21ae` | **`+0x190`** |
| `__AUTH_CONST.__cfstring` | `0x3fc0` | `0x4080` | **`+0xc0`** |
| `__DATA.__data` | `0x1640` | `0x1690` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xd68` | `0xdb8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1ea0` | `0x1ee0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xcf8` | `0xd18` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2488` | `0x24a8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2e40` | `0x2e58` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x7c8` | `0x7dc` | **`+0x14`** |

### Other Changes

```diff

-3605.30.1.0.0
+3605.31.1.11.2

-  Functions: 2632
-  Symbols:   2766
-  CStrings:  987
+  Functions: 2649
+  Symbols:   2774
+  CStrings:  1003
Symbols:
+ -[AssistantController _showLinwoodHomeAlertIfNeeded]
+ -[AssistantController presentDisableAppleIntelligenceSiriAlert]
+ GCC_except_table132
+ GCC_except_table149
+ GCC_except_table154
+ GCC_except_table171
+ GCC_except_table174
+ GCC_except_table181
+ GCC_except_table185
+ GCC_except_table202
+ GCC_except_table204
+ GCC_except_table215
+ GCC_except_table225
+ ___52-[AssistantController _showLinwoodHomeAlertIfNeeded]_block_invoke
+ ___52-[AssistantController _showLinwoodHomeAlertIfNeeded]_block_invoke_2
+ ___63-[AssistantController presentDisableAppleIntelligenceSiriAlert]_block_invoke
+ ___block_descriptor_40_e8_32w_e20_v20?0"NSError"8B16lw32l8
+ ___block_descriptor_49_e8_32s40w_e5_v8?0lw40l8s32l8
- GCC_except_table143
- GCC_except_table148
- GCC_except_table165
- GCC_except_table168
- GCC_except_table175
- GCC_except_table179
- GCC_except_table196
- GCC_except_table198
- GCC_except_table209
- GCC_except_table219
CStrings:
+ "%s Error fetching Linwood enablement status for Home devices, continue to disable. %@"
+ "%s Returning early due to block deallocation."
+ "%s User does not have Linwood enabled on any home devices."
+ "%s User has at least one home device with Linwood enabled, showing alert."
+ "%s presentDisableAppleIntelligenceSiriAlert cancel selected"
+ "%s presentDisableAppleIntelligenceSiriAlert turn off selected"
+ "-[AssistantController _showLinwoodHomeAlertIfNeeded]_block_invoke"
+ "-[AssistantController _showLinwoodHomeAlertIfNeeded]_block_invoke_2"
+ "-[AssistantController presentDisableAppleIntelligenceSiriAlert]_block_invoke"
+ "ASSISTANT_DISABLE_APPLE_INTELLIGENCE_CANCEL"
+ "ASSISTANT_DISABLE_APPLE_INTELLIGENCE_CONFIRMATION"
+ "ASSISTANT_DISABLE_APPLE_INTELLIGENCE_PROMPT"
+ "ASSISTANT_DISABLE_APPLE_INTELLIGENCE_TITLE"
+ "AssistantSettings-J490"
+ "AssistantSettings-LinwoodTVOS"
+ "v20@?0@\"NSError\"8B16"
```
