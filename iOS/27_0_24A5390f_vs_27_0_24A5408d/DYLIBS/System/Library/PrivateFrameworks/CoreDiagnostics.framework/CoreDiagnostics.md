## CoreDiagnostics

> `/System/Library/PrivateFrameworks/CoreDiagnostics.framework/CoreDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72720` | `0x72e10` | **`+0x6f0`** |
| `__AUTH_CONST.__objc_const` | `0x1910` | `0x19e0` | **`+0xd0`** |
| `__AUTH.__data` | `0x448` | `0x4f0` | **`+0xa8`** |
| `__DATA.__data` | `0x1022` | `0x10aa` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0x4cb0` | `0x4d00` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x1540` | `0x158c` | **`+0x4c`** |
| `__DATA_DIRTY.__data` | `0xa68` | `0xaa0` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x1140` | `0x1170` | **`+0x30`** |
| `__TEXT.__const` | `0x5bf8` | `0x5c28` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x15fa` | `0x161e` | **`+0x24`** |
| `__TEXT.__swift5_fieldmd` | `0x19b8` | `0x19d4` | **`+0x1c`** |
| `__DATA_CONST.__objc_protolist` | `0x18` | `0x30` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x60c` | `0x624` | **`+0x18`** |
| `__DATA_CONST.__objc_protorefs` | `0x8` | `0x18` | **`+0x10`** |
| `__TEXT.__cstring` | `0x68da` | `0x68ca` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x21e3` | `0x21f3` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x17c0` | `0x17d0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x558` | `0x560` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xb8` | `0xc0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1c8` | `0x1cc` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-81.0.0.0.0
+82.0.0.0.0

-  Functions: 2226
-  Symbols:   1445
-  CStrings:  1085
+  Functions: 2235
+  Symbols:   1453
+  CStrings:  1084
Symbols:
+ __DATA__TtCFC15CoreDiagnostics22AppleIntelligenceStateP33_088BB0F0F87A4F30D60030036C3E7D2E28updateAppleIntelligenceStateFT_T_L_14XPCQueryResult
+ __IVARS__TtCFC15CoreDiagnostics22AppleIntelligenceStateP33_088BB0F0F87A4F30D60030036C3E7D2E28updateAppleIntelligenceStateFT_T_L_14XPCQueryResult
+ __METACLASS_DATA__TtCFC15CoreDiagnostics22AppleIntelligenceStateP33_088BB0F0F87A4F30D60030036C3E7D2E28updateAppleIntelligenceStateFT_T_L_14XPCQueryResult
+ __OBJC_$_PROTOCOL_REFS_OS_xpc_object
+ __OBJC_LABEL_PROTOCOL_$_OS_xpc_object
+ __OBJC_PROTOCOL_$_OS_xpc_object
+ _flat unique So13OS_xpc_object_p
+ _symbolic _____ 15CoreDiagnostics22AppleIntelligenceStateC06updatecdE033_088BB0F0F87A4F30D60030036C3E7D2ELLyyF14XPCQueryResultL_C
+ _symbolic ______pSg So13OS_xpc_objectP
- _xpc_dictionary_get_dictionary
CStrings:
+ "AnalyticsQueryValuesFor returned non-dictionary result"
+ "AnalyticsQueryValuesFor timed out after 10s; clearing AI state"
- "Analytics query xpc_object is not of type dictionary"
- "Failed to query generative models dictionary"
- "greymatter"
```
