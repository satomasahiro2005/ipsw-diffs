## com.apple.iokit.IONVMeFamily

> `com.apple.iokit.IONVMeFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x5bea0` | `0x5c590` | **`+0x6f0`** |
| `__TEXT.__cstring` | `0x102c8` | `0x10469` | **`+0x1a1`** |
| `__DATA_CONST.__const` | `0xe3d8` | `0xe448` | **`+0x70`** |

### Other Changes

```diff

-877.0.0.0.0
-  Functions: 3578
+877.0.3.0.0
+  Functions: 3588

-  CStrings:  1749
+  CStrings:  1760
CStrings:
+ "%s::%d:fCompletionLoops: %d\n"
+ "%s::%d:nvme: CORE_DEBUG_EXPORT_STATS failed with status 0x%x\n"
+ "%s::%d:nvme: ParseSanitizeCounters: maxElements < elements\n"
+ "%s::%d:nvme: Sanitize counter keyNum: %u value: 0x%016llx\n"
+ "SanitizeDone"
+ "SanitizeFailed"
+ "SanitizeStart"
+ "nvme-completion-loops"
+ "sanitize-counters"
+ "virtual IOReturn AppleANS2NVMeController::GetSanitizeCounters()"
+ "virtual bool IONVMeController::InitializeController()"
+ "virtual void AppleANS2NVMeController::ParseSanitizeCounters(uint8_t *)"
- "( inNumDwords <= NVMeFieldMax ( kNVMeGetLogPageNumDwordsLen ) )"
```
