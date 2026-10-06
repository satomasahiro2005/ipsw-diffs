## sptm.t8140.release.im4p

> `Firmware/sptm.t8140.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1535a` | `0x1543c` | **`+0xe2`** |
| `__DATA_CONST.__const` | `0x7bc8` | `0x7be8` | **`+0x20`** |
| `__TEXT_EXEC.__text` | `0x5f320` | `0x5f33c` | **`+0x1c`** |

### Same-size Content Changes

- `__LATE_CONST.__late_const`

### Other Changes

```diff

-820.0.8.0.0
-  Functions: 399
+820.0.16.0.0
+  Functions: 397

-  CStrings:  2510
+  CStrings:  2516
CStrings:
+ "%s: AMCC cache enabled unexpectedly: lock_group=%u aperture=%u plane=%u addr=%#llx read=%#x masked=%#x expected=%#x"
+ "%s: Invalid exception vector type: %s (%u) (current_hop=%llu, dispatch_state=%s)"
+ "%s: Provided CTXID %d does not fit in the ASID field"
+ "%s: Unexpected current_hop %llu (vector_type=%s (%u), dispatch_state=%s)"
+ "%s: lock group %u %s region has been locked unexpectedly (write_disabled=%d locked=%d)"
+ "%s: region %s page size does not agree, shift count: %u"
+ "INVALID_DISPATCH_STATE"
+ "INVALID_EVENT_TYPE"
+ "INVALID_VECTOR_TYPE"
+ "SPTM-820.0.16|2026-07-10:21:28:53.721404|"
+ "SPTM_VECTOR_FIQ"
+ "SPTM_VECTOR_IRQ"
+ "SPTM_VECTOR_SERROR"
+ "SPTM_VECTOR_SYNC"
+ "internal-isa-vm-allowed"
+ "tlbi_info_for_tlbi_asid"
- "%s: %u is not a valid dispatch event type (valid dispatch event types are 0 - %u)"
- "%s: %u is not a valid dispatch state (valid dispatch states are 0 - %u)"
- "%s: AMCC cache has been enabled unexpectedly"
- "%s: Invalid exception vector type: %u"
- "%s: Unexpected current_hop %llu"
- "%s: lock group %u %s region has been locked unexpectedly"
- "%s: region %s page size does not agree, shift count: %d"
- "SPTM-820.0.8|2026-06-26:21:27:04.769007|"
- "event_type_to_string"
- "state_to_string"
```
