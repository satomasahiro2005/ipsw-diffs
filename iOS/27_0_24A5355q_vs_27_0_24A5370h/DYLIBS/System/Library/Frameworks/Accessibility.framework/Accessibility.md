## Accessibility

> `/System/Library/Frameworks/Accessibility.framework/Accessibility`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x176e8` | `0x17ba4` | **`+0x4bc`** |
| `__AUTH_CONST.__const` | `0xae8` | `0xc20` | **`+0x138`** |
| `__TEXT.__const` | `0x12d0` | `0x1378` | **`+0xa8`** |
| `__DATA.__bss` | `0x1590` | `0x1620` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x28c` | `0x2e0` | **`+0x54`** |
| `__TEXT.__cstring` | `0x1163` | `0x11b2` | **`+0x4f`** |
| `__TEXT.__swift5_typeref` | `0x38a` | `0x3d8` | **`+0x4e`** |
| `__TEXT.__unwind_info` | `0x940` | `0x970` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x30c` | `0x338` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x5e8` | `0x610` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xd20` | `0xd40` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x210` | `0x228` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x2ac` | `0x2c4` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA.__data` | `0x388` | `0x398` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x358` | `0x368` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x418` | `0x420` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x218` | `0x220` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa70` | `0xa78` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x100` | `0x104` | **`+0x4`** |

### Other Changes

```diff

-576.1.0.0.0
+579.1.0.0.0

-  Functions: 881
-  Symbols:   1312
-  CStrings:  207
+  Functions: 896
+  Symbols:   1329
+  CStrings:  209
Symbols:
+ GCC_except_table102
+ GCC_except_table167
+ GCC_except_table176
+ GCC_except_table211
+ GCC_except_table214
+ GCC_except_table245
+ GCC_except_table246
+ GCC_except_table247
+ GCC_except_table248
+ GCC_except_table249
+ GCC_except_table273
+ GCC_except_table274
+ GCC_except_table337
+ GCC_except_table338
+ GCC_except_table339
+ GCC_except_table340
+ GCC_except_table341
+ GCC_except_table355
+ GCC_except_table388
+ GCC_except_table389
+ GCC_except_table390
+ GCC_except_table391
+ GCC_except_table392
+ GCC_except_table404
+ GCC_except_table411
+ GCC_except_table451
+ GCC_except_table466
+ _AXApplicationAccessibilityEnabled
+ _AXApplicationAccessibilityEnabledDidChangeNotification
+ __AXApplicationAccessibilityEnabledChangedCallback
+ __AXBeginObservingApplicationAccessibilityEnabledChanges.onceToken
+ ____AXApplicationAccessibilityEnabledChangedCallback_block_invoke
+ ____AXBeginObservingApplicationAccessibilityEnabledChanges_block_invoke
+ ___get_AXSApplicationAccessibilityEnabledSymbolLoc_block_invoke
+ __dispatch_main_q
+ _dispatch_async
+ _get_AXSApplicationAccessibilityEnabledSymbolLoc.ptr
+ _swift_getForeignTypeMetadata
+ _symbolic $sSo20NSNotificationCenterC10FoundationE16MainActorMessageP
+ _symbolic SvSg
+ _symbolic _____ So21AccessibilitySettingsV
+ _symbolic _____ So21AccessibilitySettingsV0A0E011ApplicationA23EnabledDidChangeMessageV
+ _type_layout_string So21AccessibilitySettingsV
- GCC_except_table162
- GCC_except_table171
- GCC_except_table206
- GCC_except_table209
- GCC_except_table238
- GCC_except_table239
- GCC_except_table240
- GCC_except_table241
- GCC_except_table242
- GCC_except_table268
- GCC_except_table269
- GCC_except_table329
- GCC_except_table330
- GCC_except_table331
- GCC_except_table332
- GCC_except_table333
- GCC_except_table350
- GCC_except_table381
- GCC_except_table382
- GCC_except_table383
- GCC_except_table384
- GCC_except_table385
- GCC_except_table399
- GCC_except_table406
- GCC_except_table446
- GCC_except_table461
CStrings:
+ "_AXSApplicationAccessibilityEnabled"
+ "com.apple.accessibility.application.status"
```
