## SoftwareUpdateUIFoundation

> `/System/Library/PrivateFrameworks/SoftwareUpdateUIFoundation.framework/SoftwareUpdateUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xad4d4` | `0xae414` | **`+0xf40`** |
| `__TEXT.__oslogstring` | `0xaab7` | `0xad07` | **`+0x250`** |
| `__TEXT.__cstring` | `0x6d48` | `0x6d98` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x3f40` | `0x3f80` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1200` | `0x1218` | **`+0x18`** |

### Other Changes

```diff

-772.0.20.0.0
+772.40.11.0.0

-  Functions: 2096
-  Symbols:   2307
-  CStrings:  967
+  Functions: 2099
+  Symbols:   2310
+  CStrings:  975
Symbols:
+ GCC_except_table29
+ GCC_except_table33
+ _SUUIStatefulDescriptorDataLengthDescription
+ ___block_descriptor_65_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
+ ___os_log_helper_16_2_3_8_32_8_32_8_66
+ ___os_log_helper_16_2_6_8_32_8_66_8_66_8_0_8_66_8_66
- GCC_except_table27
- GCC_except_table32
- ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
CStrings:
+ "%lu"
+ "%s [%{public}@, %{public}@, %p]: Documentation comparison found a mismatch in licenseAgreement (current length: %{public}@, new length: %{public}@)"
+ "%s [%{public}@, %{public}@, %p]: Documentation comparison found a mismatch in releaseNotes (current length: %{public}@, new length: %{public}@)"
+ "%s [%{public}@, %{public}@, %p]: Documentation comparison found a mismatch in releaseNotesSummary (current length: %{public}@, new length: %{public}@)"
+ "%s [%{public}@, %{public}@, %p]: Documentation comparison found a mismatch in updateIcon (current length: %{public}@, new length: %{public}@)"
+ "%s: %s is nil in %{public}@. Stopping."
+ "-[SUUIStatefulDescriptor isEqualToDescriptor:includeDocumentationComparison:]"
+ "nil"
+ "self"
- "%s: Self is nil in %{public}@. Stopping."
```
