## Coordination

> `/System/Library/PrivateFrameworks/Coordination.framework/Coordination`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20378` | `0x1f5f0` | **`-0xd88`** |
| `__DATA_CONST.__objc_selrefs` | `0x1028` | `0xf78` | **`-0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x1040` | `0xfa0` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x1eac` | `0x1e1c` | **`-0x90`** |
| `__TEXT.__oslogstring` | `0x19a3` | `0x192b` | **`-0x78`** |
| `__DATA_CONST.__const` | `0xc50` | `0xbe0` | **`-0x70`** |
| `__TEXT.__cstring` | `0xe9b` | `0xe45` | **`-0x56`** |
| `__TEXT.__unwind_info` | `0x9d8` | `0x988` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1a0` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x3500` | `0x34d0` | **`-0x30`** |
| `__TEXT.__gcc_except_tab` | `0x5d4` | `0x5a4` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x1e0` | `0x1c0` | **`-0x20`** |
| `__AUTH_CONST.__objc_doubleobj` | `—` | `0x10` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x228` | `0x224` | **`-0x4`** |

### Other Changes

```diff

-249.0.0.0.0
+249.0.3.0.0

-  - /System/Library/PrivateFrameworks/CoreUtils.framework/CoreUtils

-  - /System/Library/PrivateFrameworks/MediaGroups.framework/MediaGroups

-  Functions: 838
-  Symbols:   1479
-  CStrings:  300
+  Functions: 825
+  Symbols:   1449
+  CStrings:  291
Symbols:
+ _OBJC_CLASS_$_NSConstantDoubleNumber
+ _RPOptionTimeoutSeconds
- +[COClusterRealm realmWithMediaGroup:]
- -[COClusterRealm _handleQueryResult:error:]
- -[COClusterRealm _identifierForGroupResult:]
- -[COClusterRealm _startQuery]
- -[COClusterRealm query]
- -[_COClusterRealmDynamicGroup _identifierForGroupResult:]
- -[_COClusterRealmExplicitMembership _identifierForGroupResult:]
- -[_COClusterRealmHome _identifierForGroupResult:]
- -[_COClusterRealmPair _identifierForGroupResult:]
- GCC_except_table15
- _CryptoHashDescriptorGetDigestSize
- _CryptoHashFinal
- _CryptoHashInit
- _CryptoHashUpdate
- _OBJC_CLASS_$_MGGroup
- _OBJC_CLASS_$_MGGroupQuery
- _OBJC_CLASS_$_MGHome
- _OBJC_CLASS_$_MGHomePodAccessory
- _OBJC_CLASS_$_MGMediaSystem
- _OBJC_CLASS_$_MGRoom
- _OBJC_CLASS_$_NSCompoundPredicate
- _OBJC_CLASS_$_NSMutableData
- _OBJC_IVAR_$_COClusterRealm._query
- __OBJC_$_INSTANCE_METHODS__COClusterRealmDynamicGroup
- __OBJC_$_INSTANCE_METHODS__COClusterRealmPair
- ___29-[COClusterRealm _startQuery]_block_invoke
- ___43-[COClusterRealm _handleQueryResult:error:]_block_invoke
- ___44-[COClusterRealm _identifierForGroupResult:]_block_invoke
- ___block_descriptor_32_e29_q24?0"MGGroup"8"MGGroup"16l
- ___block_descriptor_40_e8_32w_e29_v24?0"NSArray"8"NSError"16lw32l8
- ___block_descriptor_64_e8_32s40s48s56r_e5_v8?0ls32l8s40l8s48l8r56l8
- _kCryptoHashDescriptor_MD5
CStrings:
- "%hhX"
- "%p realm error querying groups %@"
- "%p realm identifier changing to %@ from %@"
- "%p received empty result, so no identifier"
- "($CURRENT_MEDIA_SYSTEM == nil)"
- "pair"
- "q24@?0@\"MGGroup\"8@\"MGGroup\"16"
- "r-mg-%lX-%@"
- "solo"
```
