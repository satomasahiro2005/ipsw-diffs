## RenderBox

> `/System/Library/PrivateFrameworks/RenderBox.framework/RenderBox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16e6d8` | `0x16f86c` | **`+0x1194`** |
| `__AUTH_CONST.__const` | `0xa5f8` | `0xa748` | **`+0x150`** |
| `__TEXT.__gcc_except_tab` | `0x7f94` | `0x80b8` | **`+0x124`** |
| `__TEXT.__unwind_info` | `0x73e0` | `0x7490` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x68d0` | `0x6888` | **`-0x48`** |
| `__TEXT.__oslogstring` | `0x12a5` | `0x12ca` | **`+0x25`** |
| `__DATA.__bss` | `0x2c8` | `0x2d8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f50` | `0x1f40` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x5c8` | `0x5b8` | **`-0x10`** |
| `__TEXT.__const` | `0x6030` | `0x6040` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1500` | `0x14f8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x890` | `0x888` | **`-0x8`** |

### Other Changes

```diff

-8.0.79.0.0
+8.0.84.0.0

-  Functions: 7671
-  Symbols:   10021
-  CStrings:  1779
+  Functions: 7705
+  Symbols:   10059
+  CStrings:  1778
Symbols:
+ -[CALayer kitScreenAllowingSystemID:]
+ GCC_except_table170
+ GCC_except_table78
+ _RBPathCopyBooleanPath
+ _RBPathCopyOffsetPath
+ __ZL10uiview_cls
+ __ZL11screen_once
+ __ZN12_GLOBAL__N_114AnimationTimer17dispatch_handlersE13RBDisplayTypeP11objc_objectjddRNSt3__111unique_lockIN2RB9spin_lockEEE
+ __ZN2RB4Path6Mapper20IntermediateConsumer6cubetoEDv2_dS3_S3_
+ __ZN2RB4Path6Mapper20IntermediateConsumer6linetoEDv2_d
+ __ZN2RB4Path6Mapper20IntermediateConsumer6movetoEDv2_d
+ __ZN2RB4Path6Mapper20IntermediateConsumer6quadtoEDv2_dS3_
+ __ZN2RB4Path6Mapper20IntermediateConsumer7endpathEv
+ __ZN2RB4Path6Mapper20IntermediateConsumer9closepathEv
+ __ZN2RB7details14realloc_vectorImLm48EEEPvS2_S2_T_RS3_S3_y
+ __ZN2RB8RefcountIZ21RBPathCopyBooleanPathE4InfoNSt3__16atomicIjEEE7releaseEv
+ __ZN2RB8RefcountIZ21RBPathCopyBooleanPathE4InfoNSt3__16atomicIjEEE8finalizeEv
+ __ZN2RB8RefcountIZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS4_OT_E4InfoNSt3__16atomicIjEEE7releaseEv
+ __ZN2RB8RefcountIZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS4_OT_E4InfoNSt3__16atomicIjEEE8finalizeEv
+ __ZNSt3__118condition_variable10wait_untilB9fqn220106INS_6chrono12steady_clockENS2_8durationIxNS_5ratioILl1ELl1000000000EEEEEEENS_9cv_statusERNS_11unique_lockINS_5mutexEEERKNS2_10time_pointIT_T0_EE
+ __ZNSt3__118condition_variable8wait_forB9fqn220106IxNS_5ratioILl1ELl1000000000EEEEENS_9cv_statusERNS_11unique_lockINS_5mutexEEERKNS_6chrono8durationIT_T0_EE
+ __ZNSt3__16chrono12steady_clock3nowEv
+ __ZTVN2RB4Path6Mapper20IntermediateConsumerE
+ __ZTVZ21RBPathCopyBooleanPathE4Info
+ __ZTVZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS2_OT_E4Info
+ __ZZ21RBPathCopyBooleanPathE9callbacks
+ __ZZ21RBPathCopyBooleanPathEN3$_08__invokeEPKv
+ __ZZ21RBPathCopyBooleanPathEN3$_18__invokeEPKv
+ __ZZ21RBPathCopyBooleanPathEN3$_28__invokeEPKvPvPFbS2_13RBPathElementPKdS1_E
+ __ZZ21RBPathCopyBooleanPathEN3$_38__invokeEPKvS1_
+ __ZZ21RBPathCopyBooleanPathEN3$_48__invokeEPKv
+ __ZZ21RBPathCopyBooleanPathEN3$_58__invokeEPKv
+ __ZZ21RBPathCopyBooleanPathEN4InfoD0Ev
+ __ZZ21RBPathCopyBooleanPathEN4InfoD1Ev
+ __ZZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS2_OT_E9callbacks
+ __ZZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS2_OT_EN4InfoD0Ev
+ __ZZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS2_OT_EN4InfoD1Ev
+ __ZZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS2_OT_ENUlPKvE0_8__invokeES6_
+ __ZZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS2_OT_ENUlPKvE1_8__invokeES6_
+ __ZZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS2_OT_ENUlPKvE2_8__invokeES6_
+ __ZZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS2_OT_ENUlPKvE3_8__invokeES6_
+ __ZZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS2_OT_ENUlPKvE_8__invokeES6_
+ __ZZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS2_OT_ENUlPKvPvPFbS7_13RBPathElementPKdS6_EE_8__invokeES6_S7_SC_
+ __ZZN12_GLOBAL__N_117make_wrapped_pathIZ20RBPathCopyOffsetPathE10OffsetArgsEE6RBPathS2_OT_ENUlPKvS6_E_8__invokeES6_S6_
+ ___block_descriptor_45_e5_v8?0l
- -[CALayer kitView]
- GCC_except_table158
- _OBJC_CLASS_$_NSURL
- __ZN12_GLOBAL__N_114AnimationTimer17dispatch_handlersE13RBDisplayTypeP11objc_objectddRNSt3__111unique_lockIN2RB9spin_lockEEE
- ___block_descriptor_41_e5_v8?0l
- _dyld_image_path_containing_address
- _strstr
CStrings:
+ "8.0.84"
+ "frame %u may contain invalid results"
+ "shader-complex"
- "/RenderBox.framework"
- "/System/Library/PrivateFrameworks/RenderBox.framework"
- "8.0.79"
- "shader-copy"
```
