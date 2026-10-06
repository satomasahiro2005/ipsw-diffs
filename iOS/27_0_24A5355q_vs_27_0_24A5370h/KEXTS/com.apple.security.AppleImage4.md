## com.apple.security.AppleImage4

> `com.apple.security.AppleImage4`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x7b0` | **`+0x7b0`** |
| `__TEXT_EXEC.__text` | `0x23f2c` | `0x23fe0` | **`+0xb4`** |
| `__DATA_CONST.__const` | `0xd340` | `0xd350` | **`+0x10`** |
| `__TEXT.__const` | `0xe828` | `0xe830` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-372.0.0.0.0
+374.0.0.0.0
Functions:
~ sub_fffffff008fcff30 -> sub_fffffff008ffcdb0 : 48 -> 72
~ __image4_trust_post_properties : 252 -> 280
~ __image4_trust_find_record : 216 -> 232
~ __darwin_trap_ignition_set_failure : 432 -> 464
~ __image4_gl2_cs_trap_kmod_set_release_type : 336 -> 344
~ ___panic_npx : 1124 -> 1144
~ sub_fffffff008fd8dbc -> sub_fffffff009005cbc : 116 -> 120
~ __Z31_darwin_el2_finalize_supervisorPK7_expert : 628 -> 624
~ _kmod_expert_finalize : 236 -> 240
~ __ZL33_darwin_el2_query_property_uint32PK7_expertPK5_chipPK9_propertyPj : 308 -> 304
~ sub_fffffff008fe02a4 -> sub_fffffff00900d1a4 : 152 -> 140
~ _odometer_compute_nonce_hash : 420 -> 440
~ __chip_decode_select_dynamic : 1320 -> 1336
~ sub_fffffff008fe9894 -> sub_fffffff0090167ac : 720 -> 724
~ sub_fffffff008fea4a8 -> sub_fffffff0090173c4 : 436 -> 440
~ sub_fffffff008fea65c -> sub_fffffff00901757c : 592 -> 588
~ sub_fffffff008fec69c -> sub_fffffff0090195b8 : 124 -> 128
~ _darwin_trap_proc_desc : 180 -> 184
~ sub_fffffff008fecca8 -> sub_fffffff009019bcc : 84 -> 88
~ sub_fffffff008fecd14 -> sub_fffffff009019c3c : 132 -> 136
~ sub_fffffff008fecdf4 -> sub_fffffff009019d20 : 112 -> 116
~ sub_fffffff008fece64 -> sub_fffffff009019d94 : 112 -> 116
CStrings:
+ "374"
+ "@(#)VERSION:Darwin Image4 Extension Version 7.0.0: Thu Jun 18 19:34:19 PDT 2026; root:AppleImage4-374~4898/AppleImage4/RELEASE_ARM64E"
+ "Darwin Image4 Extension Version 7.0.0: Thu Jun 18 19:34:19 PDT 2026; root:AppleImage4-374~4898/AppleImage4/RELEASE_ARM64E"
- "372"
- "@(#)VERSION:Darwin Image4 Extension Version 7.0.0: Wed May 27 22:46:10 PDT 2026; root:AppleImage4-372~1183/AppleImage4/RELEASE_ARM64E"
- "Darwin Image4 Extension Version 7.0.0: Wed May 27 22:46:10 PDT 2026; root:AppleImage4-372~1183/AppleImage4/RELEASE_ARM64E"
```
