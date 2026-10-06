## com.apple.iokit.IOMobileGraphicsFamily-DCP

> `com.apple.iokit.IOMobileGraphicsFamily-DCP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x2a1b0` | `0x2ad00` | **`+0xb50`** |
| `__TEXT.__cstring` | `0x5e07` | `0x6069` | **`+0x262`** |
| `__DATA_CONST.__const` | `0x1e88` | `0x1e90` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 797
+  Functions: 800

-  CStrings:  491
+  CStrings:  499
CStrings:
+ "%s: dropped external_sync_error_notify message %llu\n"
+ "IOMFB: external_sync: pending notification found, delivering state=0x%llx\n"
+ "IOMFB: external_sync: userspace client registered for notifications\n"
+ "IOMFB: external_sync_error_notify_gated: delivered successfully to client %p\n"
+ "IOMFB: external_sync_error_notify_gated: no listeners registered, storing pending state=0x%llx\n"
+ "IOMFB: external_sync_error_notify_gated: sending to client %p\n"
+ "IOMFB: external_sync_error_notify_gated: state=0x%llx (late=%d expected_clock=%d incorrect_params=%d)\n"
+ "virtual void IOMobileFramebufferAP::genlock_error_notify_gated(uint64_t)"
```
