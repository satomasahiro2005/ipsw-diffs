## tailspind

> `/usr/libexec/tailspind`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe668` | `0xe888` | **`+0x220`** |
| `__TEXT.__oslogstring` | `0x29cc` | `0x2ab7` | **`+0xeb`** |
| `__TEXT.__cstring` | `0x134a` | `0x135f` | **`+0x15`** |
| `__TEXT.__auth_stubs` | `0xc50` | `0xc60` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x638` | `0x640` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x438` | `0x440` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-264.0.0.0.0
+267.0.0.0.0

-  Functions: 284
-  Symbols:   254
-  CStrings:  509
+  Functions: 286
+  Symbols:   255
+  CStrings:  513
Symbols:
+ _uuid_parse
CStrings:
+ "300MB buffer rollout: percent=%u, sampled=%{bool}d"
+ "Failed to parse kern.bootsessionuuid for 300MB buffer rollout sampling"
+ "Failed to read kern.bootsessionuuid for 300MB buffer rollout sampling: %{errno}d"
+ "is_12GB_or_greater: %{bool}d, is_feature_flag_enabled:  %{bool}d, is_in_rollout_sample: %{bool}d, is_300MB_eligible_device: %{bool}d, is_default_buffer_size: %{bool}d, is_game_mode_enabled: %{bool}d, should_apply_new_config: %{bool}d"
+ "kern.bootsessionuuid"
- "is_12GB_or_greater: %{bool}d, is_feature_flag_enabled:  %{bool}d, is_300MB_eligible_device: %{bool}d, is_default_buffer_size: %{bool}d, is_game_mode_enabled: %{bool}d, should_apply_new_config: %{bool}d"
```
