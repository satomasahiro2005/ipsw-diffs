## com.apple.driver.AppleM2ScalerCSCDriver

> `com.apple.driver.AppleM2ScalerCSCDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1407e8` | `0x140ed0` | **`+0x6e8`** |
| `__TEXT.__cstring` | `0x2515b` | `0x2534c` | **`+0x1f1`** |
| `__TEXT.__const` | `0xc3090` | `0xc3140` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x2abf0` | `0x2ac90` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0xb0` | `0xb8` | **`+0x8`** |

### Other Changes

```diff

-200.62.4.0.0
-  Functions: 10262
+200.66.0.0.0
+  Functions: 10275

-  CStrings:  3704
+  CStrings:  3714
CStrings:
+ "\"[%s] \" \"Failed to load MsrCPU firmware %s: MSR%u scaler %u path=%s embedded=%u imem0=0x%08x apImg0=0x%08x bootProgress=%s(0x%08x) bootEntries=%u running=0x%08x ibootFw=%d ctrrLock=%u ctrrWrDis=%u\\n\" @%s:%d"
+ "%.4s"
+ "121111121222121211111111111221221121121212212222"
+ "12111121221111111222"
+ "121111212211111112222"
+ "12111121221111111222222"
+ "1211112122111111122222211222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222"
+ "AP"
+ "Histogram bin count (%ld) exceeds maximum (%d)"
+ "arenaReturnPage"
+ "command %u in use but has no packet sequence (valid=%u)\n"
+ "command %u sequence list spans two requests (%p != %p)\n"
+ "deferring arena release during flush, queue length %u\n"
+ "for PG"
+ "for reset (postInit)"
+ "for reset (resetScaler)"
+ "iBoot"
+ "reclaimed %u PIODMA command(s), released %u MSR power ref(s), refCount now %u\n"
+ "reclaiming PIODMA command idx=%u tag=%u transformId=%d powerRefOutstanding=%d release=%d\n"
- "\"[%s] \" \"Failed to load MsrCPU firmware for PG\\n\" @%s:%d"
- "\"[%s] \" \"Failed to load MsrCPU firmware for reset\\n\" @%s:%d"
- "12111112122212121111111111122122112112112212222"
- "121111211111111222"
- "1211112111111112222"
- "121111211111111222222"
- "12111121111111122222211222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222"
- "Histogram bin count (%d) exceeds maximum (%d)"
- "command %d not valid!"
```
