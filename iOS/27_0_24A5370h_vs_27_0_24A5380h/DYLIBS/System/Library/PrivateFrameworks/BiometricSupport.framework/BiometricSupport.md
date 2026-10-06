## BiometricSupport

> `/System/Library/PrivateFrameworks/BiometricSupport.framework/BiometricSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e7d0` | `0x4ea48` | **`+0x278`** |
| `__AUTH.__objc_data` | `0x190` | `0xf0` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x2160` | `0x2200` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x780` | `0x820` | **`+0xa0`** |
| `__TEXT.__const` | `0x1324` | `0x1394` | **`+0x70`** |
| `__TEXT.__cstring` | `0x6f53` | `0x6fb1` | **`+0x5e`** |
| `__DATA.__data` | `0xbd8` | `0xc08` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1ac0` | `0x1ae8` | **`+0x28`** |
| `__DATA_DIRTY.__bss` | `0x80` | `0x98` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x820` | `0x830` | **`+0x10`** |
| `__DATA.__bss` | `0x61` | `0x51` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1048` | `0x1058` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x3735` | `0x3733` | **`-0x2`** |

### Other Changes

```diff

-573.0.0.0.0
+575.0.0.0.0

-  Functions: 2010
-  Symbols:   2723
-  CStrings:  1229
+  Functions: 2015
+  Symbols:   2744
+  CStrings:  1234
Symbols:
+ _CFArrayContainsValue
+ _CFArrayGetCount
+ ___der_key_group_seed_generation
+ ___der_key_group_seed_kcv
+ ___der_key_group_seed_wrapping_type
+ ___der_key_group_user_count
+ ___der_key_vek_group_seed_generation
+ ___der_key_volume_bag_vek_cache_status
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
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-575~90, %s file: %s, line: %d\n\n"
+ "GroupSeedGeneration"
+ "GroupSeedKCV"
+ "GroupSeedWrappingType"
+ "GroupUserCount"
+ "VolumeBagVEKCacheStatus"
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-573~1109, %s file: %s, line: %d\n\n"
```
