## ManagedConfiguration

> `/System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf5478` | `0xf5c40` | **`+0x7c8`** |
| `__TEXT.__gcc_except_tab` | `0xd10` | `0x1020` | **`+0x310`** |
| `__AUTH_CONST.__cfstring` | `0x194c0` | `0x19580` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x2300` | `0x23a0` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x320` | `0x280` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x185c4` | `0x1865d` | **`+0x99`** |
| `__TEXT.__const` | `0x1454` | `0x14c4` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x4db8` | `0x4e10` | **`+0x58`** |
| `__DATA.__data` | `0xc40` | `0xc78` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x9227` | `0x925b` | **`+0x34`** |
| `__DATA.__bss` | `0xc79` | `0xc59` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x208` | `0x228` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3240` | `0x3258` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x5d88` | `0x5d90` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xb284` | `0xb28c` | **`+0x8`** |

### Other Changes

```diff

-2482.0.0.0.0
+2483.0.1.0.0

-  Functions: 5782
-  Symbols:   9648
-  CStrings:  4590
+  Functions: 5790
+  Symbols:   9672
+  CStrings:  4597
Symbols:
+ -[MCNotifier sendEnablingRestrictionsChangedNotification]
+ GCC_except_table20
+ _MCEnablingRestrictionsChangedNotification
+ _MCSendEnablingRestrictionsChangedNotification
+ ___block_descriptor_40_e8_32w_e8_v12?0i8lw32l8
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
+ "Sending enabling restrictions changed notification."
+ "VolumeBagVEKCacheStatus"
+ "com.apple.managedconfiguration.enablingrestrictionschanged"
```
