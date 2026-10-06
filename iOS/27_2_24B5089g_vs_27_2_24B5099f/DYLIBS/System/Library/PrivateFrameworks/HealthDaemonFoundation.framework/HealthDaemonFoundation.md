## HealthDaemonFoundation

> `/System/Library/PrivateFrameworks/HealthDaemonFoundation.framework/HealthDaemonFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x761a4` | `0x771a0` | **`+0xffc`** |
| `__TEXT.__gcc_except_tab` | `0x30a8` | `0x3118` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x3775` | `0x37e5` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x4100` | `0x4140` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x29f8` | `0x2a28` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x11c0` | `0x11e8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x3e0c` | `0x3e34` | **`+0x28`** |
| `__DATA.__bss` | `0x1d10` | `0x1d30` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4b4b` | `0x4b6b` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x8970` | `0x8988` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x21e0` | `0x21f8` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0xce4` | `0xcec` | **`+0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 3131
-  Symbols:   4006
-  CStrings:  912
+  Functions: 3144
+  Symbols:   4016
+  CStrings:  916
Symbols:
+ +[HDSQLiteSchemaEntity hasStaticJoinClauses]
+ -[HDSQLiteQueryDescriptor _uncachedJoinClauseForProperties:predicateJoinClauses:]
+ -[HDXPCProcess isFirstParty]
+ -[HDXPCProcess unitTest_copyProcessWithBundleIdentifier:]
+ GCC_except_table117
+ GCC_except_table120
+ GCC_except_table44
+ GCC_except_table67
+ GCC_except_table83
+ GCC_except_table88
+ GCC_except_table90
+ GCC_except_table96
+ __ZZL25_HDSQLiteCachedJoinClauseP10objc_classP7NSArrayIP8NSStringEU13block_pointerFS3_vEE15joinClauseCache
+ __ZZL25_HDSQLiteCachedJoinClauseP10objc_classP7NSArrayIP8NSStringEU13block_pointerFS3_vEE19joinClauseCacheLock
+ __ZZL25_HDSQLiteCachedJoinClauseP10objc_classP7NSArrayIP8NSStringEU13block_pointerFS3_vEE25reportedSaturatedEntities
+ ___52-[HDSQLiteQueryDescriptor _joinClauseForProperties:]_block_invoke
+ ___block_descriptor_56_ea8_32s40s48s_e15_"NSString"8?0ls32l8s40l8s48l8
- GCC_except_table113
- GCC_except_table118
- GCC_except_table84
- GCC_except_table87
- GCC_except_table89
- GCC_except_table92
- GCC_except_table95
CStrings:
+ "@\"NSString\"8@?0"
+ "Join clause memo reached its ceiling of %lu shapes for %{public}@; fragments for this entity are now rebuilt per query"
+ "[%s] Unable to open or prepare database due to error: %@"
+ "com.apple."
+ "com.appleinternal."
- "[%s] Unable to prepare database due to error: %@"
```
