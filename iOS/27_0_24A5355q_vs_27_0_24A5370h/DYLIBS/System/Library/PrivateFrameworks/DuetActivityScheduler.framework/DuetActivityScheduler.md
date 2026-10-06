## DuetActivityScheduler

> `/System/Library/PrivateFrameworks/DuetActivityScheduler.framework/DuetActivityScheduler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f134` | `0x3efe4` | **`-0x150`** |
| `__TEXT.__objc_methlist` | `0x4990` | `0x49e8` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x7f18` | `0x7f58` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x12c0` | `0x12f8` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x2948` | `0x2960` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x49c` | `0x4a0` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x156c` | `0x1568` | **`-0x4`** |

### Other Changes

```diff

-2463.0.0.502.1
+2467.0.9.0.0

-  Functions: 1683
-  Symbols:   2837
+  Functions: 1686
+  Symbols:   2844
Symbols:
+ -[_DASActivity policyBypassEnabled]
+ -[_DASActivity setPolicyBypassEnabled:]
+ -[_DASScheduler forceRunActivities:bypassingPolicies:]
+ GCC_except_table105
+ GCC_except_table109
+ GCC_except_table112
+ GCC_except_table115
+ GCC_except_table118
+ GCC_except_table124
+ GCC_except_table136
+ GCC_except_table139
+ GCC_except_table147
+ GCC_except_table157
+ GCC_except_table190
+ GCC_except_table221
+ GCC_except_table224
+ GCC_except_table227
+ GCC_except_table230
+ GCC_except_table233
+ GCC_except_table236
+ GCC_except_table246
+ GCC_except_table249
+ GCC_except_table252
+ GCC_except_table255
+ GCC_except_table258
+ GCC_except_table261
+ GCC_except_table264
+ GCC_except_table267
+ GCC_except_table270
+ GCC_except_table273
+ GCC_except_table276
+ GCC_except_table279
+ GCC_except_table282
+ GCC_except_table285
+ GCC_except_table288
+ GCC_except_table291
+ GCC_except_table294
+ GCC_except_table297
+ GCC_except_table300
+ GCC_except_table303
+ GCC_except_table306
+ GCC_except_table309
+ GCC_except_table312
+ GCC_except_table315
+ GCC_except_table318
+ GCC_except_table68
+ GCC_except_table71
+ GCC_except_table74
+ GCC_except_table77
+ GCC_except_table80
+ GCC_except_table87
+ GCC_except_table90
+ GCC_except_table93
+ GCC_except_table96
+ _OBJC_CLASS_$_NSHashTable
+ _OBJC_IVAR_$__DASActivity._policyBypassEnabled
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT__DASActivitySchedulerIntrospecting
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT__DASActivitySchedulerIntrospectingServer
+ ___54-[_DASScheduler forceRunActivities:bypassingPolicies:]_block_invoke
- GCC_except_table104
- GCC_except_table108
- GCC_except_table111
- GCC_except_table114
- GCC_except_table117
- GCC_except_table135
- GCC_except_table142
- GCC_except_table144
- GCC_except_table156
- GCC_except_table189
- GCC_except_table220
- GCC_except_table223
- GCC_except_table226
- GCC_except_table229
- GCC_except_table232
- GCC_except_table235
- GCC_except_table245
- GCC_except_table248
- GCC_except_table251
- GCC_except_table254
- GCC_except_table257
- GCC_except_table260
- GCC_except_table263
- GCC_except_table266
- GCC_except_table269
- GCC_except_table272
- GCC_except_table275
- GCC_except_table278
- GCC_except_table281
- GCC_except_table284
- GCC_except_table287
- GCC_except_table290
- GCC_except_table293
- GCC_except_table296
- GCC_except_table299
- GCC_except_table302
- GCC_except_table305
- GCC_except_table308
- GCC_except_table311
- GCC_except_table314
- GCC_except_table317
- GCC_except_table67
- GCC_except_table70
- GCC_except_table73
- GCC_except_table76
- GCC_except_table79
- GCC_except_table86
- GCC_except_table89
- GCC_except_table92
- GCC_except_table95
- _OBJC_CLASS_$_NSMapTable
- ___36-[_DASScheduler forceRunActivities:]_block_invoke
```
