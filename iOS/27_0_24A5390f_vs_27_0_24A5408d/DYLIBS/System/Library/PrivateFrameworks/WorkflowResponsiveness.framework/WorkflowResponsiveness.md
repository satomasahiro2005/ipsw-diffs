## WorkflowResponsiveness

> `/System/Library/PrivateFrameworks/WorkflowResponsiveness.framework/WorkflowResponsiveness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x40c68` | `0x40158` | **`-0xb10`** |
| `__TEXT.__cstring` | `0x8dff` | `0x8c39` | **`-0x1c6`** |
| `__TEXT.__oslogstring` | `0x5e6f` | `0x5cf9` | **`-0x176`** |
| `__AUTH_CONST.__cfstring` | `0x54a0` | `0x53a0` | **`-0x100`** |
| `__TEXT.__unwind_info` | `0x648` | `0x708` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x18e4` | `0x18bc` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x380` | `0x360` | **`-0x20`** |
| `__DATA.__bss` | `0x20` | `0x10` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x9d0` | `0x9c8` | **`-0x8`** |

### Other Changes

```diff

-445.0.0.0.0
+448.0.0.0.0

-  Functions: 749
-  Symbols:   1191
-  CStrings:  720
+  Functions: 742
+  Symbols:   1189
+  CStrings:  712
Symbols:
+ GCC_except_table18
+ GCC_except_table5
- GCC_except_table17
- __WRAllowedAdditionalWorkflowNames.allowedNames
- __WRAllowedAdditionalWorkflowNames.onceToken
- ____WRAllowedAdditionalWorkflowNames_block_invoke
CStrings:
- "/System/Library/WorkflowResponsiveness/WorkflowAllowList.plist"
- "Allow list at %{public}@ is not a dictionary (root is %{public}s)"
- "Allow list plist at %{public}@ has non-array %{public}@ key (value is %{public}s)"
- "Allow list plist at %{public}@ is missing %{public}@ key"
- "AllowedWorkflows"
- "Non-string entry in allow list %{public}@ (entry is %{public}s)"
- "Unable to parse allow list at %{public}@: %{public}@"
- "Unable to read allow list at %{public}@: %{public}@"
```
