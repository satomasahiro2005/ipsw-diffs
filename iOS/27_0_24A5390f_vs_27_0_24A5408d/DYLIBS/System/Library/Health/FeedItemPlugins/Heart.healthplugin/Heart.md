## Heart

> `/System/Library/Health/FeedItemPlugins/Heart.healthplugin/Heart`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2eacf0` | `0x2ebfbc` | **`+0x12cc`** |
| `__AUTH_CONST.__const` | `0x13048` | `0x131a0` | **`+0x158`** |
| `__TEXT.__cstring` | `0x12f4e` | `0x1307e` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0x89b8` | `0x8a30` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0x3708` | `0x3770` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x75d6` | `0x763a` | **`+0x64`** |
| `__TEXT.__eh_frame` | `0x6fd4` | `0x7034` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x9aa1` | `0x9a41` | **`-0x60`** |
| `__DATA.__data` | `0x7b28` | `0x7b58` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0xcbbc` | `0xcbe8` | **`+0x2c`** |
| `__AUTH_CONST.__objc_const` | `0xe4b0` | `0xe4d8` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x49b8` | `0x49d0` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x81a6` | `0x81b6` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x7a7c` | `0x7a88` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d10` | `0x1d18` | **`+0x8`** |

### Other Changes

```diff

-7027.0.67.2.1
+7027.0.72.2.5

-  Functions: 12619
-  Symbols:   683
-  CStrings:  2188
+  Functions: 12647
+  Symbols:   685
+  CStrings:  2190
Symbols:
+ _OBJC_CLASS_$_HKSampleCountQuery
+ _swift_task_getMainExecutor
+ _swift_task_isCurrentExecutor
- _HKFeatureAvailabilityRequirementIdentifierSomeRegionIsSupported
CStrings:
+ "Heart/HeartRateVariabilityDataTypeDetailConfigurationProvider.swift"
+ "Incorrect actor executor assumption; Expected same executor as "
+ "苹果贸易(上海)有限公司\n中国（上海）自由贸易试验区世纪大道1249号15层A区、16层(实际楼层13层A区、14层)"
- "[%s.%s] Not creating feature status configuration due to region list being empty"
```
