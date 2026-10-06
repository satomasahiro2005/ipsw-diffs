## exclave_pmm_exclave

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_pmm_exclave`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4cf50` | `0x4cdc8` | **`-0x188`** |
| `__TEXT.__cstring` | `0x11d63` | `0x11dc5` | **`+0x62`** |

### Same-size Content Changes

- `__DATA.__auth_ptr`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-1490.0.21.0.0
-  Functions: 1210
+1490.40.21.0.0
+  Functions: 1209

-  CStrings:  1513
+  CStrings:  1517
CStrings:
+ "!DO_CHUNKS_OVERLAP(currp, victimp) && !DO_CHUNKS_OVERLAP(currp->next, victimp)"
+ "!os_add_overflow(round_bytes, HEADER_UNIT_SIZE * UNIT_SIZE, &alloc_bytes)"
+ "!os_mul_overflow(units, UNIT_SIZE, &nb)"
+ "!overflow"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveCore.iPhoneOS.platform/Developer/SDKs/ExclaveCore.iPhoneOS27.2.Internal.sdk/System/ExclaveCore/System/Library/Frameworks/xrt.framework/Headers/thread.h"
+ "_insecure_random_buf"
+ "lcm"
+ "round_bytes >= alloc_bytes"
+ "s[0] || s[1]"
- "!(alignment % sizeof(Header)) && !(alignment % UNIT_SIZE)"
- "!os_mul_overflow(nu + PAD_ALLOC(align), UNIT_SIZE, &nb)"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveCore.iPhoneOS.platform/Developer/SDKs/ExclaveCore.iPhoneOS27.0.Internal.sdk/System/ExclaveCore/System/Library/Frameworks/xrt.framework/Headers/thread.h"
- "alloc_bytes >= sz"
- "p->size * UNIT_SIZE >= sizeof(Header)"
```
