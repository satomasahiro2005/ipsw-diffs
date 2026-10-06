## MediaAnalysisServices

> `/System/Library/PrivateFrameworks/MediaAnalysisServices.framework/MediaAnalysisServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3dad4` | `0x3def4` | **`+0x420`** |
| `__TEXT.__gcc_except_tab` | `0x4458` | `0x44f4` | **`+0x9c`** |
| `__TEXT.__cstring` | `0x3ba5` | `0x3bcd` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x4de0` | `0x4e00` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x19d0` | `0x19f0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x5024` | `0x5034` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x518` | `0x520` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1c60` | `0x1c68` | **`+0x8`** |

### Other Changes

```diff

-460.8.2.0.0
+460.12.1.0.0

-  Functions: 1743
-  Symbols:   3476
-  CStrings:  871
+  Functions: 1744
+  Symbols:   3481
+  CStrings:  872
Symbols:
+ -[MADService fileTypeForURL:]
+ GCC_except_table109
+ GCC_except_table111
+ GCC_except_table120
+ GCC_except_table126
+ GCC_except_table134
+ GCC_except_table137
+ GCC_except_table149
+ GCC_except_table152
+ GCC_except_table155
+ GCC_except_table157
+ GCC_except_table159
+ GCC_except_table161
+ GCC_except_table163
+ GCC_except_table166
+ GCC_except_table173
+ GCC_except_table184
+ GCC_except_table189
+ GCC_except_table192
+ GCC_except_table69
+ GCC_except_table73
+ GCC_except_table75
+ GCC_except_table82
+ _OBJC_CLASS_$_NSFileHandle
- GCC_except_table110
- GCC_except_table112
- GCC_except_table121
- GCC_except_table127
- GCC_except_table136
- GCC_except_table146
- GCC_except_table151
- GCC_except_table154
- GCC_except_table156
- GCC_except_table158
- GCC_except_table160
- GCC_except_table162
- GCC_except_table164
- GCC_except_table167
- GCC_except_table174
- GCC_except_table187
- GCC_except_table190
- GCC_except_table72
- GCC_except_table90
Functions:
+ -[MADService fileTypeForURL:]
~ -[MADService performRequests:onImageURL:withIdentifier:completionHandler:] : 832 -> 852
~ -[MADService performRequests:onImageURL:withIdentifier:error:] : 1012 -> 1068
~ -[MADService performRequests:videoURL:identifier:progressHandler:completionHandler:] : 872 -> 1628
CStrings:
+ "Could not determine a media type for %@"
```
