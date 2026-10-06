## sptm.t8140.release.im4p

> `Firmware/sptm.t8140.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x5f33c` | `0x5f990` | **`+0x654`** |
| `__TEXT.__cstring` | `0x1543c` | `0x1571d` | **`+0x2e1`** |
| `__DATA_CONST.__const` | `0x7be8` | `0x7bf0` | **`+0x8`** |

### Same-size Content Changes

- `__LATE_CONST.__late_const`

### Other Changes

```diff

-820.0.16.0.0
-  Functions: 397
+820.0.22.0.0
+  Functions: 398

-  CStrings:  2516
+  CStrings:  2527
CStrings:
+ "%s: dart %p (%s:%u): DART instance %u: Attempt to modify locked reg at offset %x 0x%08x->0x%08x"
+ "%s: dart %p (%s:%u): DART instance %u: HW reported num_sids %u exceeds T8110_DART_MAX_SIDS %u"
+ "%s: dart %p (%s:%u): DART instance %u: SID %u: 3-level translation with noncompliant dead mappings and flush-by-DVA is unsupported on pre-Gen3 DARTs"
+ "%s: dart %p (%s:%u): DART instance %u: SID_CONFIG[%u] 0x%08x does not match shadow 0x%08x"
+ "%s: dart %p (%s:%u): DART instance %u: TTBR[%u] 0x%08x does not match shadow 0x%08x"
+ "%s: dart %p (%s:%u): DART instance %u: max_sid %#x doesn't match with the rest %#x"
+ "%s: non-canonical or unaligned output address %#llx"
+ "SPTM-820.0.22|2026-08-03:20:29:20.402231|"
+ "VIOLATION_T8110_DART_SID_TRANSLATION_DISABLED"
+ "hib_validate_io_buffer_page"
+ "sptm_t8110dart_sk_tlbi_request"
+ "t8110dart_read_dapf_reg"
+ "t8110dart_verify_sid_config"
+ "t8110dart_verify_sid_shadow_config"
- "%s: dart %p (%s:%u): DART instance %u: Attempt to modify locked reg %p 0x%08x->0x%08x"
- "SPTM-820.0.16|2026-07-10:21:28:53.721404|"
- "start_dva_offset"
```
