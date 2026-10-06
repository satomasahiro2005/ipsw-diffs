## FrontBoard

> `/System/Library/PrivateFrameworks/FrontBoard.framework/FrontBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x840ac` | `0x844c8` | **`+0x41c`** |
| `__AUTH_CONST.__objc_const` | `0xb650` | `0xb690` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x5a98` | `0x5ab0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3828` | `0x3838` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2010` | `0x2020` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x954` | `0x958` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1153.0.1.0.0
+1153.2.1.0.0

-  Functions: 3170
-  Symbols:   4766
+  Functions: 3172
+  Symbols:   4769
Symbols:
+ -[FBProcessExecutionContext developerToolsOptions]
+ -[FBProcessExecutionContext setDeveloperToolsOptions:]
+ _OBJC_IVAR_$_FBProcessExecutionContext._developerToolsOptions
+ ___block_descriptor_73_e8_32s40s48s56s64s_e63_v24?0"FBSMutableSceneSettings"8"FBSSceneTransitionContext"16ls32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_72_e8_32s40s48s56s64s_e63_v24?0"FBSMutableSceneSettings"8"FBSSceneTransitionContext"16ls32l8s40l8s48l8s56l8s64l8
```
