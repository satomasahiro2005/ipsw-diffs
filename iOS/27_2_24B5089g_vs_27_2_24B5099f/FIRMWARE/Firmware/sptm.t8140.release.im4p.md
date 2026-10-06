## sptm.t8140.release.im4p

> `Firmware/sptm.t8140.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x5fa30` | `0x60778` | **`+0xd48`** |
| `__TEXT.__cstring` | `0x1587f` | `0x15b39` | **`+0x2ba`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`
- `__TEXT.__chain_starts`

### Other Changes

```diff

-820.40.20.0.0
-  Functions: 399
+820.40.23.0.0
+  Functions: 401

-  CStrings:  2537
+  CStrings:  2550
CStrings:
+ "%s: Failed to verify TLBI"
+ "%s: The GMMU TLBI verification register should be 8B-aligned"
+ "%s: UAT Dekker gate acquisition timed out after %llu ns (spun for %llu cycles)"
+ "%s: UAT Dekker lock acquisition timed out after %llu ns (spun for %llu cycles)"
+ "%s: dart %p (%s:%u): relaxed_rw_protections and allow_pte_remap are not supported together"
+ "%s: gmmu-tlbi-verification-bit (%llu) is unset or out of range [0, 63]"
+ "%s: verify-gmmu-tlbis-at-sync is enabled but gmmu-tlbi-verification-reg is not set"
+ "0x4B1D000000000003ULL"
+ "SPTM-820.40.23|2026-09-27:19:59:11.633384|"
+ "gmmu-tlbi-verification-bit"
+ "gmmu-tlbi-verification-reg"
+ "hib_header_copy->handoffPageCount < HIB_HANDOFF_PAGECOUNT_LIMIT"
+ "uat_dekker_gate_lock"
+ "uat_dekkerlock_lock"
+ "uat_sync_outer_tlb_sapt_flush"
+ "verify-gmmu-tlbis-at-sync"
- "0x4B1D000000000002ULL"
- "SPTM-820.40.20|2026-09-13:19:38:35.360456|"
- "wrprot"
```
