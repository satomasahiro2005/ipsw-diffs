## SoftwareUpdateUIMobile

> `/System/Library/PrivateFrameworks/SoftwareUpdateUIMobile.framework/SoftwareUpdateUIMobile`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ca5c` | `0x7d79c` | **`+0xd40`** |
| `__DATA_CONST.__const` | `0x8c68` | `0x8ef8` | **`+0x290`** |
| `__TEXT.__cstring` | `0x4647` | `0x46c7` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x84a0` | `0x8500` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x1f20` | `0x1f60` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xe08` | `0xe30` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x195c` | `0x1978` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x1840` | `0x1848` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x26bc` | `0x26c4` | **`+0x8`** |

### Other Changes

```diff

-772.0.0.0.0
+772.0.3.0.0

-  Functions: 1124
-  Symbols:   1937
-  CStrings:  683
+  Functions: 1129
+  Symbols:   1944
+  CStrings:  687
Symbols:
+ -[SUUIMobileUpdateOperation _waitForScanCompletionWithEventInfo:onSuccess:failureEvent:]
+ GCC_except_table19
+ GCC_except_table37
+ GCC_except_table46
+ GCC_except_table49
+ GCC_except_table50
+ GCC_except_table53
+ GCC_except_table58
+ GCC_except_table72
+ GCC_except_table75
+ GCC_except_table81
+ GCC_except_table84
+ _MA_KNOX_URL_OVERRIDE_DEFAULT_KEY
+ _MA_WKMS_URL_OVERRIDE_DEFAULT_KEY
+ ___88-[SUUIMobileUpdateOperation _waitForScanCompletionWithEventInfo:onSuccess:failureEvent:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48bs56w_e20_v20?0B8"NSError"12lw56l8s32l8s48l8s40l8
+ ___block_descriptor_73_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s64l8s48l8s56l8
- GCC_except_table13
- GCC_except_table17
- GCC_except_table36
- GCC_except_table41
- GCC_except_table45
- GCC_except_table48
- GCC_except_table59
- GCC_except_table68
- GCC_except_table73
- GCC_except_table79
CStrings:
+ "%s [->%{public}@]: Controller is still scanning after waiting. Reporting ScanInProgress error for event: %{public}@."
+ "%s [->%{public}@]: Failed to check isScanning status: %{public}@. Proceeding with operation."
+ "%s [->%{public}@]: Scan wait completed, proceeding with operation."
+ "-[SUUIMobileUpdateOperation _waitForScanCompletionWithEventInfo:onSuccess:failureEvent:]_block_invoke"
+ "KnoxURLOverride"
+ "WKMSURLOverride"
- "%s: Controller is still scanning after waiting. Reporting ScanInProgress error."
- "%s: Failed to check isScanning status: %{public}@. Proceeding with download anyway (best effort)."
```
