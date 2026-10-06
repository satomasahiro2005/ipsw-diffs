## FaceTimeMessageStore

> `/System/Library/PrivateFrameworks/FaceTimeMessageStore.framework/FaceTimeMessageStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x176168` | `0x177014` | **`+0xeac`** |
| `__TEXT.__oslogstring` | `0x933b` | `0x94bb` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0xbcc8` | `0xbd20` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x54a8` | `0x54d8` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x4a68` | `0x4a90` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0xd8d4` | `0xd8f4` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1790` | `0x17a8` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x41c8` | `0x41e0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x15b8` | `0x15d0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x6260` | `0x6278` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1860` | `0x1850` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x48c0` | `0x48b0` | **`-0x10`** |

### Other Changes

```diff

-1608.100.12.2.6
+1612.100.3.2.1

-  Functions: 9888
-  Symbols:   2709
-  CStrings:  859
+  Functions: 9901
+  Symbols:   2707
+  CStrings:  863
Symbols:
+ _symbolic SccySo21SCSensitivityAnalysisC______pG s5ErrorP
- _OUTLINED_FUNCTION_317
- _OUTLINED_FUNCTION_318
- _OUTLINED_FUNCTION_319
CStrings:
+ "No duplicate notifications found for %{public}@. Adding to postedNotificationIdentifiers"
+ "Platform does not support posting notification for message: %{public}@"
+ "Released posted notification identifier for %{public}@"
+ "We're already attempting to post (or have already posted) a notification for message: %{public}@. Should not post another notification"
```
