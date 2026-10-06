## SIMSetupSupport

> `/System/Library/PrivateFrameworks/SIMSetupSupport.framework/SIMSetupSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe6b10` | `0xe6d4c` | **`+0x23c`** |
| `__AUTH_CONST.__objc_const` | `0x4f8b8` | `0x4f8f8` | **`+0x40`** |
| `__TEXT.__cstring` | `0x17a03` | `0x179ce` | **`-0x35`** |
| `__AUTH_CONST.__cfstring` | `0xae00` | `0xade0` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x5f78` | `0x5f88` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xc81c` | `0xc82c` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1354` | `0x135c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x30a8` | `0x30b0` | **`+0x8`** |

### Other Changes

```diff

-980.0.0.0.0
+982.0.0.0.0

-  Functions: 4977
-  Symbols:   7999
-  CStrings:  3149
+  Functions: 4979
+  Symbols:   8003
+  CStrings:  3148
Symbols:
+ -[SSQuickSwitchSecondaryEnrollmentFlow _isQSBootstrapErrorFromPreQSSource:]
+ -[TSCellularPlanActivatingFlow(Override) _maybeHideBackButtonForQuickSwitch:]
+ GCC_except_table133
+ GCC_except_table135
+ GCC_except_table139
+ GCC_except_table145
+ GCC_except_table154
+ GCC_except_table161
+ GCC_except_table169
+ GCC_except_table203
+ GCC_except_table206
+ GCC_except_table214
+ GCC_except_table216
+ GCC_except_table218
+ _OBJC_IVAR_$_SSQuickSwitchSecondaryEnrollmentFlow._shouldCheckDisplayPlansForQS
+ _OBJC_IVAR_$_TSActivationFlowWithSimSetupFlow._qsQuerySucceededWithNoAccounts
- GCC_except_table132
- GCC_except_table134
- GCC_except_table138
- GCC_except_table144
- GCC_except_table152
- GCC_except_table160
- GCC_except_table168
- GCC_except_table202
- GCC_except_table205
- GCC_except_table213
- GCC_except_table215
- GCC_except_table217
CStrings:
+ "27.0"
- "QS_APPLE_ACCOUNTS_MISMATCH_TITLE"
- "QS_ICLOUD_MISMATCH_TITLE"
```
