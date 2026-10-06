## ChronoUIServices

> `/System/Library/PrivateFrameworks/ChronoUIServices.framework/ChronoUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x963a4` | `0x96bec` | **`+0x848`** |
| `__TEXT.__gcc_except_tab` | `0x4290` | `0x43c0` | **`+0x130`** |
| `__AUTH_CONST.__objc_const` | `0x98c0` | `0x9950` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x3324` | `0x33b4` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x3358` | `0x33c8` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x1ae0` | `0x1b20` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x3065` | `0x30a5` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e38` | `0x1e68` | **`+0x30`** |
| `__TEXT.__cstring` | `0x22d1` | `0x2301` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xd30` | `0xd40` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2e0` | `0x2e4` | **`+0x4`** |

### Other Changes

```diff

-740.0.0.0.0
+749.0.1.0.0

-  Functions: 3744
-  Symbols:   3046
-  CStrings:  504
+  Functions: 3757
+  Symbols:   3066
+  CStrings:  507
Symbols:
+ -[CHUISMutableWidgetSceneSettings foregroundEvictionPriority]
+ -[CHUISMutableWidgetSceneSettings secondHandFPSOverride]
+ -[CHUISMutableWidgetSceneSettings setForegroundEvictionPriority:]
+ -[CHUISMutableWidgetSceneSettings setSecondHandFPSOverride:]
+ -[CHUISWidgetHostViewController _updateForegroundEvictionPriority]
+ -[CHUISWidgetHostViewController secondHandFPSOverride]
+ -[CHUISWidgetHostViewController setSecondHandFPSOverride:]
+ -[CHUISWidgetScene foregroundEvictionPriority]
+ -[CHUISWidgetScene secondHandFPSOverride]
+ -[CHUISWidgetSceneSettings foregroundEvictionPriority]
+ -[CHUISWidgetSceneSettings secondHandFPSOverride]
+ -[CHUISWidgetSceneSettingsDiffInspector observeSecondHandFPSOverrideWithBlock:]
+ GCC_except_table106
+ GCC_except_table108
+ GCC_except_table109
+ GCC_except_table110
+ GCC_except_table113
+ GCC_except_table124
+ GCC_except_table129
+ GCC_except_table130
+ GCC_except_table135
+ GCC_except_table139
+ GCC_except_table142
+ GCC_except_table143
+ GCC_except_table149
+ GCC_except_table153
+ GCC_except_table156
+ GCC_except_table157
+ GCC_except_table163
+ GCC_except_table181
+ GCC_except_table182
+ GCC_except_table185
+ GCC_except_table190
+ GCC_except_table194
+ GCC_except_table197
+ GCC_except_table198
+ GCC_except_table202
+ GCC_except_table203
+ GCC_except_table210
+ GCC_except_table211
+ GCC_except_table221
+ GCC_except_table229
+ GCC_except_table232
+ GCC_except_table233
+ GCC_except_table240
+ GCC_except_table246
+ GCC_except_table247
+ GCC_except_table252
+ GCC_except_table253
+ GCC_except_table260
+ GCC_except_table261
+ GCC_except_table267
+ GCC_except_table268
+ GCC_except_table272
+ GCC_except_table278
+ GCC_except_table290
+ GCC_except_table291
+ GCC_except_table292
+ GCC_except_table293
+ GCC_except_table298
+ GCC_except_table299
+ GCC_except_table301
+ GCC_except_table330
+ GCC_except_table332
+ GCC_except_table339
+ GCC_except_table340
+ GCC_except_table341
+ GCC_except_table343
+ GCC_except_table350
+ GCC_except_table351
+ GCC_except_table352
+ GCC_except_table353
+ GCC_except_table36
+ GCC_except_table39
+ _OBJC_IVAR_$_CHUISWidgetHostViewController._secondHandFPSOverride
+ ___58-[CHUISWidgetHostViewController setSecondHandFPSOverride:]_block_invoke
+ ___66-[CHUISWidgetHostViewController _updateForegroundEvictionPriority]_block_invoke
- GCC_except_table126
- GCC_except_table127
- GCC_except_table131
- GCC_except_table137
- GCC_except_table140
- GCC_except_table141
- GCC_except_table145
- GCC_except_table146
- GCC_except_table151
- GCC_except_table155
- GCC_except_table161
- GCC_except_table176
- GCC_except_table177
- GCC_except_table183
- GCC_except_table184
- GCC_except_table187
- GCC_except_table192
- GCC_except_table196
- GCC_except_table200
- GCC_except_table201
- GCC_except_table204
- GCC_except_table207
- GCC_except_table217
- GCC_except_table218
- GCC_except_table223
- GCC_except_table231
- GCC_except_table236
- GCC_except_table242
- GCC_except_table243
- GCC_except_table250
- GCC_except_table251
- GCC_except_table254
- GCC_except_table255
- GCC_except_table265
- GCC_except_table266
- GCC_except_table270
- GCC_except_table274
- GCC_except_table275
- GCC_except_table282
- GCC_except_table283
- GCC_except_table284
- GCC_except_table294
- GCC_except_table295
- GCC_except_table297
- GCC_except_table325
- GCC_except_table326
- GCC_except_table327
- GCC_except_table328
- GCC_except_table334
- GCC_except_table335
- GCC_except_table345
- GCC_except_table346
- GCC_except_table347
- GCC_except_table348
- GCC_except_table37
- GCC_except_table40
- GCC_except_table41
CStrings:
+ "[%p-%{public}@] Ignoring unreasonable secondHandFPSOverride: %f."
+ "foregroundEvictionPriority"
+ "secondHandFPSOverride"
```
