## sptm.t8140.release.im4p

> `Firmware/sptm.t8140.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1571d` | `0x15859` | **`+0x13c`** |
| `__TEXT_EXEC.__text` | `0x5fa2c` | `0x5fa5c` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x7bf0` | `0x7bf8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__auth_ptr`
- `__LATE_CONST.__late_const`

### Other Changes

```diff

-820.0.22.0.0
-  Functions: 398
+820.40.18.0.0
+  Functions: 399

-  CStrings:  2527
+  CStrings:  2536
CStrings:
+ "%s(%s:%d) - fte(%p), new_type(%s), page_flags(%u), read_refcnt(%d) iommu_read_refcnt(%u)\n"
+ "%s: %s: iommu_read_refcnt (0x%hhx) > read_refcnt(0x%x) for FTE %p"
+ "%s: unexpected size %u for property '%s'"
+ "/chosen/manifest-properties"
+ "SPTM-820.40.18|2026-09-04:20:09:28.017559|"
+ "VIOLATION_NVME_ILLEGAL_HIBERNATION_QUEUE_LATCH"
+ "enforce_no_hib_latch"
+ "internal-use-only-unit"
+ "iuos"
+ "sptm_allow_vm_isa_internal_guests"
+ "sptm_is_iuou_or_iuos_device"
- "%s(%s:%d) - fte(%p), new_type(%s), page_flags(%u), read_refcnt(%d)\n"
- "SPTM-820.0.22|2026-08-08:13:24:32.076410|"
```
