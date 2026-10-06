## ComputeSafeguards

> `/System/Library/PrivateFrameworks/ComputeSafeguards.framework/ComputeSafeguards`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b188` | `0x5b3b0` | **`+0x228`** |
| `__AUTH_CONST.__objc_const` | `0x61b0` | `0x61e0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4644` | `0x466c` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x6340` | `0x6360` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a28` | `0x2a40` | **`+0x18`** |
| `__TEXT.__cstring` | `0x6144` | `0x6155` | **`+0x11`** |
| `__TEXT.__unwind_info` | `0x1098` | `0x10a0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x530` | `0x534` | **`+0x4`** |

### Other Changes

```diff

-177.0.16.0.0
+177.40.5.0.0

-  Functions: 2069
-  Symbols:   2696
-  CStrings:  1876
+  Functions: 2073
+  Symbols:   2702
+  CStrings:  1877
Symbols:
+ -[CSMitigationManager isMitigationInternalOnlyForRule:]
+ -[CSProcess setViolationRuleID:]
+ -[CSProcess violationRuleID]
+ GCC_except_table56
+ GCC_except_table58
+ _OBJC_IVAR_$_CSProcess._violationRuleID
+ _getCSExternalRuleMitigationPolicies
- GCC_except_table69
CStrings:
+ "InternalOnlyRule"
+ "[Q$"
- "KQ$"
```
