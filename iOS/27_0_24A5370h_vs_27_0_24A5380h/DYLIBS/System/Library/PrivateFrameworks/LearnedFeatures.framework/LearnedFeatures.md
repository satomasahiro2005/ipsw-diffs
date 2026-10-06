## LearnedFeatures

> `/System/Library/PrivateFrameworks/LearnedFeatures.framework/LearnedFeatures`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2312b0` | `0x232cbc` | **`+0x1a0c`** |
| `__AUTH.__objc_data` | `0x370` | `—` | **`-0x370`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x370` | **`+0x370`** |
| `__TEXT.__gcc_except_tab` | `0x16a08` | `0x167a0` | **`-0x268`** |
| `__TEXT.__const` | `0x193a0` | `0x192e0` | **`-0xc0`** |
| `__DATA.__bss` | `0x8e8` | `0x848` | **`-0xa0`** |
| `__DATA.__common` | `0xb0` | `0x150` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xcf88` | `0xcf0b` | **`-0x7d`** |
| `__AUTH_CONST.__const` | `0x10598` | `0x10610` | **`+0x78`** |
| `__TEXT.__eh_frame` | `0x3c0` | `0x438` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x80c0` | `0x8110` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0xa68` | `0xa88` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x310` | `0x330` | **`+0x20`** |

### Other Changes

```diff

-9.26.5.12.5
+9.26.6.16.5

-  Functions: 5606
-  Symbols:   572
-  CStrings:  1040
+  Functions: 5634
+  Symbols:   580
+  CStrings:  1039
Symbols:
+ __ZNKSt3__119bad_expected_accessIvE4whatEv
+ __ZTINSt3__119bad_expected_accessIvEE
+ _e5rt_io_port_is_surface
+ _e5rt_io_port_retain_surface_desc
+ _e5rt_surface_desc_get_custom_row_strides
+ _e5rt_surface_desc_get_height
+ _e5rt_surface_desc_get_plane_count
+ _e5rt_surface_desc_get_width
+ _e5rt_surface_desc_release
- _snprintf
CStrings:
+ " : "
+ "(null)"
+ "-"
+ "CV3D_LF_ATUHardNetGlobalFeat_E2E/"
- " : %.*s"
- "%s: %s:%d"
- "CV3D_LearnedFeatures_ATUHardNetGlobalFeat_EndToEnd_Model/"
- "Copy not supported yet."
- "p32_64u_u8_3_7_0_6aa24xpnhm_b1024_gf_i_128f_u8_3_7_0_a3p73mmcsz_b1/model"
```
