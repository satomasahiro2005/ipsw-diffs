## ReplicatorCore

> `/System/Library/PrivateFrameworks/ReplicatorCore.framework/ReplicatorCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ceec` | `0x7efe8` | **`+0x20fc`** |
| `__TEXT.__const` | `0xf88` | `0x1288` | **`+0x300`** |
| `__DATA.__bss` | `0x380` | `0x600` | **`+0x280`** |
| `__AUTH.__data` | `0x1b0` | `0x360` | **`+0x1b0`** |
| `__AUTH_CONST.__objc_const` | `0x1bf0` | `0x1da0` | **`+0x1b0`** |
| `__TEXT.__constg_swiftt` | `0xdb8` | `0xf48` | **`+0x190`** |
| `__AUTH_CONST.__const` | `0x1028` | `0x1170` | **`+0x148`** |
| `__TEXT.__oslogstring` | `0x2596` | `0x26d6` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0xec1` | `0xff9` | **`+0x138`** |
| `__TEXT.__swift5_fieldmd` | `0x730` | `0x7dc` | **`+0xac`** |
| `__TEXT.__unwind_info` | `0xd38` | `0xdc0` | **`+0x88`** |
| `__TEXT.__swift5_reflstr` | `0x6cd` | `0x753` | **`+0x86`** |
| `__TEXT.__swift5_assocty` | `—` | `0x60` | **`+0x60`** |
| `__DATA.__data` | `0x7c0` | `0x7f0` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x2020` | `0x1ff0` | **`-0x30`** |
| `__TEXT.__cstring` | `0x9e6` | `0xa06` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x68` | `0x88` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1968` | `0x1980` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x80` | `0x90` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xa0` | `0xb0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x398` | `0x3a8` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x68` | `0x78` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x2c` | `0x38` | **`+0xc`** |
| `__DATA_DIRTY.__data` | `0x1418` | `0x1420` | **`+0x8`** |

### Other Changes

```diff

-176.0.0.0.0
+176.2.2.0.0

-  Functions: 924
-  Symbols:   631
-  CStrings:  232
+  Functions: 1021
+  Symbols:   660
+  CStrings:  238
Symbols:
+ _OBJC_CLASS_$_BSBuildVersion
+ __DATA__TtC14ReplicatorCore18SystemDataMigrator
+ __DATA__TtC14ReplicatorCore38SystemDataMigratorBuildVersionProvider
+ __IVARS__TtC14ReplicatorCore18SystemDataMigrator
+ __IVARS__TtC14ReplicatorCore38SystemDataMigratorBuildVersionProvider
+ __METACLASS_DATA__TtC14ReplicatorCore18SystemDataMigrator
+ __METACLASS_DATA__TtC14ReplicatorCore38SystemDataMigratorBuildVersionProvider
+ ___swift_memcpy8_8
+ _associated conformance 14ReplicatorCore18SystemDataMigratorC16MigrationReasonsVs10SetAlgebraAASQ
+ _associated conformance 14ReplicatorCore18SystemDataMigratorC16MigrationReasonsVs10SetAlgebraAAs25ExpressibleByArrayLiteral
+ _associated conformance 14ReplicatorCore18SystemDataMigratorC16MigrationReasonsVs9OptionSetAASY
+ _associated conformance 14ReplicatorCore18SystemDataMigratorC16MigrationReasonsVs9OptionSetAAs0I7Algebra
+ _free
+ _swift_coroFrameAlloc
+ _symbolic $s14ReplicatorCore25SystemDataMigratorStoringP
+ _symbolic $s14ReplicatorCore28SystemDataMigratorPerformingP
+ _symbolic $s14ReplicatorCore39SystemDataMigratorBuildVersionProvidingP
+ _symbolic $sSY
+ _symbolic $ss10SetAlgebraP
+ _symbolic $ss25ExpressibleByArrayLiteralP
+ _symbolic $ss9OptionSetP
+ _symbolic _____ 14ReplicatorCore18SystemDataMigratorC
+ _symbolic _____ 14ReplicatorCore18SystemDataMigratorC16MigrationReasonsV
+ _symbolic _____ 14ReplicatorCore23SystemDataMigratorStoreV
+ _symbolic _____ 14ReplicatorCore27SystemDataMigratorPerformerV
+ _symbolic _____ 14ReplicatorCore38SystemDataMigratorBuildVersionProviderC
+ _symbolic ______p 14ReplicatorCore25SystemDataMigratorStoringP
+ _symbolic ______p 14ReplicatorCore28SystemDataMigratorPerformingP
+ _symbolic ______p 14ReplicatorCore39SystemDataMigratorBuildVersionProvidingP
+ _type_layout_string 14ReplicatorCore18SystemDataMigratorC16MigrationReasonsV
- _symbolic _____ 14ReplicatorCore18SystemDataMigratorV
CStrings:
+ "Cached %{public}s and current %{public}s build versions do not match"
+ "Current build version is unknown"
+ "Last known build version is unknown"
+ "Stored and current build versions match %{public}s; bypassing migration check"
+ "Updating current build version from %{public}s to %{public}s"
+ "lastKnownBuildVersion"
```
