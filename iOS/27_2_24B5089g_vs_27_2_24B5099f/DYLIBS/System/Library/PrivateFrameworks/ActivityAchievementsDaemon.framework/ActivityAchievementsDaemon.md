## ActivityAchievementsDaemon

> `/System/Library/PrivateFrameworks/ActivityAchievementsDaemon.framework/ActivityAchievementsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76198` | `0x76290` | **`+0xf8`** |
| `__AUTH_CONST.__const` | `0xc90` | `0xc70` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3800` | `0x3810` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1ef0` | `0x1ee0` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2178` | `0x217c` | **`+0x4`** |

### Other Changes

```diff

-2027.1.3.0.0
+2027.1.4.0.0

-  Functions: 2825
+  Functions: 2824
Symbols:
+ +[ACHEarnedInstanceEntity earnedInstancesFromDateComponentsString:toDateComponentsString:profile:error:]
+ -[ACHAwardsServer remote_fetchEarnedInstancesFromDateComponentsString:toDateComponentsString:completion:]
+ GCC_except_table55
+ GCC_except_table60
+ _ACHEarnedInstanceCompoundPredicateForEarnedDateComponentsStringRange
+ ___105-[ACHAwardsServer remote_fetchEarnedInstancesFromDateComponentsString:toDateComponentsString:completion:]_block_invoke
+ ___105-[ACHAwardsServer remote_fetchEarnedInstancesFromDateComponentsString:toDateComponentsString:completion:]_block_invoke_2
- +[ACHEarnedInstanceEntity earnedInstancesForDateComponentStringsArray:profile:error:]
- -[ACHAwardsServer remote_fetchEarnedInstancesForDateComponentStringsArray:completion:]
- GCC_except_table61
- _ACHEarnedInstanceCompoundPredicateForDateComponentStringsArray
- ___86-[ACHAwardsServer remote_fetchEarnedInstancesForDateComponentStringsArray:completion:]_block_invoke
- ___86-[ACHAwardsServer remote_fetchEarnedInstancesForDateComponentStringsArray:completion:]_block_invoke_2
- ___ACHEarnedInstanceCompoundPredicateForDateComponentStringsArray_block_invoke
```
