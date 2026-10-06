## ChronoCore

> `/System/Library/PrivateFrameworks/ChronoCore.framework/ChronoCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43716c` | `0x43d40c` | **`+0x62a0`** |
| `__AUTH.__data` | `0x16d8` | `0x1958` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0x16347` | `0x164e7` | **`+0x1a0`** |
| `__AUTH_CONST.__objc_const` | `0x18960` | `0x18ab0` | **`+0x150`** |
| `__DATA_DIRTY.__bss` | `0x9ab0` | `0x99b0` | **`-0x100`** |
| `__DATA_DIRTY.__data` | `0x105f8` | `0x104f8` | **`-0x100`** |
| `__TEXT.__swift5_reflstr` | `0xabef` | `0xacdf` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0xbde4` | `0xbec4` | **`+0xe0`** |
| `__DATA.__data` | `0x3500` | `0x3580` | **`+0x80`** |
| `__TEXT.__const` | `0x149c8` | `0x14a48` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0xcaa0` | `0xcb10` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x8028` | `0x8098` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x1158` | `0x11a8` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x13af8` | `0x13b48` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x78c0` | `0x7900` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xc4b0` | `0xc4e8` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x5624` | `0x5640` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x4578` | `0x4590` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x600` | `0x608` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xb74` | `0xb6c` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x684` | `0x688` | **`+0x4`** |

### Other Changes

```diff

-749.2.4.0.0
+749.2.7.0.0

-  Functions: 11153
-  Symbols:   4504
-  CStrings:  2012
+  Functions: 11217
+  Symbols:   4511
+  CStrings:  2018
Symbols:
+ __DATA__TtC10ChronoCore20TaskPriorityBucketer
+ __IVARS__TtC10ChronoCore20TaskPriorityBucketer
+ __METACLASS_DATA__TtC10ChronoCore20TaskPriorityBucketer
+ _associated conformance 10ChronoCore19SessionPriorityInfoVSHAASQ
+ _symbolic SDySo20CHSExtensionIdentityCShy_____GG 10ChronoCore19SessionPriorityInfoV
+ _symbolic SDy_____Say_____GG 14ChronoServices12TaskPriorityO 0A4Core0cD8BucketerC0C4InfoV
+ _symbolic _____ 10ChronoCore19SessionPriorityInfoV
+ _symbolic _____ 10ChronoCore20TaskPriorityBucketerC
+ _symbolic _____ 10ChronoCore20TaskPriorityBucketerC0C4InfoV
+ _symbolic _____Sg 10ChronoCore13ExtensionTaskC
+ _symbolic _____Sg 10ChronoCore19SessionPriorityInfoV
+ _symbolic _____Sg_ABt 14ChronoServices12TaskPriorityO
+ _symbolic ______Say_____Gt 14ChronoServices12TaskPriorityO 0A4Core0cD8BucketerC0C4InfoV
+ _symbolic _____ySo20CHSExtensionIdentityCShy_____GG s18_DictionaryStorageC 10ChronoCore19SessionPriorityInfoV
+ _symbolic _____y_____G s11_SetStorageC 10ChronoCore19SessionPriorityInfoV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10ChronoCore20TaskPriorityBucketerC0F4InfoV
+ _symbolic _____y_____Say_____GG s18_DictionaryStorageC 14ChronoServices12TaskPriorityO 0C4Core0eF8BucketerC0E4InfoV
- _associated conformance 10ChronoCore20_SessionPriorityInfo33_88014C52750BCE846CAE375D70242454LLVSHAASQ
- _associated conformance 10ChronoCore9_TaskInfo33_88014C52750BCE846CAE375D70242454LLVSHAASQ
- _symbolic SDySo20CHSExtensionIdentityCShy_____GG 10ChronoCore20_SessionPriorityInfo33_88014C52750BCE846CAE375D70242454LLV
- _symbolic _____ 10ChronoCore20_SessionPriorityInfo33_88014C52750BCE846CAE375D70242454LLV
- _symbolic _____ 10ChronoCore9_TaskInfo33_88014C52750BCE846CAE375D70242454LLV
- _symbolic _____Sg 10ChronoCore20_SessionPriorityInfo33_88014C52750BCE846CAE375D70242454LLV
- _symbolic _____ySo20CHSExtensionIdentityCShy_____GG s18_DictionaryStorageC 10ChronoCore20_SessionPriorityInfo33_88014C52750BCE846CAE375D70242454LLV
- _symbolic _____y_____G s11_SetStorageC 10ChronoCore20_SessionPriorityInfo33_88014C52750BCE846CAE375D70242454LLV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 10ChronoCore9_TaskInfo33_88014C52750BCE846CAE375D70242454LLV
- _symbolic _____y_____Say_____GG s18_DictionaryStorageC 14ChronoServices12TaskPriorityO 0C4Core01_E4Info33_88014C52750BCE846CAE375D70242454LLV
CStrings:
+ "Boosting task %{public}@ to fix priority inversion"
+ "No priority inversions detected: no pending foreground tasks"
+ "No priority inversions detected: no sessions"
+ "No priority inversions detected: no sessions or no pending foreground tasks"
+ "Task %{public}@ will be boosted to fix no-slots priority inversion"
+ "Task %{public}@ will be boosted to fix same-extension priority inversion"
```
