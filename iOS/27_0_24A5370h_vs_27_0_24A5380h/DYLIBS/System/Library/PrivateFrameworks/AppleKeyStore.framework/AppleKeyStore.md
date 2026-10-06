## AppleKeyStore

> `/System/Library/PrivateFrameworks/AppleKeyStore.framework/AppleKeyStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62958` | `0x62b78` | **`+0x220`** |
| `__AUTH_CONST.__cfstring` | `0x760` | `0x800` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x33ef` | `0x348f` | **`+0xa0`** |
| `__TEXT.__const` | `0x11013` | `0x11073` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x24c0` | `0x24f0` | **`+0x30`** |
| `__DATA.__data` | `0x1478` | `0x14a8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x62b8` | `0x62e0` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0xcb0` | `0xcb8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1738` | `0x1740` | **`+0x8`** |

### Other Changes

```diff

-2383.0.6.0.1
+2383.0.14.0.1

-  Functions: 2829
-  Symbols:   2627
-  CStrings:  747
+  Functions: 2836
+  Symbols:   2647
+  CStrings:  754
Symbols:
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
+ "groupSeedNeedsRoll"
+ "groupSeedProposed"
```
