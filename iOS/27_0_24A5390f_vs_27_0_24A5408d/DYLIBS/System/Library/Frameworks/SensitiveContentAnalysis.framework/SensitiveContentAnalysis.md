## SensitiveContentAnalysis

> `/System/Library/Frameworks/SensitiveContentAnalysis.framework/SensitiveContentAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd87ac` | `0xd8b80` | **`+0x3d4`** |
| `__TEXT.__eh_frame` | `0x7c84` | `0x7c54` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x7cb8` | `0x7ce0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xf74` | `0xf9c` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xb48` | `0xb60` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4078` | `0x4090` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x3912` | `0x3924` | **`+0x12`** |
| `__AUTH_CONST.__objc_const` | `0x35f8` | `0x3608` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x540` | `0x550` | **`+0x10`** |
| `__TEXT.__cstring` | `0x2867` | `0x2877` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x22d9` | `0x22e9` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x12d8` | `0x12e8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x44c` | `0x43c` | **`-0x10`** |

### Other Changes

```diff

-148.0.0.0.0
+151.0.0.0.0

-  Functions: 5085
-  Symbols:   2308
-  CStrings:  467
+  Functions: 5093
+  Symbols:   2312
+  CStrings:  468
Symbols:
+ -[SCSensitivityAnalyzer _optionsByApplyingGoreAndViolenceEnablement:]
+ -[SCSensitivityAnalyzer gvEnabled]
+ -[SCSensitivityAnalyzer setGvEnabled:]
+ _symbolic ytSg______pIgrzo_ s5ErrorP
CStrings:
+ ".userOptedToHide"
+ "analyzeImageFile: starting analysis for fileURL=%{[private]}@, options=%lu"
- "analyzeImageFile: starting analysis for fileURL=%{[private]}@"
```
