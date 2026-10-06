## ActivityKit

> `/System/Library/Frameworks/ActivityKit.framework/ActivityKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc0b18` | `0xc3658` | **`+0x2b40`** |
| `__DATA.__bss` | `0x12c30` | `0x130b0` | **`+0x480`** |
| `__TEXT.__const` | `0xed4a` | `0xef8a` | **`+0x240`** |
| `__TEXT.__eh_frame` | `0x43e0` | `0x45e0` | **`+0x200`** |
| `__AUTH_CONST.__const` | `0x8b48` | `0x8c70` | **`+0x128`** |
| `__TEXT.__unwind_info` | `0x3848` | `0x3920` | **`+0xd8`** |
| `__TEXT.__swift5_reflstr` | `0x234e` | `0x2413` | **`+0xc5`** |
| `__TEXT.__swift5_fieldmd` | `0x2f9c` | `0x3058` | **`+0xbc`** |
| `__DATA.__data` | `0x3260` | `0x3300` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x5720` | `0x57b0` | **`+0x90`** |
| `__TEXT.__cstring` | `0x1e01` | `0x1e61` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x3820` | `0x3878` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x3dc2` | `0x3e18` | **`+0x56`** |
| `__AUTH_CONST.__auth_got` | `0xdd0` | `0xe00` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x2840` | `0x2810` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0xf04` | `0xf2c` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0xd50` | `0xd74` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x680` | `0x698` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x480` | `0x490` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x808` | `0x810` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x3f4` | `0x3fc` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x64` | `0x68` | **`+0x4`** |

### Other Changes

```diff

-312.100.0.0.0
+313.2.3.0.0

-  Functions: 5162
-  Symbols:   2137
-  CStrings:  360
+  Functions: 5226
+  Symbols:   2149
+  CStrings:  363
Symbols:
+ ___swift_memcpy34_8
+ _associated conformance 11ActivityKit04LiveA17ApplicationRecordV10CodingKeys33_FA809C0041491A663E080F99D71C72CALLOSHAASQ
+ _associated conformance 11ActivityKit04LiveA17ApplicationRecordV10CodingKeys33_FA809C0041491A663E080F99D71C72CALLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 11ActivityKit04LiveA17ApplicationRecordV10CodingKeys33_FA809C0041491A663E080F99D71C72CALLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 11ActivityKit04LiveA17ApplicationRecordVSHAASQ
+ _symbolic Say_____G 11ActivityKit04LiveA17ApplicationRecordV
+ _symbolic _____ 11ActivityKit04LiveA17ApplicationRecordV
+ _symbolic _____ 11ActivityKit04LiveA17ApplicationRecordV10CodingKeys33_FA809C0041491A663E080F99D71C72CALLO
+ _symbolic _____Sg 10Foundation23LocalizedStringResourceV
+ _symbolic ______p 11ActivityKit0A21AuthorizationManagingP
+ _symbolic _____y_____G s22KeyedDecodingContainerV 11ActivityKit04LiveD17ApplicationRecordV10CodingKeys33_FA809C0041491A663E080F99D71C72CALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 11ActivityKit04LiveD17ApplicationRecordV10CodingKeys33_FA809C0041491A663E080F99D71C72CALLO
+ _type_layout_string 11ActivityKit04LiveA17ApplicationRecordV
- _symbolic ______pSgXw 11ActivityKit0A21AuthorizationManagingP
CStrings:
+ "areActivitiesEnabled"
+ "declaresDisplayName"
+ "localizedActivityName"
```
