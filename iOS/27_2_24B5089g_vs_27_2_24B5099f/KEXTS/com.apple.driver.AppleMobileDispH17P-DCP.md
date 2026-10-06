## com.apple.driver.AppleMobileDispH17P-DCP

> `com.apple.driver.AppleMobileDispH17P-DCP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x25cd0` | `0x262e0` | **`+0x610`** |
| `__TEXT.__cstring` | `0x73f8` | `0x77f0` | **`+0x3f8`** |
| `__DATA_CONST.__const` | `0x50e8` | `0x5100` | **`+0x18`** |

### Other Changes

```diff

-700.50.104.1.0
-  Functions: 1477
+700.50.108.0.0
+  Functions: 1481

-  CStrings:  598
+  CStrings:  610
Functions:
+ sub_fffffff00922687c
+ sub_fffffff009228fac
+ sub_fffffff00922fac0
~ __ZN23IOMobileFramebufferShim10swap_startEPjP12IOUserClient : 360 -> 448
~ __ZN23IOMobileFramebufferShim29set_config_requires_dual_pipeEv : 224 -> 284
~ __ZN23IOMobileFramebufferShim20set_digital_out_modeEjj : 7216 -> 8500
+ sub_fffffff009247f3c
CStrings:
+ "%s: Dual pipe: fb %u issuing secondary modeset on fb %u (timing %u color %u)\n"
+ "%s: Dual pipe: fb %u primary VFTG link check done in %u ms, localStatus %u\n"
+ "%s: Dual pipe: fb %u primary modeset thread finished in %u ms, status 0x%x\n"
+ "%s: Dual pipe: fb %u waiting for primary VFTG link check, timeout %u ms\n"
+ "%s: Dual pipe: fb %u waiting for primary modeset thread, timeout %u ms\n"
+ "%s: Skipping redundant modeset (timing=%u, color=%u)\n"
+ "%s: modeset: fb %u is_dual=%d adm_forced=%d vftg_cfg=%d paired=%d hpd_dual_ok=%d timing=%u color=%u (%ux%u@%uHz)\n"
+ "%s: modeset: fb %u set_digital_out_mode returning 0x%x (timing %u color %u dual %d)\n"
+ "AED: fb %u could not read ADM pipe-count intent (0x%x); modesetting as single pipe\n"
+ "Dual pipe: fb %u issuing secondary modeset on fb %u (timing %u color %u)\n"
+ "Dual pipe: fb %u primary VFTG link check done in %u ms, localStatus %u\n"
+ "Dual pipe: fb %u primary modeset thread finished in %u ms, status 0x%x\n"
+ "Dual pipe: fb %u waiting for primary VFTG link check, timeout %u ms\n"
+ "Dual pipe: fb %u waiting for primary modeset thread, timeout %u ms\n"
+ "Skipping redundant modeset (timing=%u, color=%u)\n"
+ "dual pipe: rejected swap_start on secondary fb %u (client %p)"
+ "modeset: fb %u is_dual=%d adm_forced=%d vftg_cfg=%d paired=%d hpd_dual_ok=%d timing=%u color=%u (%ux%u@%uHz)\n"
+ "modeset: fb %u set_digital_out_mode returning 0x%x (timing %u color %u dual %d)\n"
- "%s: AED: Skipping spurious modeset (timing=%u, color=%u, is_dual=%d unchanged, intent toggled %d->%d)\n"
- "%s: Merge Config: Primary VFTG enable time %dms\n"
- "%s: Primary modeset time %dms\n"
- "AED: Skipping spurious modeset (timing=%u, color=%u, is_dual=%d unchanged, intent toggled %d->%d)\n"
- "Merge Config: Primary VFTG enable time %dms\n"
- "Primary modeset time %dms\n"
```
