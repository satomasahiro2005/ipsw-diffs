## CoreCDP

> `/System/Library/PrivateFrameworks/CoreCDP.framework/CoreCDP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f250` | `0x4f4c8` | **`+0x278`** |
| `__AUTH_CONST.__cfstring` | `0x3dc0` | `0x3e80` | **`+0xc0`** |
| `__TEXT.__const` | `0x13b4` | `0x1424` | **`+0x70`** |
| `__TEXT.__cstring` | `0x6536` | `0x65a4` | **`+0x6e`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x1040` | `0x1090` | **`+0x50`** |
| `__DATA.__data` | `0x1120` | `0x1150` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2fa0` | `0x2fd0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1648` | `0x1658` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x870` | `0x878` | **`+0x8`** |

### Other Changes

```diff

-442.0.0.0.0
+444.0.0.0.0

-  Functions: 2393
-  Symbols:   3852
-  CStrings:  1632
+  Functions: 2398
+  Symbols:   3873
+  CStrings:  1638
Symbols:
+ _CDPFollowUpItemUserInfoKeyTelemetryFlowID
+ _CFArrayContainsValue
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
+ "GroupSeedGeneration"
+ "GroupSeedKCV"
+ "GroupSeedWrappingType"
+ "GroupUserCount"
+ "VolumeBagVEKCacheStatus"
+ "telemetryFlowID"
```
