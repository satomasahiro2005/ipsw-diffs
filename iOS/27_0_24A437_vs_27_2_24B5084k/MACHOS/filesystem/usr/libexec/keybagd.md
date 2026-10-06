## keybagd

> `/usr/libexec/keybagd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21c00` | `0x21d40` | **`+0x140`** |
| `__TEXT.__cstring` | `0x9d7d` | `0x9e1b` | **`+0x9e`** |
| `__DATA_CONST.__cfstring` | `0x4e80` | `0x4ea0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x480` | `0x464` | **`-0x1c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-697.0.6.0.0
+697.40.4.0.0

-  CStrings:  1499
+  CStrings:  1503
Functions:
~ sub_1000084d8 : 956 -> 1024
~ sub_100008984 -> sub_1000089c8 : 948 -> 1008
~ sub_10000a3f4 -> sub_10000a474 : 960 -> 1028
~ sub_10000f9a0 -> sub_10000fa64 : 1360 -> 1372
~ sub_10000fef0 -> sub_10000ffc0 : 2332 -> 2380
~ sub_100013914 -> sub_100013a14 : 256 -> 292
~ sub_1000154c8 -> sub_1000155ec : 2168 -> 2196
CStrings:
+ "AnalyticsEvent: report_version: %llu, grace_period: %llu, failed_unlock_attempts: %llu, max_unlock_attempts: %llu, recovery_iterations: %llu, recovery_target_iterations: %llu, recovery_wc_protected: %llu, recovery_restricted: %llu, recovery_ps_protected: %llu, recovery_akpu_protected: %llu, recovery_auto: %llu, memento_supported: %llu, memento_exists: %llu, memento_passcode_generation: %llu, passcode_generation: %llu, inactivity_reboot_enabled: %llu, oneness_automatic_mode: %llu, user_uuid_mismatch: %llu, zero_user_uuid: %llu, group_uuid_mismatch: %llu, zero_group_uuid: %llu, keybag_state_no_pin: %llu, keybag_state_been_unlocked: %llu, keybag_state_passcode_threshold: %llu, keybag_state_mesa_token: %llu, keybag_state_recovery_required: %llu, keybag_state_not_recoverable: %llu, keybag_state_stash_unlocked: %llu, keybag_state_escrow_unwrap_required: %llu, keybag_state_smdk_entangled: %llu, keybag_state_staged_manifest: %llu, keybag_state_se_unrecoverable: %llu, keybag_state_se_recovery_required: %llu, keybag_state_se_entangled: %llu, keybag_state_se_healthy: %llu, keybag_state_se_been_unlocked: %llu, keybag_state_art_loaded: %llu, keybag_state_xart_unlock_policy: %llu, keybag_state_xart_policy_cached: %llu, keybag_state_xart_policy_dirty: %llu, keybag_state_xart_policy_enforced: %llu, keybag_state_ps_entangled: %llu, keybag_state_from_xart: %llu, keybag_state_allow_test_keys: %llu, keybag_state_remote_session_unlocked: %llu, keybag_state_has_group_seed: %llu, keybag_state_been_passcode_unlocked: %llu, keybag_state_has_auto_recovery: %llu, keybag_state_has_lkgp_recovery: %llu, keybag_state_has_fv_recovery: %llu, keybag_state_has_memento_blob: %llu, keybag_more_state_cx_expiring: %llu, keybag_more_state_cx_expired: %llu, keybag_more_state_recovery_ps_fua_cached: %llu, keybag_more_state_unlocked_with_escrow: %llu, keybag_more_state_oneness_assert: %llu, keybag_more_state_peer_records_dirty: %llu, keybag_more_state_peer_records_flush: %llu, keybag_more_state_se_input_uid_bound: %llu, keybag_more_state_cache_flow_enabled: %llu, hours_since_locked: %llu, cx_hours_remaining: %llu, days_since_passcode_change: %llu, memento_flags_blob_exists: %llu, memento_flags_se: %llu, memento_flags_ps: %llu, memento_flags_se_reset_token: %llu, memento_flags_tombstone: %llu, memento_failed_unlock_attempts: %llu, memento_se_slot: %llu, aks_get_extended_device_state_failure: %llu, AKSIdentityGetSessionTimeWindowsFailure: %llu, aks_get_seconds_since_passcode_change_failure: %llu, aks_memento_get_state_failure: %llu, aks_get_configuration_failure: %llu, handle: %llu, is_primary_user: %llu, is_shared_ipad: %llu, supports_enhanced_apfs: %llu, AKSIdentityGetPrimary_failure: %llu, keybag_more_state_group_seed_proposed: %llu, keybag_more_state_group_seed_needs_roll: %llu, group_seed_generation: %llu, group_seed_wrapping_type: %llu, group_user_count: %llu, volume_bag_vek_cache_status: %llu, aks_get_internal_info_failure: %llu, vek_user_bound: %llu, vek_sys_bound: %llu, vek_proposed: %llu, vek_group_uuid_match: %llu, vek_group_seed_generation: %llu, vek_blob_state_failure: %llu, heap_size: %llu, heap_free: %llu, heap_allocated_max: %llu, heap_offset_max: %llu"
+ "corrupt keysize %u in db entry (max %zu), not returning it"
+ "get_backup_key"
+ "heap_allocated_max"
+ "heap_offset_max"
- "AnalyticsEvent: report_version: %llu, grace_period: %llu, failed_unlock_attempts: %llu, max_unlock_attempts: %llu, recovery_iterations: %llu, recovery_target_iterations: %llu, recovery_wc_protected: %llu, recovery_restricted: %llu, recovery_ps_protected: %llu, recovery_akpu_protected: %llu, recovery_auto: %llu, memento_supported: %llu, memento_exists: %llu, memento_passcode_generation: %llu, passcode_generation: %llu, inactivity_reboot_enabled: %llu, oneness_automatic_mode: %llu, user_uuid_mismatch: %llu, zero_user_uuid: %llu, group_uuid_mismatch: %llu, zero_group_uuid: %llu, keybag_state_no_pin: %llu, keybag_state_been_unlocked: %llu, keybag_state_passcode_threshold: %llu, keybag_state_mesa_token: %llu, keybag_state_recovery_required: %llu, keybag_state_not_recoverable: %llu, keybag_state_stash_unlocked: %llu, keybag_state_escrow_unwrap_required: %llu, keybag_state_smdk_entangled: %llu, keybag_state_staged_manifest: %llu, keybag_state_se_unrecoverable: %llu, keybag_state_se_recovery_required: %llu, keybag_state_se_entangled: %llu, keybag_state_se_healthy: %llu, keybag_state_se_been_unlocked: %llu, keybag_state_art_loaded: %llu, keybag_state_xart_unlock_policy: %llu, keybag_state_xart_policy_cached: %llu, keybag_state_xart_policy_dirty: %llu, keybag_state_xart_policy_enforced: %llu, keybag_state_ps_entangled: %llu, keybag_state_from_xart: %llu, keybag_state_allow_test_keys: %llu, keybag_state_remote_session_unlocked: %llu, keybag_state_has_group_seed: %llu, keybag_state_been_passcode_unlocked: %llu, keybag_state_has_auto_recovery: %llu, keybag_state_has_lkgp_recovery: %llu, keybag_state_has_fv_recovery: %llu, keybag_state_has_memento_blob: %llu, keybag_more_state_cx_expiring: %llu, keybag_more_state_cx_expired: %llu, keybag_more_state_recovery_ps_fua_cached: %llu, keybag_more_state_unlocked_with_escrow: %llu, keybag_more_state_oneness_assert: %llu, keybag_more_state_peer_records_dirty: %llu, keybag_more_state_peer_records_flush: %llu, keybag_more_state_se_input_uid_bound: %llu, keybag_more_state_cache_flow_enabled: %llu, hours_since_locked: %llu, cx_hours_remaining: %llu, days_since_passcode_change: %llu, memento_flags_blob_exists: %llu, memento_flags_se: %llu, memento_flags_ps: %llu, memento_flags_se_reset_token: %llu, memento_flags_tombstone: %llu, memento_failed_unlock_attempts: %llu, memento_se_slot: %llu, aks_get_extended_device_state_failure: %llu, AKSIdentityGetSessionTimeWindowsFailure: %llu, aks_get_seconds_since_passcode_change_failure: %llu, aks_memento_get_state_failure: %llu, aks_get_configuration_failure: %llu, handle: %llu, is_primary_user: %llu, is_shared_ipad: %llu, supports_enhanced_apfs: %llu, AKSIdentityGetPrimary_failure: %llu, keybag_more_state_group_seed_proposed: %llu, keybag_more_state_group_seed_needs_roll: %llu, group_seed_generation: %llu, group_seed_wrapping_type: %llu, group_user_count: %llu, volume_bag_vek_cache_status: %llu, aks_get_internal_info_failure: %llu, vek_user_bound: %llu, vek_sys_bound: %llu, vek_proposed: %llu, vek_group_uuid_match: %llu, vek_group_seed_generation: %llu, vek_blob_state_failure: %llu, heap_size: %llu, heap_free: %llu"
```
