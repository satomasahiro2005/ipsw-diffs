## PlatformSSOCore

> `/System/Library/PrivateFrameworks/PlatformSSOCore.framework/PlatformSSOCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x96e70` | `0x974e0` | **`+0x670`** |
| `__AUTH_CONST.__cfstring` | `0x7a40` | `0x7b20` | **`+0xe0`** |
| `__TEXT.__cstring` | `0xac4c` | `0xad0a` | **`+0xbe`** |
| `__TEXT.__const` | `0x18e4` | `0x1954` | **`+0x70`** |
| `__AUTH_CONST.__objc_intobj` | `0x1c8` | `0x228` | **`+0x60`** |
| `__DATA.__data` | `0x11d0` | `0x1200` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x6c4` | `0x6f4` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x25d8` | `0x2600` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2cb0` | `0x2cd8` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x14cb8` | `0x14c98` | **`-0x20`** |
| `__DATA.__bss` | `0x761` | `0x771` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2158` | `0x2168` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xdb0` | `0xdb8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x64c` | `0x648` | **`-0x4`** |

### Other Changes

```diff

-643.0.12.0.0
+643.0.21.0.0

-  Functions: 3832
-  Symbols:   5790
-  CStrings:  1750
+  Functions: 3838
+  Symbols:   5811
+  CStrings:  1758
Symbols:
+ GCC_except_table55
+ _CFArrayContainsValue
+ _CFArrayGetCount
+ _NSFileGroupOwnerAccountID
+ _NSFileOwnerAccountID
+ ___der_key_group_seed_generation
+ ___der_key_group_seed_kcv
+ ___der_key_group_seed_wrapping_type
+ ___der_key_group_user_count
+ ___der_key_vek_group_seed_generation
+ ___der_key_volume_bag_vek_cache_status
+ __sharedPrebootKey
+ _aks_unlock_bag_with_options
+ _der_key_group_seed_generation
+ _der_key_group_seed_kcv
+ _der_key_group_seed_wrapping_type
+ _der_key_group_user_count
+ _der_key_vek_group_seed_generation
+ _der_key_volume_bag_vek_cache_status
+ _kAKSInternalInfoGroupSeedGeneration
+ _kAKSInternalInfoGroupSeedKCV
+ _kAKSInternalInfoGroupSeedWrappingType
+ _kAKSInternalInfoGroupUserCount
+ _kAKSInternalInfoVolumeBagVEKCacheStatus
+ _pdk_generate
- GCC_except_table42
- GCC_except_table49
- _OBJC_IVAR_$_PODaemonCoreProcess._prebootKey
- _swift_willThrowTypedImpl
CStrings:
+ "$"
+ "Failed to create parent directory for config write"
+ "Failed to create parent directory for trigger file"
+ "GroupSeedGeneration"
+ "GroupSeedKCV"
+ "GroupSeedWrappingType"
+ "GroupUserCount"
+ "VolumeBagVEKCacheStatus"
```
